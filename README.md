# StudyFlow

**Your school, organized automatically.**

StudyFlow is a privacy-first, offline-capable native iOS study command center for iPhone and iPad. It brings assignments, planning, scanning, study materials, on-device AI study tools, a smart timer, school calendar, widgets, and a utility toolbox together in one app.

## Features

### Planner & Assignments

* Today view with recommended next tasks
* Quick Add and detailed assignment editing
* Priorities, estimated effort, notes, rescheduling, and undo
* Deterministic study planning based on deadlines, effort, priority, exams, and available time
* Filtering and search by status, class, title, and notes

### Homework Scanner

* Camera capture or photo-library import
* On-device text recognition using Apple Vision
* Editable confirmation before saving
* Uncertain OCR results are clearly flagged instead of silently accepted

### Materials

* Store PDFs, images, scans, notes, and imported files
* Organize materials by subject
* On-device text extraction and local search
* Associate materials with assignments
* Spotlight indexing

### Study AI

On-device study tools using Apple's Natural Language framework:

* Summarizer
* Concept Explainer
* Flashcards
* Interactive Quiz

AI output is treated as a study aid, not authoritative school data.

### Study Timer

* Assignment-linked study sessions
* Planned durations
* Pause/resume and breaks
* Interruption logging
* Session history
* Completion is always confirmed by the user

### School Calendar

* School-focused day view
* Assignments, exams, deadlines, and study sessions
* Exam countdowns with preparation windows

### Offline Utility Toolbox

1. Grade Calculator
2. What-If Grade Calculator
3. Weighted Grade Calculator
4. GPA Calculator
5. Percentage Calculator
6. Unit Converter
7. Word & Character Counter
8. Exam & Assignment Countdown
9. Random Group Generator
10. Study Session History

### Google Classroom

Optional, read-only integration for importing classes and coursework. OAuth tokens are stored in the device Keychain. Classroom is the only external service integration, and every other feature works without connecting it.

### iOS Integration

* Home Screen widgets
* Local notifications
* App Intents & Shortcuts
* Spotlight indexing

## Privacy

StudyFlow is local-first. Assignments, planner data, materials, and study history are stored on the device by default.

* No ads
* No tracking SDKs
* No analytics in the app
* No account required
* No data sold
* Full offline functionality except optional Google Classroom sync
* OAuth secrets stored only in Keychain

## Distribution

StudyFlow is currently distributed directly as a signed `.ipa` for sideloading rather than through the App Store.

**Platform:** iOS
**Bundle ID:** `com.Study-Tracking-AIO`
