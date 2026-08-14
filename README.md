# Claude Skills for PMs

A curated set of [Claude Skills](https://www.anthropic.com/news/skills) built for product managers.

Each skill packages a repeatable PM workflow (persona-building, requirement structuring, roadmap planning, etc.) into a reusable Claude Skill you can drop into your own Claude setup and invoke on demand.

## What's a Claude Skill?

A Skill is a folder of instructions (and sometimes helper scripts) that teaches Claude how to do a specific, repeatable task consistently — instead of re-explaining your process in every conversation. Once installed, you just ask Claude for the task ("write a PRD for this feature") and it follows the skill's structure automatically.

## Skills included

| Skill | Use it when you need to... |
|---|---|
| **company-research** | Build a Company Intelligence Brief on a prospective client — tech landscape, business health, stakeholders, and opportunity mapping. |
| **requirement-gathering** | Structure requirements pulled from client stakeholders, internal engineering/design, and leadership before scoping work. |
| **proto-persona** | Create a working customer/user persona from research and team knowledge, before deeper validation. |
| **epic-hypothesis** | Frame a major initiative as a testable hypothesis (target user, expected outcome, validation method) before roadmapping. |
| **roadmap-planning** | Build or restructure a product roadmap — Now/Next/Later, quarterly, or dependency-based — from a backlog or set of initiatives. |
| **prd-development** | Turn discovery notes and requirements into an engineering-ready PRD (Problem Alignment / Solution Alignment format). |
| **user-story** | Write user stories in Mike Cohn format with Gherkin acceptance criteria, ready for development. |
| **swot-analysis** | Produce a structured SWOT (Strengths, Weaknesses, Opportunities, Threats) with strategic recommendations for a company, product, or decision. |

## How to use these

1. Download the `.zip` for the skill you want from the [`skills/`](./skills) folder
2. Unzip it
3. Add the unzipped folder to your Claude Skills directory (in Claude.ai: **Settings → Capabilities → Skills**, or drop it into `/mnt/skills/user/` if you're working in a Claude environment that supports local skills)
4. Ask Claude for the relevant task in plain language — the skill activates automatically when it matches what you're asking for


---
*Built and shared by the York IE team for PM Connect 3.0.*
