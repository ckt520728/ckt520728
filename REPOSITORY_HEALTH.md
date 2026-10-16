# Repository health report

**Audit date:** 2026-10-16
**Scope:** 48 public repositories owned by `ckt520728` (11 original, 37 forks). Private repositories, secret scanning results, runtime deployments, and upstream code quality were not inspected.

## Executive assessment

The portfolio has a clear technical identity and active original work. Discoverability is reasonably strong, but governance and automation are inconsistent. The highest-value improvement is to standardize a small set of repository controls across the original projects while keeping forks visibly separate from authored work.

## Current baseline

| Signal | Result | Assessment |
| --- | ---: | --- |
| Original repositories with a description | 10 / 11 | Strong |
| Original repositories with topics | 8 / 11 | Good |
| Original repositories with a root README | 8 / 11 | Needs completion |
| Original repositories with a recognized root license | 1 / 11 | High-priority gap |
| Original repositories with GitHub Actions on the default branch | 0 / 11 | High-priority gap |
| Original repositories with protected default branches | 0 / 11 | High-priority gap |
| Original repositories with a root security policy | 0 / 11 | High-priority gap for public clinical/AI work |
| Original repositories with a root contributing guide | 0 / 11 | Optional for personal work; useful for shared projects |
| Original repositories with issue tracking enabled | 11 / 11 | Strong |
| Public repositories archived | 2 / 48 | Clear lifecycle signal where used |

## What is working well

- The portfolio has a coherent focus: clinical science, cognitive neuroscience, agentic research, and reusable workflows.
- Original repositories are now separated from upstream reference forks in the profile architecture.
- Most original projects have useful descriptions and topic metadata.
- `kidney-cognition-lab` already has a recognized license and `CITATION.cff`, a strong pattern for research-facing projects.
- Private clinical repositories are not exposed through this public index.

## Priority actions

### P0 — portfolio navigation

- Keep this profile repository as the authoritative portfolio map.
- Use [SKILL_INDEX.md](SKILL_INDEX.md) as the classification layer; do not physically regroup skills merely to make them discoverable.
- Pin the six most representative original repositories on the GitHub profile rather than forks.

### P1 — trust and change safety

1. Add a root README to `2026-Antigravity`, `Claude-Code`, and `kwotachu-dashboard`.
2. Choose and document reuse terms for every original public repository. Add an OSI license for open-source code, or an explicit all-rights-reserved/content notice where open reuse is not intended.
3. Add minimal CI to actively maintained code repositories: install, lint or validate, test, and build where applicable.
4. Protect default branches for `claude-skills`, `2026Cordex`, `2026-Antigravity`, and `kidney-cognition-lab`; require the CI checks introduced above.
5. Add `SECURITY.md`, especially where software touches clinical workflows, uploads, credentials, Firebase, or generated medical content.

### P2 — consistent repository experience

- Add issue and pull-request templates to actively maintained collaborative repositories.
- Add dependency update automation where a package manifest exists.
- Add `CITATION.cff` to research outputs that may be referenced academically.
- Add topics to `claude-skills`, `ckt520728`, and `classroom-firebase-tools`; add a profile-repository description.
- Prefer `main` for new repositories. Renaming existing default branches is optional and should be done only after checking automation and links.

### P3 — lifecycle and fork hygiene

- Review unmodified or no-longer-used forks periodically; archive or delete only after confirming they are not used as pinned references or dependency sources.
- Record upstream URL and sync status when a fork is materially modified.
- Mark experiments as experimental and completed projects as maintained or archived.
- Avoid presenting fork activity as original portfolio output; the profile now labels it as upstream reference material.

## Recommended minimum standards by repository type

| Type | Minimum standard |
| --- | --- |
| Reusable skill registry | README, provenance, license/reuse terms, validation script, CI, changelog or releases |
| Research workspace | README, environment lockfile, data policy, reproducible entry point, citation, lightweight CI |
| Public application | README, license, security policy, dependency updates, test/build CI, deployment documentation |
| Knowledge or notes repository | README, scope and lifecycle, reuse terms; CI only for generated or built outputs |
| Upstream fork | Original upstream attribution, reason for fork, sync status; archive when no longer useful |

## Suggested rollout

Start with the four portfolio anchors: `claude-skills`, `2026Cordex`, `2026-Antigravity`, and `kidney-cognition-lab`. Establish one reusable community-health template and one small CI pattern, then apply them to the remaining original repositories according to project type.

This report is a point-in-time public audit, not a certification. Re-run it after major repository additions or quarterly.

[Return to profile](README.md) · [Browse the skill index](SKILL_INDEX.md)
