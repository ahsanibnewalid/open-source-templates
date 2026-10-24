# Education & Learning Platforms

For course delivery, learning portals, student-facing websites, and educational administration. These are larger platforms, not merely visual themes.

| Project | What to explore | Stack / notes |
|---|---|---|
| [Moodle](https://github.com/moodle/moodle) | Learning management system | PHP; plugins and themes have their own compatibility and licensing considerations |
| [Open edX](https://github.com/openedx) | Online learning platform ecosystem | Multiple services; plan hosting and operations carefully |
| [Canvas LMS](https://github.com/instructure/canvas-lms) | Learning management system | Ruby on Rails ecosystem; evaluate deployment complexity |
| [Tutor](https://github.com/overhangio/tutor) | Open edX deployment tooling | Docker-based deployment workflow |
| [Django](https://github.com/django/django) | Build a custom education portal | Framework foundation rather than a complete LMS |

**Customization ideas:** admissions pages, course catalog, student/teacher dashboards, attendance, assignments, results, fee statements, notifications, and parent access.

**Critical for real student data:** verify privacy and data-retention requirements, enforce role and record-level access on the server, use test data during development, and complete a security review before importing live records.
