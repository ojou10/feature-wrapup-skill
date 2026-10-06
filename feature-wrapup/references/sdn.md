# Technical SDN: Summary, Decisions, Next steps

Create `feature-name-sdn.md` as the editable source, then export `feature-name-sdn.pdf`. The two files must make the same claims and preserve usable context pointers. Write for developers, maintainers, reviewers, and other readers who need to continue the work.

Use exactly these three main sections, in order. A short title and metadata above them are fine; put tests, limitations, or screenshots within the relevant section rather than adding a fourth main section.

## 1. Summary

State the feature boundary, what is verified complete, what remains, and the important technical limits. Link each material item to the best available source: PR, commit, issue, design decision, test, documentation, or repository file. Say what was tested and what was not verified. Prefer a concise status table or bullets to a narrative history.

## 2. Decisions needing answers

List only open decisions. For each, give the question, why it matters, known options or trade-offs, a pointer to the discussion or code context, and owner or decision date only if documented. If no decision is open, say so explicitly. Keep already-made decisions in the Summary with their records.

## 3. Next available steps

List actionable steps in a useful order. Include prerequisites, the expected result, and a pointer to the relevant issue, code, test, or document. Distinguish work ready now from work waiting on a decision or dependency. Do not invent assignments or dates.

## Pointers and export

- Use stable remote URLs when available. In Markdown, repository-relative links are acceptable when the document will stay in that repository; in a portable PDF, prefer absolute URLs. If only a local path exists, label it as local context and explain that it may not work for other readers.
- Preserve clickable links in the PDF. Check a representative link from each section after rendering.
- If a source is unavailable, state the gap plainly instead of adding a placeholder link.
- Screenshots are optional. Include them only when they clarify a UI state or flow better than the linked implementation evidence.
