<!-- ================================================================
AGENT INSTRUCTIONS — invisible when rendered. Do NOT copy this
comment block into the generated README. Follow it, then delete it.

GOAL: write a clean, compact README for the current project that
follows the structure below. Fill every {{PLACEHOLDER}}. Delete any
block that has no content (no empty sections, no TODOs).

GLOBAL RULES
1. Scannable in under 2 minutes. Depth goes into <details> blocks
   or linked docs — never into long prose.
2. Exactly one badge style: flat-square, labelColor=070e15 everywhere.
   Badge grammar:
   https://img.shields.io/badge/<LABEL>-<MESSAGE>-<COLOR>?style=flat-square&logo=<LOGO>&logoColor=ffffff&labelColor=070e15
   (spaces in LABEL/MESSAGE as %20 or -; COLOR hex without #)
   First badge SHOULD be last-commit:
   https://img.shields.io/github/last-commit/<OWNER>/<REPO>?style=flat-square&color=16242d&labelColor=070e15
   Link a badge only if the target is the canonical upstream URL.
3. Max 2 hero images (width="1200"), each a thumbnail linking to
   full size: <a href="<FULL>"><img src="<THUMB>" alt="<DESC>"
   width="1200"></a>. Prefer .webp thumbnails.
4. One `---` between top-level sections. No emoji. No TOC unless the
   rendered README exceeds ~150 lines.
5. <details> blocks: <summary><b>Name</b></summary>, blank line after
   <summary>, blank line before </details> (GitHub needs both to
   render markdown inside). Max ~3 blocks per section, bullets inside
   are one-liners: `path/` — what it is.
6. Keep the header's bold one-liner to 3–5 keywords joined by `·`.

ADAPT PER PROJECT TYPE (keep the skeleton, rename sections):
- CLI / tool: Quick start = install + first command. Sections = Usage,
  Configuration, Examples (in <details>).
- Library: Quick start = install + minimal snippet. Sections = API /
  Concepts (in <details>), Configuration.
- Config / dotfiles: Quick start = what maps where + selective copy
  + special cases. Sections = grouped areas (in <details>).
- App / service: Quick start = run + open. Sections = Features,
  Configuration, Deployment (in <details>).
- Gallery section: only if the project has 3+ visuals; otherwise drop it.
================================================================= -->

<div align="center">

# {{project-name}}

**{{keyword-1}} · {{keyword-2}} · {{keyword-3}}**

![](https://img.shields.io/github/last-commit/{{owner}}/{{repo}}?style=flat-square&color=16242d&labelColor=070e15)
![](https://img.shields.io/badge/{{label}}-{{message}}-{{color}}?style=flat-square&logo={{logo}}&logoColor=ffffff&labelColor=070e15)
![](https://img.shields.io/badge/{{label}}-{{message}}-{{color}}?style=flat-square&logo={{logo}}&logoColor=ffffff&labelColor=070e15)

<!-- Keep 0–2 hero images. Delete this block if the project has no visuals. -->
<a href="{{assets/full-1.png}}"><img src="{{assets/thumb-1.webp}}" alt="{{what the screenshot shows}}" width="1200"></a>

</div>

---

## {{Project}} stack

<!-- 2-column overview: aspect → choice. 5–10 rows. Link upstream projects. -->
| Layer | Software |
|---|---|
| {{Aspect}} | {{Choice}} |
| {{Aspect}} | [{{Choice}}]({{upstream-url}}) |

---

## Quick start

<!-- 1 premise sentence (what maps where / what install gives you), then the
minimal copy-pasteable block so the reader runs something in 30 seconds. -->
{{One sentence premise.}}

```bash
{{clone / install / run — minimal path only}}
```

<!-- Only genuine exceptions to the block above. Delete if none. -->
Special cases:

- `{{path}}`: {{what to do differently, or link to deeper docs}}

---

## {{Area-1}}

<!-- Group content into ≤3 collapsible blocks. Bullets: `path/` — one line. -->

<details>
<summary><b>{{Group name}}</b></summary>

- `{{path}}/` — {{what it is / does}}

</details>

<details>
<summary><b>{{Group name}}</b></summary>

- `{{path}}/` — {{what it is / does}}

</details>

---

## {{Area-2}}

<details>
<summary><b>{{Group name}}</b></summary>

- `{{path}}/` — {{what it is / does}}

</details>

---

<!-- Optional: keep only with 3+ visuals, else delete the whole section. -->
## Gallery

<details>
<summary><b>Gallery</b> ({{N}} images, click for full size)</summary>

<div align="center">

<a href="{{assets/full-1.png}}"><img src="{{assets/thumb-1.webp}}" width="220" alt="{{name}}"></a>
<a href="{{assets/full-2.png}}"><img src="{{assets/thumb-2.webp}}" width="220" alt="{{name}}"></a>

</div>

</details>
