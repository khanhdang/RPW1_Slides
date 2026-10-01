# Research Paper Writing Seminar I (RPW1)

Marp lecture materials for the University of Aizu's Research Paper Writing Seminar I, AY2026, S2 (Q3 and Q4). The course focuses on scientific writing, paper structure, evidence, citation, peer review, and revision, using examples from computer science and engineering.

## Repository and editing workflow

- Read `COURSE_CONTEXT.md` at session start, and any nested `AGENTS.md` files relevant to the session being edited.
- Edit `session-NN/lecture.md` as the source. Preserve the `session-NN` directory names; the repository currently contains Session 01.
- Preserve `marp: true`, `theme: event-course`, and `paginate: true`. Keep the title and footer consistent with the session and academic year.
- Shared styling is in `themes/event-course.css`. The `event-course` name is retained from the original template and is still used by the deck. Register this CSS as a custom theme in the Marp preview/export tool when needed; there is currently no `.vscode/settings.json`.
- Keep session-specific media in that session's `images/` or `videos/` folder, with relative paths from `lecture.md`. Editable SVG diagrams are in `images/diagrams/`.
- Keep slides concise, with one main idea. Put fuller explanations, activity prompts, source credits, and verification notes in HTML comments for Marp speaker notes.
- Preview with Marp for VS Code; export with “Marp: Export Slide Deck...” or Marp CLI with the custom theme. Inspect rendered output after layout changes.
- PDF, HTML, and PPTX files are exports. Regenerate requested outputs from Markdown rather than editing exports as the source.
- `README.md` currently contains only the repository title; it does not yet document the editing or export workflow.

## Teaching and content guidance

- Use clear, precise English and examples accessible across computer science and engineering fields. Emphasize the research question, contribution, supporting evidence, and limitations.
- Present papers as a way to communicate discoveries. Favor research quality and clear reasoning over publication counts or impressive language.
- Distinguish hypothetical teaching examples from measured research results. Verify factual claims and references against original sources; do not invent results, citations, or research gaps.
- Session 01 is adapted from a 2025 lecture. Keep its survey results labeled as the 2025 class, and preserve source credits when reusing figures or material.
- Use the AY2026 syllabus for the course topic plan and grading split, and current ELMS announcements for class dates, activities, deadlines, and detailed course rules. Do not carry old activity links or dates forward without checking them.
- Preserve the current assignment flow unless the user provides an update: individual paper drafts, three independent student reviews at midterm, revision addressing all three reviewers, and three student reviews in the final round. Instructors grade drafts and reviews.
- Explain generative AI use in terms of checking meaning, claims, and references, with students responsible for their submissions. Follow current course and venue policies for permitted use and disclosure.
- Describe publication and peer-review practices with appropriate venue-specific qualifications; section structures, reviewer roles, anonymity, and revision procedures vary.

## Course topic plan

This is a topic plan, not a confirmed timetable. Check ELMS for dates, order changes, and invited lecturers.

Session 1: Introduction to Research Paper Writing (RPW1)
Session 2: Literature Survey and Review
Session 3: Paper Structure and Organization
Session 4: Scientific Expression and Clarity
Session 5: Writing the Title and Abstract
Session 6: Writing the Introduction
Session 7: Writing Technical Content (Part 1)
Session 8: Writing Technical Content (Part 2)
Session 9: Presenting and Interpreting Results
Session 10: Paper Formatting, Submission, and Ethical Considerations
Session 11: Revision and Rebuttal
Session 12: Invited Talk by a PhD Student/Postdoc
Session 13: Invited Talk by a Conference/Journal Chair
Session 14: Invited Talk by a Journal Editor
