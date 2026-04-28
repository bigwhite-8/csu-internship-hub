# csu-internship-hub

## Overview
`csu-internship-hub` is a front-end project for students in the School of Resources and Safety Engineering at Central South University (CSU).  
It provides a single-page platform that combines:
- internship and employment guidance content,
- a community sharing board (post/like/comment),
- and curated external resources relevant to internship and job preparation.

The repository is intended for academic and portfolio presentation on GitHub, with emphasis on clarity and maintainability.

## Live Demo
[Live Demo link to be added]

## Features
- **Guide section** with structured content for major-specific paths, interview preparation, and a 90-day action plan.
- **Employment extension** in addition to internship-oriented guidance.
- **Search and filtering** for both guide content and community posts.
- **Community board** backed by Supabase (post creation, likes, comments, and admin delete flow).
- **External resource aggregation** with categorized internship/employment links and fallback curated sources.
- **Media attachments** in posts (image compression and PDF preview/download support).

## Tech Stack
- **Frontend:** HTML, CSS, JavaScript (React 18 via CDN + Babel standalone)
- **UI:** Tailwind CSS (CDN)
- **Backend service:** Supabase (database interactions for community posts)
- **Data integration:** Browser-side fetch + DOM parsing for external links

## Screenshots
Screenshots are stored (or should be stored) in the `figures/` directory.

Suggested screenshots:
- `figures/home-guide.png` — Guide homepage / hero area
- `figures/community-board.png` — Community board view
- `figures/resource-aggregation.png` — External resource aggregation panel
- `figures/post-modal.png` — Post creation modal with attachment options

> Please replace placeholders with actual screenshots after capture.

## Project Structure
```text
csu-internship-hub/
├── CHANGELOG.md
├── README.md
├── index.html
└── figures/
    └── README.md
```

## Author
- Maintainer: Repository owner
- Affiliation context: School of Resources and Safety Engineering, Central South University
