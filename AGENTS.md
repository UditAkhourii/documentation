# Documentation project instructions

## About this project

- This is the documentation site for [ADHD](https://github.com/UditAkhourii/adhd) — parallel divergent ideation for coding agents — built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Source of truth for technical claims is the [ADHD repo](https://github.com/UditAkhourii/adhd): `README.md`, `skills/adhd/SKILL.md`, `documentation/`, and `CONTRIBUTING.md` — keep these docs in sync with it
- For Mintlify product knowledge (components, configuration, writing standards), install the Mintlify skill: `npx skills add https://mintlify.com/docs`

## Terminology

- "ADHD" is the project name (an architectural method), always uppercase
- Use "frame" / "vantage operator", never "persona" — frames re-pose the problem, they are not role-played identities
- "Diverge" and "Focus" are the two phases; the "critic" is the separate scoring/clustering LLM call
- The npm package is `adhd-agent`; the skill file is `SKILL.md`
- "Trap" = an idea that looks good but isn't, always flagged with a mechanistic reason

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, flags, and code references
- Keep the project's voice: direct, honest about costs and limitations, no hype

## Content boundaries

- Don't invent benchmark numbers — eval figures come from the ADHD repo's `EVALS.md` and cited external reviews only
- State limitations plainly (same-model judging, small problem set, scale gap)
