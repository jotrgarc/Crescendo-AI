🧩 Backlog: Epics & User Stories for Crescendo MVP
🟣 EPIC 1: User Authentication & Profile Management
Goal: Allow students and teachers to log in, set preferences, and save progress.

User Story ID	User Story
US1.1	As a user, I want to create an account so I can save my arrangements.
US1.2	As a user, I want to log in securely so my data is protected.
US1.3	As a student, I want to select my instrument and skill level so arrangements are tailored to me.
US1.4	As a teacher, I want to create a teacher account so I can manage students (future feature).

🟣 EPIC 2: Sheet Music Upload & Processing
Goal: Enable users to upload sheet music files (PDF or MusicXML) for processing.

User Story ID	User Story
US2.1	As a user, I want to upload PDF or MusicXML files so I can adapt them to my level.
US2.2	As a user, I want to see a confirmation that the file was uploaded successfully.
US2.3	As a user, I want to preview the original sheet music after upload.

🟣 EPIC 3: AI-Powered Arrangement Engine
Goal: Transform input sheet music into level-appropriate arrangements.

User Story ID	User Story
US3.1	As a student, I want to select a difficulty level so the arrangement suits my skills.
US3.2	As a user, I want to choose between simplification or practice mode so I can tailor the output to my goal.
US3.3	As a user, I want to receive a simplified version of my uploaded music that matches my selected level.
US3.4	As a user, I want the output to maintain the style of the original music (optional for MVP).
US3.5	As a user, I want to download the new sheet music as a PDF or MusicXML.

🟣 EPIC 4: Audio Playback & Practice Tools
Goal: Let users listen to arrangements and practice effectively.

User Story ID	User Story
US4.1	As a student, I want to listen to the adapted arrangement so I can hear how it should sound.
US4.2	As a user, I want to follow along visually as the sheet music plays back.
US4.3	As a student, I want to adjust playback speed so I can practice slowly.

🟣 EPIC 5: Saved Arrangements & History
Goal: Let users manage their adapted pieces.

User Story ID	User Story
US5.1	As a user, I want to see a library of my adapted arrangements so I can revisit them later.
US5.2	As a user, I want to rename or delete saved arrangements.
US5.3	As a user, I want to duplicate a past arrangement with a different difficulty level.

🟣 EPIC 6: Feedback & Ratings
Goal: Gather user feedback for continuous improvement.

User Story ID	User Story
US6.1	As a user, I want to rate how helpful an arrangement was so the system can improve.
US6.2	As a user, I want to leave comments on my experience.
US6.3	As a teacher, I want to see feedback from students so I can track their progress.

🟣 EPIC 7: Admin & Infrastructure
Goal: Build backend tools for app stability and scale.

User Story ID	User Story
US7.1	As a developer, I want to log arrangement requests for debugging.
US7.2	As a system, I want to validate file types and size limits.
US7.3	As a system, I want to notify the user if file parsing fails.
US7.4	As a developer, I want metrics on most-used levels/instruments.

(Optional) 🟣 EPIC 8: Teacher Dashboard (Future)
User Story ID	User Story
US8.1	As a teacher, I want to assign sheet music to students.
US8.2	As a teacher, I want to see student progress by level.
US8.3	As a teacher, I want to leave annotations on assigned music.

✅ Prioritization for MVP (MoSCoW Method)
Priority	Features
Must Have	US1.1–1.3, US2.1–2.3, US3.1–3.3, US4.1, US5.1, US6.1, US7.2–7.3
Should Have	US3.4, US4.2, US5.2
Could Have	US4.3, US5.3, US6.2
Won’t Have (MVP)	All EPIC 8 + US1.4, US6.3, US7.4
