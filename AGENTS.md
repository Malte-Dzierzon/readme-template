# readme-template agent rules

Respond in the user's language (German unless they switch).

## Source of truth

- `TEMPLATE.md` defines the README structure. Its HTML comment header holds
  binding agent instructions — follow them, never copy them into output.
- `README.md` describes this repo. Keep it short; it is not an example.

## When writing a project README from TEMPLATE.md

- Fill every `{{PLACEHOLDER}}`; delete blocks with no content. No empty
  sections, no TODOs, no lorem ipsum.
- Keep the skeleton, rename sections per project type (see comment in
  `TEMPLATE.md`). Don't invent new top-level patterns.
- Badge grammar: `flat-square`, `labelColor=070e15` everywhere, spaces as
  `%20` or `-`, hex colors without `#`.
- `<details>` blocks: `<summary><b>Name</b></summary>`, blank line after
  `<summary>`, blank line before `</details>`, or GitHub won't render
  inner markdown. Max ~3 blocks per section.
- Max 2 hero images (`width="1200"`), thumbnails link to full size.
  Gallery section only with 3+ visuals, else delete it.
- No emoji. No TOC under ~150 rendered lines.

## Operating loop

Inspect (project layout, existing docs/assets) → Decide (which sections
survive) → Implement → Verify (raw markdown read-back, links resolve,
images exist). Done only when verified.
