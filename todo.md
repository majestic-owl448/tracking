# Todo List

## Curriculum

### In Progress

- **Camperbot Profile App**: issue https://github.com/freeCodeCamp/CurriculumExpansion/issues/1138 / PR https://github.com/freeCodeCamp/back-end-development-and-apis/pull/2 — changes requested by ShaunSHamilton (use fetch integration tests, no regex)

### To Review

- **[#66510](https://github.com/freeCodeCamp/freeCodeCamp/pull/66510)** — add traffic light sequencer lab
- **[#66298](https://github.com/freeCodeCamp/freeCodeCamp/pull/66298)** — re-review Smart Pantry Restocker lab; author (aBeholic) pushed commit and commented on 2026-03-16 after our CHANGES_REQUESTED
- **[#65887](https://github.com/freeCodeCamp/freeCodeCamp/issues/65887)** — improve solution download format to ZIP project structure; open issue by Jeevankumar-s, needs triage
- **[#66117](https://github.com/freeCodeCamp/freeCodeCamp/pull/66117)** — add linked list workshop JS v9
- **[#65819](https://github.com/freeCodeCamp/freeCodeCamp/pull/65819)** — add JS graphs and tree quiz
- **[#64427](https://github.com/freeCodeCamp/freeCodeCamp/pull/64427)** — add envelope budget app
- **[#64012](https://github.com/freeCodeCamp/freeCodeCamp/pull/64012)** — add workshop-word-counter to JS v9 cert
- **[#66379](https://github.com/freeCodeCamp/freeCodeCamp/pull/66379)** — Build a Zoo Animal Scatterplot
- **[#65848](https://github.com/freeCodeCamp/freeCodeCamp/pull/65848)** — add JS BFS workshop
- **[#66022](https://github.com/freeCodeCamp/freeCodeCamp/pull/66022)** — add workshop heritage library catalog
- **[#66406](https://github.com/freeCodeCamp/freeCodeCamp/pull/66406)** — add interactive JS courses to catalog
- **[CurriculumExpansion#1135](https://github.com/freeCodeCamp/CurriculumExpansion/pull/1135)** — adding express error handling piggy bank lab
- **[CurriculumExpansion#1131](https://github.com/freeCodeCamp/CurriculumExpansion/pull/1131)** — adding express error handling tiny bank API workshop
- **[#65515](https://github.com/freeCodeCamp/freeCodeCamp/pull/65515)** — add Playlist Remix Engine lab
- **[curriculum-helpers#561](https://github.com/freeCodeCamp/curriculum-helpers/pull/561)** — implement universal selector handling in getStyle (linked to issue https://github.com/freeCodeCamp/freeCodeCamp/issues/64218)
- **[#62399](https://github.com/freeCodeCamp/freeCodeCamp/pull/62399)** — add setup instructions to first backend challenge (linked to issue https://github.com/freeCodeCamp/freeCodeCamp/issues/60576)

---

## Contribute Docs

### To Open

- **Open a PR** to document test execution order in workshop and lab guides: tests for each step run against the seed of the next step, or the solution block for the last step (workshops only)
- **Open a PR** to add a note that `pnpm run develop` must be running for the "View Live Version" link in the Challenge Editor to work (port 8000), since the editor runs on port 3300 — applies to workshop and lab guides
- **Open a PR** to explain position within a module: 1-indexed, based on currently existing blocks, not planned ones — applies to workshop and lab guides
- **Open a PR** to document the `intro.json` update step in the workshop and lab creation workflow (the file structure is documented in the curriculum file structure page, but the step itself is missing from the creation workflow)
- **[contribute#1249](https://github.com/freeCodeCamp/contribute/issues/1249)** — Open a PR to add daily challenges docs (how to add new ones, how to test, how to release); current info is at https://github.com/freeCodeCamp/staff-wiki

### To Check
- **Check on https://github.com/freeCodeCamp/contribute/issues/992** — building freeCodeCamp on codespaces doesn't work; no linked PRs
- **Check on https://github.com/freeCodeCamp/contribute/issues/1189** — failing command for codespaces users, request docs tweak
- **Check on https://github.com/freeCodeCamp/contribute/issues/1142** — document curriculum best practices
- **Check on https://github.com/freeCodeCamp/contribute/issues/1140** — rename "Work on Codebase" to "Basic Git Workflow"
- **Check on https://github.com/freeCodeCamp/contribute/issues/1139** — add "Returning to freeCodeCamp" guide
- **Check on https://github.com/freeCodeCamp/contribute/issues/1179** — rework documentation to be task-oriented with Astro templates

### To Review

- **[contribute#1236](https://github.com/freeCodeCamp/contribute/pull/1236)** — docs: add TS helpers (relates to curriculum-helpers explorer.ts update)
- **[contribute#1227](https://github.com/freeCodeCamp/contribute/pull/1227)** — docs: add language curricula guide
- **[contribute#1170](https://github.com/freeCodeCamp/contribute/pull/1170)** — docs: Codespaces devcontainer

---

## Utils Scripts (`/home/ilenia/freeCodeCamp/utils-scripts`)

Figure out if/how to integrate each script into the regular workflow.

- **`merge-conflict-check.sh`** — scans open PRs for merge conflict label mismatches; currently has hardcoded PR numbers, last run August 2025
- **`inactive-check.sh`** — checks for inactive PRs
- **`discussing-inactive-check.sh`** — checks for inactive PRs in "discussing" status
- **`dfs.py`** — unknown purpose, investigate

---

## To Read

<!-- Articles, docs, issues, or threads worth reading when there's time -->

- https://gist.github.com/raisedadead/cc46e3fe8184013741ab14ff10151ebd
- https://github.com/freeCodeCamp/Claude-Code-Handbook

### Claude Code Docs

- https://code.claude.com/docs/en/overview
- https://code.claude.com/docs/en/quickstart
- https://code.claude.com/docs/en/changelog
- https://code.claude.com/docs/en/how-claude-code-works
- https://code.claude.com/docs/en/features-overview
- https://code.claude.com/docs/en/memory
- https://code.claude.com/docs/en/common-workflows
- https://code.claude.com/docs/en/best-practices
- https://code.claude.com/docs/en/remote-control
- https://code.claude.com/docs/en/claude-code-on-the-web
- https://code.claude.com/docs/en/desktop-quickstart
- https://code.claude.com/docs/en/desktop
- https://code.claude.com/docs/en/chrome
- https://code.claude.com/docs/en/vs-code
- https://code.claude.com/docs/en/jetbrains
- https://code.claude.com/docs/en/code-review
- https://code.claude.com/docs/en/github-actions
- https://code.claude.com/docs/en/gitlab-ci-cd
- https://code.claude.com/docs/en/slack
- https://code.claude.com/docs/en/sub-agents
- https://code.claude.com/docs/en/agent-teams
- https://code.claude.com/docs/en/plugins
- https://code.claude.com/docs/en/discover-plugins
- https://code.claude.com/docs/en/skills
- https://code.claude.com/docs/en/scheduled-tasks
- https://code.claude.com/docs/en/output-styles
- https://code.claude.com/docs/en/hooks-guide
- https://code.claude.com/docs/en/headless
- https://code.claude.com/docs/en/mcp
- https://code.claude.com/docs/en/troubleshooting
- https://code.claude.com/docs/en/settings
- https://code.claude.com/docs/en/permissions
- https://code.claude.com/docs/en/sandboxing
- https://code.claude.com/docs/en/terminal-config
- https://code.claude.com/docs/en/model-config
- https://code.claude.com/docs/en/fast-mode
- https://code.claude.com/docs/en/statusline
- https://code.claude.com/docs/en/keybindings

---

## Translations (lowest priority — only when all other work is done)

### Pending Review

- **Skeleton Loader Example – How to Build a Skeleton Screen with CSS for Better UX**: https://github.com/freeCodeCamp/news-translation-tasks/issues/281
- **Python String Manipulation Handbook – Learn How to Manipulate Python Strings for Beginners**: https://github.com/freeCodeCamp/news-translation-tasks/issues/376
- **Python Requirements.txt – How to Create and Pip Install Requirements.txt in Python**: https://github.com/freeCodeCamp/news-translation-tasks/issues/526
- **Google Dorking: How to Find Hidden Information on the Web**: https://github.com/freeCodeCamp/news-translation-tasks/issues/527
- **Microsoft Excel: 14 Time-Saving Keyboard Shortcuts**: https://github.com/freeCodeCamp/news-translation-tasks/issues/534
- **Come Lavorare con SQLite in Python – Un Manuale per Principianti**: https://github.com/freeCodeCamp/news-translation-tasks/pull/631
