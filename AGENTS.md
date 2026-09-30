# Portfolio project instructions

## About this project

- This is the technical writing portfolio of Strahinja Milošević, published at strahinjamilosevic.com
- The site is built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Use the Mintlify docs MCP server, `https://www.mintlify.com/docs/mcp`, to query information about using Mintlify via MCP
- The audience is recruiters, hiring managers, HR tools, and LLMs. Every page needs a specific `title` and `description`

## Source of truth

- All facts come from the private `career` repo: `profile/facts.yaml` and `profile/achievements/`. Follow the rules in its `CLAUDE.md`
- Never invent or embellish metrics, titles, tools, dates, or scope
- Do not use entries marked `verify:` in `facts.yaml`
- Keep wording and numbers identical to the resume and LinkedIn

## Terminology

- Write "in-person payments", not "IPP"
- Write "docs-as-code", "information architecture", and "API governance" in lowercase
- Dates use full month names and an en dash: "November 2024 – Present"

## Style preferences

- Write in first person ("I") and active voice
- Short declarative sentences, one idea per sentence
- Use sentence case for headings
- Bullets: outcome, action, scope. Include the number when one exists
- No bold labels at the start of bullets, no filler, no emojis
- Code formatting for file names, commands, paths, and code references

## Content boundaries

- Never publish a phone number, email address, salary data, or internal company data
- Case studies in `projects/` follow the why, what, how, result structure
