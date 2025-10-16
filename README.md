# PiCode

AI-supported live coding and IoT learning module integrated with Moodle LMS.

## Summary
PiCode is a learning module designed to bring live coding and IoT hands-on activities into Moodle-based courses. It integrates live coding environments and hardware interaction so instructors can deliver interactive exercises and labs inside existing LMS workflows.

## Key features
- Live coding exercises embedded in Moodle pages
- Basic IoT device communication (sensors/actuators) for student labs
- Auto-grading hooks and activity reporting compatible with Moodle gradebook
- Lightweight AI-assisted hints for students (configurable)

## Tech stack
- Moodle plugin / LTI-compatible integration
- Backend: (example) Node.js / Python Flask (adjust to repo)
- Frontend: HTML/CSS/JS, WebSocket for live code execution
- Optional: Raspberry Pi / microcontroller support via REST/WebSocket bridge

## Quick start
1. Place the plugin files in your Moodle plugin folder and enable in Site administration → Plugins.
2. Configure the IoT bridge endpoint and credentials in plugin settings.
3. Add "PiCode activity" to a course, create an exercise, and assign to students.

## Contributing
Please open issues for feature requests or bugs. Include steps to reproduce and environment details.

