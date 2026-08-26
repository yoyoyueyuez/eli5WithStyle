# eli5WithStyle

Explain like I'm five — with style. An ELI5 explainer for web-dev topics, presented as a single self-contained HTML page with hand-drawn SVG diagrams, built to a design-system style guide.

## Examples

- **`examples/poke-the-page.html`** — *Poke the Page*: React events, explained with big pictures and few words. Covers event names, `onClick` handlers, the classic `onClick={fn}` vs `onClick={fn()}` bug, the synthetic event, event delegation, and the redraw loop. No dependencies — open it directly in a browser.

## Skill

- **`.claude/skills/eli5-with-style/`** — a Claude Code skill (`/eli5-with-style`) that produces these explainers.

### Bring your own design

Every explainer is styled from a design guide. The skill reads **`DESIGN.md`** from the skill folder — and falls back to the bundled **`DESIGN_DEFAULT.md`** (Ant Design) when yours isn't there.

To make the skill build in your own style:

1. Add `.claude/skills/eli5-with-style/DESIGN.md` — start from a copy of `DESIGN_DEFAULT.md`.
2. Edit the YAML front-matter (colors, typography, spacing, components) and the prose rules to match your design system.
3. The next time you run `/eli5-with-style <topic>`, the page follows your `DESIGN.md`.

`examples/poke-the-page.html` was generated from the default Ant Design guide.
