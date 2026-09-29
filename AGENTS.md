# Notes authoring guide

## Goal
Create clear, accurate study notes that are easy to understand on the first read and easy to navigate in the GitHub browser.

## Workflow
- The user will provide raw notes, excerpts, corrections, or ideas in chat or in an open file.
- Treat that material as source notes. Organize and rewrite it into polished Markdown files in the appropriate subject folder.
- Preserve the user's intended meaning and useful details. Correct spelling, grammar, confusing phrasing, and obvious structural problems. Do not silently invent facts; flag uncertainty or verify factual claims when needed.
- Keep explanations simple and direct. Define unfamiliar terms briefly where they first appear. Use examples, timelines, and step-by-step sequences when they make a topic easier to follow.
- Avoid needless repetition while retaining information useful for exams and revision.

## Markdown and navigation
- Use descriptive headings in a logical hierarchy, starting with one H1 title and then H2/H3 sections.
- Add a linked table of contents for long notes. Use relative Markdown links for links between files and fragment links for sections within a file.
- When a topic should connect to another section, link the relevant phrase to its heading or file. Prefer GitHub-compatible heading anchors; keep headings stable and readable.
- Use tables for compact comparisons or chronological summaries, and lists for grouped facts. Keep tables readable on narrow screens.
- Use bold sparingly for key terms, dates, people, and exam takeaways.
- Write valid GitHub-flavored Markdown. Avoid HTML or formatting that does not render reliably on GitHub.

## Accuracy and editing
- Preserve distinctions between proposals, criticism, historical claims, and established facts; attribute opinions to their sources or speakers.
- Keep dates, names, figures, and quotations precise. If the source notes conflict or appear incomplete, investigate or mark the point for review rather than guessing.
- Make focused edits to the relevant notes file. Do not reorganize unrelated files or add unrequested sections.
- Do not run tests or other verification commands unless the user asks. For documentation changes, inspect the resulting Markdown for clarity and working navigation when requested.
