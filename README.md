# NEXUS — Student Resource Sharing Platform

NEXUS is a responsive front-end prototype for an international student community to discover, organize, save, and share study resources in Italian, English, and Spanish.

## Current features

- Responsive desktop and mobile layout
- Italian / English / Spanish interface toggle
- Search by title, topic, author, description, and subject
- Subject and document-language filters
- Demonstration material cards and detail modal
- Save / unsave materials using browser localStorage
- Local demo upload form with a PDF file selector
- Demonstration study tools: summary, quiz prompt, flashcards, translation preview
- Demonstration report form
- No build step or external JavaScript dependencies

## Run locally

1. Download or clone this repository.
2. Open `index.html` in a modern browser.

For a local development server, if Python is installed, run:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Important prototype limitations

This is a front-end demo, not a production service. It does **not** currently include:
- real user registration or authentication
- a backend or database
- cloud file storage or public uploads
- real moderation/report submission
- AI model integration
- production PDF viewing
- payment or subscription processing

Uploads and reports are local demonstrations only. Saved items use the current browser's localStorage. Do not upload confidential documents or personal data.

## Suggested next technical milestones

1. Add a backend/database for user accounts, materials, metadata, and reports.
2. Add authenticated cloud storage with file type/size checks and access controls.
3. Add moderation workflows and copyright reporting.
4. Connect an AI provider for document-grounded summaries, quizzes, and flashcards.
5. Add privacy, security, accessibility, and legal review before public launch.

## Copyright and safety

Only share original materials or resources you have permission to distribute. Do not upload copyrighted books or personal information without a lawful basis and appropriate authorization.

## License

No license has been granted yet. Add a license only after deciding how the project code may be reused.
