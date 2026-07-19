# skill-creator

## Original source

- **Repository:** [anthropics/skills](https://github.com/anthropics/skills)
- **Skill path:** `skills/skill-creator`
- **Commit:** `fa0fa64bdc967915dc8399e803be67759e1e62b8`
- **Local source copy:** [`sources/anthropic/skills/skill-creator`](../../../sources/anthropic/skills/skill-creator)

## Purpose

Anthropic's official meta-skill for the full skill development lifecycle: creating new skills from scratch, editing and improving existing ones, running evaluations, benchmarking performance with variance analysis, and optimizing skill descriptions for better triggering accuracy.

Includes bundled scripts (`package_skill`, `quick_validate`, `run_eval`, `run_loop`, `generate_report`, `improve_description`), reference docs, eval viewer tooling, and grader/comparator/analyzer agent definitions.

## Why this skill is valuable

- **Canonical authoring guide** — defines the official Anthropic workflow for skill creation, from intent capture through iterative eval loops
- **Built-in quality tooling** — validation, packaging, benchmarking, and description tuning scripts ship with the skill itself
- **Foundation for any collection** — essential meta-skill for building and maintaining a curated skills library like this repository
- **Cross-agent relevance** — while authored by Anthropic, the patterns align with the open [Agent Skills specification](https://agentskills.io/specification) used by Cursor, Codex, and others
- **High ecosystem adoption** — one of the most installed skills on [skills.sh](https://skills.sh/anthropics/skills/skill-creator) (~318K installs); source repo ~162K ⭐
