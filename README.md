# Bogotá 1995: the game

A game version of [Bogotá 1995](https://github.com/juancopi81/bogota-1995),
an interactive room set in a Bogotá bedroom on a rainy afternoon in 1995.

The game is the excuse. The real purpose of this repo is to learn
[The AI-native SDLC playbook](https://claude.com/resources/articles/the-ai-native-sdlc-playbook)
by applying it one play at a time with Claude, following the reading as written
before adapting anything.

There's nothing to play yet. Nothing is hosted: the game is built and tried
locally until it's worth showing.

## Plays

Each play is ticked off once it has been applied here. "Needs first" lists
the prerequisites the playbook gives for that play; a dash means the play
doesn't name any.

| Stage | Play | Needs first | Applied |
| --- | --- | --- | --- |
| 1. Plan | Capture as `intent.md` | None | ✓ [first intent](intent/001-first-two-missions/intent.md) |
| 2. Design | Requirements and design (`spec.md`) | `intent.md`; policies written as skills | |
| 3. Build | Plan mode as the starting point (`plan.md`) | `intent.md` or `spec.md` if one exists; `CLAUDE.md` helps | |
| 3. Build | Auto mode | – | |
| 3. Build | The `CLAUDE.md` | None | |
| 3. Build | Skills as institutional knowledge | None | |
| 3. Build | Hooks as build-time guardrails | – | |
| 3. Build | Parallel sessions and subagents | `CLAUDE.md`; a feedback loop helps | |
| 4. Test | Give Claude a feedback loop | None | |
| 4. Test | Continuous evals in CI | `CLAUDE.md`; feedback loop | |
| 5. Deploy | AI in the PR review loop | `CLAUDE.md`; skills; subagents | |
| 5. Deploy | Hooks as approval gates | None | |
| 5. Deploy | CI/CD integration and deployment | PR review loop; hooks as approval gates | |
| 6. Maintain | Maintenance and closing the loop | `intent.md`; PR review; hooks; a rollback path | |
| 6. Maintain | Recurring codebase scans | PR review gate; hooks as approval gates; `intent.md` | |
| 6. Maintain | Claude on call with Claude Tag | – | |

## How changes arrive

Every change reaches `main` through a pull request, merged as a single squashed
commit. Merging is the approval: an accepted `intent.md`, spec or plan is one
that has been merged.
