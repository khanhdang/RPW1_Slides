# Slides context

Marp lecture materials for the Event Sensor Course. Read README.md for the editing and export workflow.
- Read ../COURSE_CONTEXT.md at session start for the user's course structure and teaching preferences when available in this workspace.
- Read nested AGENTS.md files at session start when opening Slides directly.
- Edit session-NN/lecture.md as the source. Preserve the existing session-NN names even though README.md also mentions weekNN.
- Preserve marp: true, theme: event-course, and paginate: true in existing decks. The actual decks use the shared custom theme rather than the README's default-theme example.
- Shared styling is in themes/event-course.css; .vscode/settings.json registers it for Marp.
- Use concise slides with one main idea and relative media paths. Keep session-specific media in that session's images/ or videos/ folder.
- Preview with Marp for VS Code; export with “Marp: Export Slide Deck...”. Inspect rendered output after layout changes.
- PDF, HTML, and PPTX files are exports. Regenerate requested outputs from Markdown rather than treating exports as the source.
- Related device examples are in ../Labs/. This directory is its own Git repository.

- Session 01 uses Colab variables/for loops and an instructor camera demonstration. Session 02 holds board setup, extended Python practice, histogram display, and flash/microSD exercises; keep the matching lab guides and slides aligned.
