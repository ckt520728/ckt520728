# Skill classification index

This is a discovery layer for skills distributed across the public repositories of [ckt520728](https://github.com/ckt520728). It classifies related capabilities without moving, merging, or deleting their source files.

**Snapshot:** 2026-10-16 · **1,174 manifest instances** · **20 public repositories** · **59 exact skill names appear in more than one repository**

> Counts are inventory signals, not counts of unique skills. They include upstream forks, workspace mirrors, generated examples, and test fixtures. Repository provenance should be checked before reuse.

## How to read the index

- **Canonical custom registry**: the preferred public source for mature custom skills.
- **Workspace or product-local**: skills coupled to experiments, applications, or project context.
- **Upstream reference fork**: third-party work retained for evaluation or learning; upstream licensing and authorship apply.
- **Generated or fixture content**: useful examples that should not be treated as independently maintained packages.

## Functional classification

| Classification | What it covers | Primary custom sources | Related upstream references |
| --- | --- | --- | --- |
| Biomedical databases and bioinformatics | Literature, variants, proteins, compounds, pathways, omics, structures | [2026-Antigravity](https://github.com/ckt520728/2026-Antigravity/tree/main/.agents/plugins/science/skills) workspace mirror | [science-skills](https://github.com/ckt520728/science-skills/tree/main/skills), [OpenClaw-Medical-Skills](https://github.com/ckt520728/OpenClaw-Medical-Skills/tree/main/skills) |
| Clinical reasoning and health workflows | Admission notes, mortality analysis, neuropsychology, clinical time series, medical websites | [claude-skills](https://github.com/ckt520728/claude-skills), [perio-board-exam-resources](https://github.com/ckt520728/perio-board-exam-resources/tree/main/skills) | [OpenClaw-Medical-Skills](https://github.com/ckt520728/OpenClaw-Medical-Skills/tree/main/skills) |
| Neuroscience and simulation | FORCE/RNN, drift-diffusion, ODE learning, closed-loop prototyping | [claude-skills](https://github.com/ckt520728/claude-skills), [2026Cordex](https://github.com/ckt520728/2026Cordex/tree/master/skills), [2026-Antigravity](https://github.com/ckt520728/2026-Antigravity/tree/main/.agents/skills) | [OpenClaw-Medical-Skills](https://github.com/ckt520728/OpenClaw-Medical-Skills/tree/main/skills) |
| Research synthesis and publication | Corpus ingestion, literature review, evidence synthesis, academic writing, peer review, blog publishing | [2026Cordex research-to-publication](https://github.com/ckt520728/2026Cordex/tree/master/plugins/research-to-publication/skills), [claude-skills](https://github.com/ckt520728/claude-skills) | [OpenClaw-Medical-Skills](https://github.com/ckt520728/OpenClaw-Medical-Skills/tree/main/skills) |
| Data analysis and visualization | Structured-data analysis, dashboards, statistics, plots, scientific diagrams | [claude-skills](https://github.com/ckt520728/claude-skills), [2026-Antigravity](https://github.com/ckt520728/2026-Antigravity) | [diagram-design](https://github.com/ckt520728/diagram-design/tree/main/skills), [OpenClaw-Medical-Skills](https://github.com/ckt520728/OpenClaw-Medical-Skills/tree/main/skills) |
| Presentations, teaching, and interactive content | Slides, SOIL teaching decks, lecture notes, classroom tools, diagrams | [claude-skills](https://github.com/ckt520728/claude-skills), [2026-Antigravity](https://github.com/ckt520728/2026-Antigravity/tree/main/.agents/skills) | [open-slide](https://github.com/ckt520728/open-slide/tree/main/packages/core/skills), [diagram-design](https://github.com/ckt520728/diagram-design/tree/main/skills), [wordwall-cli](https://github.com/ckt520728/wordwall-cli) |
| Agent engineering and verification | TDD, debugging, review, planning, orchestration, CI triage, loop verification | [2026Cordex](https://github.com/ckt520728/2026Cordex/tree/master/skills), [claude-skills](https://github.com/ckt520728/claude-skills) | [superpowers](https://github.com/ckt520728/superpowers/tree/main/skills), [loop-engineering](https://github.com/ckt520728/loop-engineering/tree/main/skills), [mattpocock-skills](https://github.com/ckt520728/mattpocock-skills/tree/main/skills), [old-coder](https://github.com/ckt520728/old-coder/tree/main/skills) |
| Knowledge and productivity systems | Knowledge bases, meetings, email, daily review, startup/shutdown, Obsidian workflows | [claude-skills](https://github.com/ckt520728/claude-skills), [2026-Hermes](https://github.com/ckt520728/2026-Hermes/tree/main/skills), [codex-management-book](https://github.com/ckt520728/codex-management-book/tree/main/skills) | [cross-device-agent-skills](https://github.com/ckt520728/cross-device-agent-skills), [claude-code-tips](https://github.com/ckt520728/claude-code-tips/tree/main/skills) |
| Skill authoring, installation, and packaging | Creating, installing, converting, and distributing reusable skills | [claude-skills](https://github.com/ckt520728/claude-skills) | [book-to-skill](https://github.com/ckt520728/book-to-skill), [science-skills](https://github.com/ckt520728/science-skills/tree/main/skills/workflow_skill_creator) |
| Web, app, and deployment workflows | Websites, iOS apps, Firebase/GAS, blog deployment, frontend design | [claude-skills](https://github.com/ckt520728/claude-skills), [2026-Antigravity](https://github.com/ckt520728/2026-Antigravity/tree/main/.agents/skills), [2026Cordex](https://github.com/ckt520728/2026Cordex/tree/master/skills) | [open-slide](https://github.com/ckt520728/open-slide), [mattpocock-skills](https://github.com/ckt520728/mattpocock-skills) |
| Media generation and voice | Image generation, visual assets, voice cloning and synthesis | [claude-skills](https://github.com/ckt520728/claude-skills) | [opencode-draw-free](https://github.com/ckt520728/opencode-draw-free), [OpenClaw-Medical-Skills](https://github.com/ckt520728/OpenClaw-Medical-Skills/tree/main/skills) |
| Codebase knowledge and graph extraction | Repository mapping, code knowledge graphs, legacy migration | [2026Cordex](https://github.com/ckt520728/2026Cordex/tree/master/skills/implement-graphify) | [graphify](https://github.com/ckt520728/graphify), [mattpocock-skills](https://github.com/ckt520728/mattpocock-skills) |

## Repository inventory

| Repository | Provenance | Manifest instances | Main role |
| --- | --- | ---: | --- |
| [claude-skills](https://github.com/ckt520728/claude-skills) | Original; canonical custom registry | 50 | Clinical, research, analysis, teaching, publishing, and productivity |
| [2026-Antigravity](https://github.com/ckt520728/2026-Antigravity) | Original; workspace | 47 | Science-plugin mirror plus project-local research and deployment skills |
| [2026Cordex](https://github.com/ckt520728/2026Cordex) | Original; workspace | 25 | Research-to-publication, decision workflows, codebase and site tooling |
| [codex-management-book](https://github.com/ckt520728/codex-management-book) | Original; project-local | 2 | Management-skill creation and System 1/System 2 review |
| [perio-board-exam-resources](https://github.com/ckt520728/perio-board-exam-resources) | Original; project-local | 1 | Periodontal examination analysis |
| [2026-Hermes](https://github.com/ckt520728/2026-Hermes) | Original; project-local | 1 | Productivity and blog-generation workflow |
| [OpenClaw-Medical-Skills](https://github.com/ckt520728/OpenClaw-Medical-Skills) | Upstream reference fork | 897 | Broad medical, bioinformatics, scientific, and general agent library |
| [science-skills](https://github.com/ckt520728/science-skills) | Upstream reference fork | 40 | Curated scientific databases and analysis tools |
| [mattpocock-skills](https://github.com/ckt520728/mattpocock-skills) | Upstream reference fork | 38 | Software engineering, architecture, planning, and productivity |
| [loop-engineering](https://github.com/ckt520728/loop-engineering) | Upstream reference fork | 31 | Iterative agent loops, triage, verification, and starter templates |
| [superpowers](https://github.com/ckt520728/superpowers) | Upstream reference fork | 14 | End-to-end software-development practices for agents |
| [open-slide](https://github.com/ckt520728/open-slide) | Upstream reference fork | 13 | Slide authoring, theming, design, and frontend patterns |
| [claude-code-tips](https://github.com/ckt520728/claude-code-tips) | Upstream reference fork | 6 | GitHub Actions, handoff, review, and repository-cloning utilities |
| [cross-device-agent-skills](https://github.com/ckt520728/cross-device-agent-skills) | Upstream reference fork | 3 | Project startup, shutdown, and initialization |
| [diagram-design](https://github.com/ckt520728/diagram-design) | Upstream reference fork | 1 | Editorial diagram design |
| [opencode-draw-free](https://github.com/ckt520728/opencode-draw-free) | Upstream reference fork | 1 | Image generation |
| [graphify](https://github.com/ckt520728/graphify) | Upstream reference fork | 1 | Codebase knowledge-graph generation |
| [old-coder](https://github.com/ckt520728/old-coder) | Upstream reference fork | 1 | Evidence-first software delivery |
| [wordwall-cli](https://github.com/ckt520728/wordwall-cli) | Upstream reference fork | 1 | Wordwall teaching-content automation |
| [book-to-skill](https://github.com/ckt520728/book-to-skill) | Upstream reference fork | 1 | Converting technical books into agent skills |

## Known overlap map

Exact-name matching found 59 names present in multiple repositories. The main patterns are:

- **40 scientific skills** are mirrored from `science-skills` inside `2026-Antigravity`.
- **14 software-engineering skills** appear in both `superpowers` and `OpenClaw-Medical-Skills`.
- `article-writer` and `publish-lab-blog` appear in both `claude-skills` and `2026Cordex`.
- `jev-engineering` appears in both `claude-skills` and `2026-Antigravity`.
- `handoff` appears in both `mattpocock-skills` and `claude-code-tips`.

These overlaps are not automatically defects. They may be intentional vendoring, snapshots, or independently modified copies. When promoting a custom skill, record its canonical repository, upstream source, version or commit, and whether the local copy is vendored or independently maintained.

## Maintenance convention

For new or promoted skills, add four small metadata fields to the nearest README or catalog:

1. **Canonical source** — the repository and path that owns the skill.
2. **Provenance** — original, adapted, vendored, generated, or fixture.
3. **Lifecycle** — experimental, maintained, deprecated, or archived.
4. **Last verified** — date or commit against which the skill was tested.

[Return to profile](README.md) · [Review repository health](REPOSITORY_HEALTH.md)
