# ForenSight — AI Digital Forensics Concepts Study Kit

A responsive, beginner-friendly digital forensics learning project built with **HTML, CSS and vanilla JavaScript**. It is designed as a GitHub-ready educational project.

## Features

- 8 concise digital forensics learning modules
- Interactive fictional USB evidence-handling scenario
- 5-question knowledge-check quiz with feedback and score
- Built-in concept coach with guided explanations
- Searchable mini glossary
- Learning progress indicator
- Responsive layout for desktop, tablet and mobile
- No build tools, frameworks, backend or API key required

## Important note about the "AI" coach

The included coach is a **local rule-based study assistant**, not a live large language model. It runs entirely in the browser and does not transmit questions to an external service. This keeps the project easy to run and safe to publish as a beginner portfolio project. A future version could connect to an AI API through a secure backend; never place private API keys in browser-side JavaScript.

## Run locally

1. Download or clone this repository.
2. Open `index.html` in a modern browser.

No installation is required.

## Publish to GitHub

1. Create a new repository on GitHub, for example `ai-digital-forensics-study-kit`.
2. Extract this ZIP file.
3. Upload the files and folders inside the extracted project folder to the repository root.
4. Commit the files.
5. Optional: In **Settings → Pages**, choose the `main` branch and `/ (root)` folder to publish the site with GitHub Pages.

## Project structure

```text
ai-digital-forensics-study-kit/
├── index.html
├── README.md
├── LICENSE
├── .gitignore
└── assets/
    ├── app.js
    └── style.css
```

## Learning topics

1. Foundations of digital forensics
2. Evidence and chain of custody
3. Forensic acquisition and imaging
4. Hashing and evidence integrity
5. File systems and metadata
6. Operating-system and browser artefacts
7. Network and mobile forensics
8. Analysis, reporting and ethics

## Scope and responsible use

This project is for education only. The practice case uses fictional information and does not access devices, files, networks or accounts. Real forensic work must be authorised and performed by trained people using validated tools, applicable laws and organisational procedures. Do not use the project to access, alter or collect data without permission.

## Customisation ideas

- Add modules for cloud forensics, memory forensics and malware analysis.
- Add flashcards and spaced-repetition review.
- Add a backend-based AI tutor with server-side API-key protection.
- Add references to textbooks, standards and official tool documentation.
- Add unit tests and accessibility checks.

## License

MIT — see [LICENSE](LICENSE).
