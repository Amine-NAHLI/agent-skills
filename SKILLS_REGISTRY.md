# Skills Registry

Central registry for all skills collected in **agent-skills**.  
Update this file whenever a skill is imported, reviewed, tested, or archived.

---

## Status legend

| Status | Meaning |
|--------|---------|
| **New** | Imported into the collection; not yet reviewed |
| **Reviewed** | Metadata and content checked against source |
| **Tested** | Validated with at least one compatible coding agent |
| **Archived** | Moved to `archive/` — outdated, superseded, or rejected |

---

## Registry

| Skill | Category | Source repository | Original URL | Import date | Popularity | Status | Notes |
|-------|----------|-------------------|--------------|-------------|------------|--------|-------|
| skill-creator | Core | [anthropics/skills](https://github.com/anthropics/skills) | [skills/skill-creator](https://github.com/anthropics/skills/tree/main/skills/skill-creator) | 2026-07-19 | ~318K installs ([skills.sh](https://skills.sh/anthropics/skills/skill-creator)); repo ~162K ⭐ | New | Anthropic official meta-skill. Scripts, eval viewer, agent definitions. Commit `fa0fa64`. Curated: `curated/core/skill-creator/`. Apache-2.0. |
| mcp-builder | AI / MCP | [anthropics/skills](https://github.com/anthropics/skills) | [skills/mcp-builder](https://github.com/anthropics/skills/tree/main/skills/mcp-builder) | 2026-07-19 | ~89K installs ([skills.sh](https://skills.sh/anthropics/skills/mcp-builder)); repo ~162K ⭐ | New | MCP server development guide — 4-phase workflow, TS/Python. Commit `fa0fa64`. Curated: `curated/ai/mcp-builder/`. Apache-2.0. |
| claude-api | AI / LLM | [anthropics/skills](https://github.com/anthropics/skills) | [skills/claude-api](https://github.com/anthropics/skills/tree/main/skills/claude-api) | 2026-07-19 | repo ~162K ⭐ | New | Claude API & Anthropic SDK reference, multi-language. Commit `fa0fa64`. Curated: `curated/ai/claude-api/`. Apache-2.0. |
| vercel-react-best-practices | Development / React | [vercel-labs/agent-skills](https://github.com/vercel-labs/agent-skills) | [skills/react-best-practices](https://github.com/vercel-labs/agent-skills/tree/main/skills/react-best-practices) | 2026-07-19 | ~185K installs ([skills.sh](https://skills.sh/vercel-labs/agent-skills/react-best-practices)); repo ~29K ⭐ | New | 70 performance rules, 8 categories. Commit `f8a72b9`. Curated: `curated/development/react/vercel-react-best-practices/`. MIT. |
| frontend-design | Development / Frontend | [anthropics/skills](https://github.com/anthropics/skills) | [skills/frontend-design](https://github.com/anthropics/skills/tree/main/skills/frontend-design) | 2026-07-19 | popular on [skills.sh](https://skills.sh/anthropics/skills/frontend-design); repo ~162K ⭐ | New | Distinctive UI design guidance, anti-template aesthetics. Commit `fa0fa64`. Curated: `curated/development/frontend/frontend-design/`. Apache-2.0. |
| webapp-testing | Testing | [anthropics/skills](https://github.com/anthropics/skills) | [skills/webapp-testing](https://github.com/anthropics/skills/tree/main/skills/webapp-testing) | 2026-07-19 | [skills.sh](https://skills.sh/anthropics/skills/webapp-testing); repo ~162K ⭐ | New | Playwright web app testing with server lifecycle helper. Commit `fa0fa64`. Curated: `curated/testing/webapp-testing/`. Apache-2.0. |
| doc-coauthoring | Documentation | [anthropics/skills](https://github.com/anthropics/skills) | [skills/doc-coauthoring](https://github.com/anthropics/skills/tree/main/skills/doc-coauthoring) | 2026-07-19 | repo ~162K ⭐ | New | 3-stage doc co-authoring workflow for specs and proposals. Commit `fa0fa64`. Curated: `curated/documentation/doc-coauthoring/`. Apache-2.0. |
| docx | Documentation | [anthropics/skills](https://github.com/anthropics/skills) | [skills/docx](https://github.com/anthropics/skills/tree/main/skills/docx) | 2026-07-19 | repo ~162K ⭐ | New | Word document creation/editing — production reference. Commit `fa0fa64`. Curated: `curated/documentation/docx/`. Proprietary/source-available. |
| pdf | Documentation | [anthropics/skills](https://github.com/anthropics/skills) | [skills/pdf](https://github.com/anthropics/skills/tree/main/skills/pdf) | 2026-07-19 | repo ~162K ⭐ | New | PDF processing — extract, merge, forms, OCR. Commit `fa0fa64`. Curated: `curated/documentation/pdf/`. Proprietary/source-available. |
| pptx | Documentation | [anthropics/skills](https://github.com/anthropics/skills) | [skills/pptx](https://github.com/anthropics/skills/tree/main/skills/pptx) | 2026-07-19 | repo ~162K ⭐ | New | PowerPoint creation/editing — production reference. Commit `fa0fa64`. Curated: `curated/documentation/pptx/`. Proprietary/source-available. |
| xlsx | Documentation | [anthropics/skills](https://github.com/anthropics/skills) | [skills/xlsx](https://github.com/anthropics/skills/tree/main/skills/xlsx) | 2026-07-19 | repo ~162K ⭐ | New | Spreadsheet creation/editing — production reference. Commit `fa0fa64`. Curated: `curated/documentation/xlsx/`. Proprietary/source-available. |
| find-skills | Productivity | [vercel-labs/skills](https://github.com/vercel-labs/skills) | [skills/find-skills](https://github.com/vercel-labs/skills/tree/main/skills/find-skills) | 2026-07-19 | repo ~27K ⭐; [skills.sh](https://skills.sh/) leaderboard | New | Skill discovery via Skills CLI. Commit `777599e`. Curated: `curated/productivity/find-skills/`. MIT. |

---

## Adding a new skill

Copy this row template when importing:

```markdown
| skill-name | Category / Subcategory | [owner/repo](https://github.com/owner/repo) | [path/to/skill](https://github.com/owner/repo/tree/main/path/to/skill) | YYYY-MM-DD | installs or stars if known | New | Brief note — purpose, license, local paths. |
```

### Field guide

| Field | What to record |
|-------|----------------|
| **Skill** | `name` from `SKILL.md` frontmatter |
| **Category** | Top-level area from `curated/` (e.g. Development / React) |
| **Source repository** | GitHub repo link hosting the original skill |
| **Original URL** | Direct link to the skill directory in the source repo |
| **Import date** | Date added to this collection (ISO 8601: `YYYY-MM-DD`) |
| **Popularity** | Install count from [skills.sh](https://skills.sh/), npm/downloads, or repo stars — cite the source |
| **Status** | One of: New, Reviewed, Tested, Archived |
| **Notes** | Commit hash, local paths, license, rule count, or review findings |

---

*Last updated: 2026-07-19*
