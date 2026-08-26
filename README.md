# eli5WithStyle

Explain like I'm five — with style. An ELI5 explainer for web-dev topics, presented as a single self-contained HTML page with hand-drawn SVG diagrams, built to a design-system style guide.

## Examples

- **`examples/poke-the-page.html`** — *Poke the Page*: React events, explained with big pictures and few words. Covers event names, `onClick` handlers, the classic `onClick={fn}` vs `onClick={fn()}` bug, the synthetic event, event delegation, and the redraw loop. No dependencies — open it directly in a browser.

## Skill

- **`.claude/skills/eli5-with-style/`** — a Claude Code skill (`/eli5-with-style`) that produces these explainers, with a bundled Ant Design style guide (`DESIGN_DEFAULT.md`).
