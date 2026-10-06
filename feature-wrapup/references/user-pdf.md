# User PDF: screenshot-led feature update

Write for the people who will use the feature. Explain what they can now do, where to find it, and what still needs work. Prefer observable behavior over implementation vocabulary.

## Content shape

1. **Opening page:** Feature name, release or work package if known, a one-minute overview, and an immediately visible **Done / What's left** summary. Do not imply that a deferred item shipped.
2. **Workflow pages:** Group by module or task. For each meaningful step, pair a real screenshot with a short title and a few concise explanations. State the action, resulting behavior, and any important permission or error state. One screenshot per page is a useful starting point, not a fixed rule.
3. **Closing page:** Expand on remaining work, material limitations, and the next expected steps. Add pointers to full release notes, help pages, issues, or a technical SDN when those exist.

If the feature is small, combine pages. If screenshots or evidence are missing, keep the gap visible rather than padding the document.

## Visual direction

The source example uses landscape pages, broad margins, a small section label above a strong title, brief text beside a large application screenshot, and a quiet footer with page number. Adapt that composition to the target product and the amount of content. Extract its palette, typography, logo, and UI spacing from actual assets or screens; do not reuse the source example's brand.

Keep screenshot text readable at normal viewing size. Crop to the relevant UI state without hiding essential context. Use captions or labels when the screenshot alone is ambiguous. Keep status colors semantically consistent with the product. Avoid placing large screenshots on pages where they shrink below readable size.

## Accuracy and privacy

- Use actual captures of the implementation or clearly identified supplied screenshots. Never create a synthetic UI image and present it as evidence of a real feature.
- Use demo data or redact customer names, personal information, tokens, internal URLs, and sensitive figures.
- State environment-specific limits, such as missing demo configuration, as limits of the demonstration rather than general product behavior.
- Attribute unverified or future behavior accurately: **planned**, **in progress**, **blocked**, or **unknown** as appropriate.

## Final check

Render and inspect every page. Confirm the first page and closing page agree on what remains, every screenshot illustrates its adjacent claim, and footer/page numbering is consistent.
