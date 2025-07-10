🧩 Crescendo – Data Model
🔵 User
Field	Type	Notes
user_id	UUID	Primary Key
name	String	Full name
email	String	Unique
password_hash	String	Securely stored
role	Enum (student, teacher)	For future multi-user support
level	Integer (1–10)	User's default level
instrument	String	e.g., "piano", "cello"
created_at	Timestamp	
last_login	Timestamp	

🔵 SheetMusic
Field	Type	Notes
sheet_id	UUID	Primary Key
user_id	UUID (FK)	Uploader’s ID
title	String	Title of the piece
composer	String	Optional
original_format	Enum (PDF, MusicXML, Image)	
file_url	String	Path to original file
created_at	Timestamp	

🔵 Arrangement
Field	Type	Notes
arrangement_id	UUID	Primary Key
sheet_id	UUID (FK)	Linked to SheetMusic
user_id	UUID (FK)	Creator (if different from uploader)
target_level	Integer (1–10)	Desired difficulty level
mode	Enum (simplify, challenge, practice)	Arrangement mode
instrument	String	Target instrument
style_preserved	Boolean	If stylistic integrity is preserved
file_url_pdf	String	Final sheet as PDF
file_url_musicxml	String	Final MusicXML (optional)
playback_url	String	MIDI or audio playback
created_at	Timestamp	

🔵 Feedback
Field	Type	Notes
feedback_id	UUID	Primary Key
arrangement_id	UUID (FK)	Related to which arrangement
user_id	UUID (FK)	Who gave the feedback
rating	Integer (1–5)	Satisfaction score
comments	Text	Optional notes
created_at	Timestamp	

🔵 TeacherStudentLink (Optional for future)
Field	Type	Notes
teacher_id	UUID	FK to User where role = teacher
student_id	UUID	FK to User where role = student
relationship_id	UUID	Primary Key
status	Enum (active, inactive, pending)	

🔗 Relationships
A User can upload many SheetMusic items.

A SheetMusic can have many Arrangements.

A User can have many Arrangements.

A User can leave Feedback on many Arrangements.

Future: A Teacher can be linked to many Students.
