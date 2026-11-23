# Web Design Skills for Codex

10 skills that make Codex design better websites (less "AI template" look).

## Install (2 minutes)

1. Unzip, then copy every folder inside `skills/` into your Codex skills folder:

   ```bash
   mkdir -p ~/.agents/skills
   cp -R skills/* ~/.agents/skills/
   ```

   (Older Codex versions read `~/.codex/skills/` instead. If they don't show up, copy them there too.)

2. Restart Codex. Type `/skills` to check they're listed, or call one with `$skill-name`
   (e.g. `$design-taste-frontend`). Most also trigger on their own when you ask for a web page.

## What's inside

| Skill | Use it for |
|---|---|
| `design-taste-frontend` | Main one. Landing pages, portfolios, redesigns that don't look templated. |
| `high-end-visual-design` | Fonts, spacing, shadows, cards and animation that feel "expensive". |
| `redesign-existing-projects` | Upgrade an existing site without breaking it. |
| `image-to-code` | Generate a design image first, then build the site to match it. |
| `imagegen-frontend-web` | Generate premium design reference images, one per page section. |
| `design-md-references` | Design systems of 74 well-known sites (Linear, Stripe, Apple, Vercel...) to borrow from. |
| `minimalist-ui` | Clean editorial look: warm monochrome, flat bento grids. |
| `industrial-brutalist-ui` | Raw Swiss/terminal look for dashboards and editorial sites. |
| `gpt-taste` | Bold GSAP scroll-motion landing pages. |
| `web-design-guidelines` | Review a page against Vercel's Web Interface Guidelines (accessibility, UX). |

## Two more worth installing (official Codex versions)

- **Impeccable** — full design director skill (critique, polish, audit, design systems):
  ```bash
  npx impeccable install
  ```
- **Icons8** — real icons and illustrations, plus design-tokens / ui-polish / ux-check / ux-writing skills:
  ```bash
  codex plugin marketplace add icons8/agent-skills
  ```
  then install **icons8** from `/plugins`. Icons need a free Icons8 sign-in (`codex mcp login icons8mcp`).

Each skill keeps its own LICENSE file where it came with one.
