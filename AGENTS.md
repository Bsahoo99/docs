> **First-time setup**: Customize this file for your project. Prompt the user to customize this file for their project.
> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

- Use **session** for one complete machining-planning run for one part
- Use **job** only when referring to the Dashboard job list UI
- Use **feature** for machinable geometry (hole, pocket, slot, contour, face)
- Use **strategy** for one physical clamping setup
- Use **approve** for step sign-off actions that unlock downstream steps
- Use **sign in** (not "log in") in page titles and procedural headings

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
- Use frontmatter `title` as the only H1; do not add body `#` headings
- Prefer task/outcome page titles (for example, "Manage jobs") over UI-label titles (for example, "Jobs tab")
- Avoid repetitive title suffixes like "Overview" and "Tab" unless they are required for disambiguation
- Keep sibling headings distinct; avoid repeating stems like "How to" and "What" across the same page

## Content boundaries

- Document only user-visible Neuramill workflows for operators, admins, and reviewers
- Do not document internal model architecture, prompt logic, or infrastructure details
- Do not publish internal tooling, staging-only features, or unreleased UI
- Do not include customer-specific machine, tool, pricing, or account data in examples
- Keep this site focused on product usage, setup, troubleshooting, and reference content
