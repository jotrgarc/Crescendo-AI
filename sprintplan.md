🗓️ Sprint Plan: Crescendo MVP
🔧 Tech Stack Assumptions
Frontend: React or Next.js

Backend: Node.js + Express or Firebase

Database: PostgreSQL or Firestore

AI: Custom model + Music21 (Python) or API integration (e.g. OpenAI, Note-level models)

Storage: AWS S3 or Firebase Storage

🔁 Sprint 0: Prep & Setup (1–3 days)
Goal: Set up dev environment, define scope, finalize requirements

Tasks:

✅ Finalize MVP features

✅ Set up GitHub repo & CI/CD

✅ Select AI tools for arrangement engine

✅ Create wireframes for user upload & arrangement flow

✅ Define user personas & test cases

Deliverables:

Internal design doc

Wireframes (Figma or similar)

Tech stack confirmed

🚀 Sprint 1: Core Upload + AI Engine (Week 1)
Goal: Users can upload sheet music and receive an auto-leveled version

Tasks:

 Build upload UI (PDF / MusicXML only for MVP)

 Parse input using backend (Music21 or similar)

 Integrate AI module to adapt music to chosen level

 Generate simplified MusicXML output

 Generate and return downloadable PDF

Deliverables:

Working file upload + level selection flow

First arrangement logic complete (basic level adaptation)

Sheet music outputs available in MusicXML & PDF

🎼 Sprint 2: Playback + User System (Week 2)
Goal: Logged-in users can hear playback and save arrangements

Tasks:

 Auth system (email/password or Google)

 MIDI playback player with visual follow

 Save user arrangements to library

 User profile (basic settings + instrument + level)

 Improve AI fidelity with rhythmic simplification

Deliverables:

Functional playback

Arrangement history saved by user

More intelligent arrangements (e.g. removing complex chords)

🧪 Sprint 3: Teacher Tools + Polishing (Week 3)
Goal: Add minimal teacher support + polish UX

Tasks:

 Add teacher toggle (assign simplified piece to a student)

 Allow annotations/notes on scores

 Basic dashboard with arrangement stats

 UI refinement (loading states, errors, help pop-ups)

Deliverables:

First draft of teacher dashboard

Streamlined experience

QA-ready version

✅ Sprint 4: Testing + Launch (Week 4)
Goal: Final bug fixes, user testing, launch beta

Tasks:

 Run internal + external testing with 5–10 students

 Gather structured feedback

 Fix bugs, polish UI

 Launch landing page for public signups

 Deploy MVP

Deliverables:

Beta MVP live

Feedback doc with action items

Signup page & short demo video

💡 Post-MVP Next Steps
Add image → MusicXML via OCR (Photo upload)

Dynamic difficulty suggestions based on student’s playing data

Expand to more instruments and styles (e.g. jazz, choral)

Mobile version

In-app practice tracking
