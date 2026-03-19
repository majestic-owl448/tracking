# Shelved Items

PRs, issues, and docs work set aside while focusing on the Scopa project.

---

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
- **Open a PR** to add Python 4-space indentation style to the style guide

### To Review and Update

Review each page for outdated or missing information and open PRs as needed:

- `_hooks-shared.mdx`
- `authors-analytics-manual.mdx`
- `codebase-best-practices.mdx`
- `courses-vscode-extension.mdx`
- `curriculum-file-structure.mdx`
- `curriculum-help.mdx`
- `faq.mdx`
- `getting-started.mdx`
- `how-to-add-playwright-tests.mdx`
- `how-to-catch-outgoing-emails-locally.mdx`
- `how-to-contribute-to-the-codebase.mdx`
- `how-to-create-catalog-items.mdx`
- `how-to-enable-new-languages.mdx`
- `how-to-fix-merge-conflicts.mdx`
- `how-to-help-with-video-challenges.mdx`
- `how-to-open-a-pull-request.mdx`
- `how-to-proofread-files.mdx`
- `how-to-setup-freecodecamp-locally.mdx`
- `how-to-setup-freecodecamp-mobile-app-locally.mdx`
- `how-to-setup-wsl.mdx`
- `how-to-translate-files.mdx`
- `how-to-use-docker-on-windows-home.mdx`
- `how-to-work-on-coding-challenges.mdx` *(in progress — indentation rules, hyphenation)*
- `how-to-work-on-labs.mdx`
- `how-to-work-on-localized-client-webapp.mdx`
- `how-to-work-on-quizzes.mdx`
- `how-to-work-on-reviews.mdx`
- `how-to-work-on-the-component-library.mdx`
- `how-to-work-on-the-docs-site.mdx`
- `how-to-work-on-tutorials-that-use-coderoad.mdx`
- `how-to-work-on-workshops.mdx`
- `intro.mdx`
- `language-lead-handbook.mdx`
- `moderator-handbook.mdx`
- `moderator-onboarding-guide.mdx`
- `reply-templates.mdx`
- `security.mdx`
- `troubleshooting-development-issues.mdx`
- `user-token-workflow.mdx`
- `writing-style-guide.mdx`

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

## Translations

### Pending Review

- **Skeleton Loader Example – How to Build a Skeleton Screen with CSS for Better UX**: https://github.com/freeCodeCamp/news-translation-tasks/issues/281
- **Python String Manipulation Handbook – Learn How to Manipulate Python Strings for Beginners**: https://github.com/freeCodeCamp/news-translation-tasks/issues/376
- **Python Requirements.txt – How to Create and Pip Install Requirements.txt in Python**: https://github.com/freeCodeCamp/news-translation-tasks/issues/526
- **Google Dorking: How to Find Hidden Information on the Web**: https://github.com/freeCodeCamp/news-translation-tasks/issues/527
- **Microsoft Excel: 14 Time-Saving Keyboard Shortcuts**: https://github.com/freeCodeCamp/news-translation-tasks/issues/534
- **Come Lavorare con SQLite in Python – Un Manuale per Principianti**: https://github.com/freeCodeCamp/news-translation-tasks/pull/631

---

## Utils Scripts (`/home/ilenia/freeCodeCamp/utils-scripts`)

Figure out if/how to integrate each script into the regular workflow.

- **`merge-conflict-check.sh`** — scans open PRs for merge conflict label mismatches; currently has hardcoded PR numbers, last run August 2025
- **`inactive-check.sh`** — checks for inactive PRs
- **`discussing-inactive-check.sh`** — checks for inactive PRs in "discussing" status
- **`dfs.py`** — unknown purpose, investigate

---

## Follow-up (shelved)

### Unassigned Issues — Watching for Activity

- **[contribute#1220](https://github.com/freeCodeCamp/contribute/pull/1220)** (contribute) - Docs PR to detail each `create-new-project` CLI question and intended answer; seems abandoned — if still unupdated once #1259 and #1260 are merged, close it and open a new PR with those details

- **[contribute#1200](https://github.com/freeCodeCamp/contribute/issues/1200)** (contribute) - Workshop Creation Documentation Gaps; left a comment summarizing what's been addressed and what still needs docs PRs; monitoring for responses

- **[#64786](https://github.com/freeCodeCamp/freeCodeCamp/issues/64786)** (freeCodeCamp) - lab job application form user story not visible; previous PR closed without merge, needs a new one; labeled `status: waiting triage`
- **[#62452](https://github.com/freeCodeCamp/freeCodeCamp/issues/62452)** (freeCodeCamp) - create-new-project extra metadata for lectures; contributor Unknownmaster0 working on it, no PR yet, waiting for ojeytonwilliams feedback; PR #62482 also open and related
- **[#65573](https://github.com/freeCodeCamp/freeCodeCamp/issues/65573)** (freeCodeCamp) - feature request: revert to seed / delete WIP code; scoping discussion ongoing with ShaunSHamilton, labeled `status: waiting triage`

Naomi's Sprint issues with no assignee. Monitor for comments requesting assignment, or flag if inactive too long.

- **[#66172](https://github.com/freeCodeCamp/freeCodeCamp/issues/66172)** (freeCodeCamp) - Add Build a Music Industry Revenue Bar Chart workshop to frontend libraries cert
- **[#66049](https://github.com/freeCodeCamp/freeCodeCamp/issues/66049)** (freeCodeCamp) - Python Certification setter example modification
- **[#65979](https://github.com/freeCodeCamp/freeCodeCamp/issues/65979)** (freeCodeCamp) - Workshop – Build a Wildlife Tracker; PR #65980 opened by Jeevankumar-s; left two inline suggestions on 2026-03-17 (semicolon + double blank line in step 6); waiting for author to address
- **[#64869](https://github.com/freeCodeCamp/freeCodeCamp/issues/64869)** (freeCodeCamp) - Break down string methods workshop and add it to main
- **[#64121](https://github.com/freeCodeCamp/freeCodeCamp/issues/64121)** (freeCodeCamp) - Workshop – Artifact Provenance Auditor
- **[#64111](https://github.com/freeCodeCamp/freeCodeCamp/issues/64111)** (freeCodeCamp) - Workshop – Delivery Route Merger
- **[#62778](https://github.com/freeCodeCamp/freeCodeCamp/issues/62778)** (freeCodeCamp) - CSS Projects Availability Table: Enhance Table Accessibility with ARIA and Captions
- **[#61779](https://github.com/freeCodeCamp/freeCodeCamp/issues/61779)** (freeCodeCamp) - Include async/await workshop in FullStack Curriculum
- **[#60472](https://github.com/freeCodeCamp/freeCodeCamp/issues/60472)** (freeCodeCamp) - Refactor shopping cart workshop

### Assigned Issues — Waiting for PR

- **[#64124](https://github.com/freeCodeCamp/freeCodeCamp/issues/64124)** (freeCodeCamp) - Workshop – Weather Trend Analyzer; assigned to aliyasyeddd, waiting for CurriculumExpansion/fCC PR
- **[#64126](https://github.com/freeCodeCamp/freeCodeCamp/issues/64126)** (freeCodeCamp) - Lab – Data Sanitizer Sweep; assigned to MarkI2, waiting for CurriculumExpansion/fCC PR
- **[#64127](https://github.com/freeCodeCamp/freeCodeCamp/issues/64127)** (freeCodeCamp) - Workshop – Festival Crowd Flow Simulator; assigned to LGH831, waiting for CurriculumExpansion/fCC PR
- **[#64117](https://github.com/freeCodeCamp/freeCodeCamp/issues/64117)** (freeCodeCamp) - Workshop – Smart Campus Directory; assigned to Rudro4038, waiting for CurriculumExpansion/fCC PR
- **[#64627](https://github.com/freeCodeCamp/freeCodeCamp/issues/64627)** (freeCodeCamp) - Create a prototype for Python functions workshop; assigned to ahmedmahfoudhi, waiting for CurriculumExpansion/fCC PR
- **[#64630](https://github.com/freeCodeCamp/freeCodeCamp/issues/64630)** (freeCodeCamp) - Audit and update prototype for d3 Dashboard workshop; assigned to meemeealm, waiting for CurriculumExpansion/fCC PR
- **[#62351](https://github.com/freeCodeCamp/freeCodeCamp/issues/62351)** (freeCodeCamp) - Make the "Build a Magazine" workshop HTML more semantic; assigned to maryojo, waiting for fCC PR
- **[#64122](https://github.com/freeCodeCamp/freeCodeCamp/issues/64122)** (freeCodeCamp) - Lab – Traffic Light Sequencer; assigned to AdityaSingh-18, prototype approved in CurriculumExpansion#1147, waiting for fCC PR

### Awaiting Author Response

- **[#65515](https://github.com/freeCodeCamp/freeCodeCamp/pull/65515)** (freeCodeCamp) - Playlist Remix Engine lab; left inline comments on 2026-03-18 (missing user story for empty array validation, redundant parameter check, solution indentation and semicolons, `name` field in block JSON); waiting for author to address
- **[#66235](https://github.com/freeCodeCamp/freeCodeCamp/pull/66235)** (freeCodeCamp) - fix regex for todo form input checks; left review that the material is archived and not maintained, waiting for author response
- **[#66340](https://github.com/freeCodeCamp/freeCodeCamp/pull/66340)** (freeCodeCamp) - enforce workshop file validations; left comment asking whether `isLastStep` could use block.json instead of filesystem scanning; waiting for author to respond and update
- **[#66522](https://github.com/freeCodeCamp/freeCodeCamp/pull/66522)** (freeCodeCamp) - Python functions workshop prototype; left comment to move to draft and inline comment to fix intro.json ordering on 2026-03-17; waiting for author to address
- **[#65964](https://github.com/freeCodeCamp/freeCodeCamp/pull/65964)** (freeCodeCamp) - binary search workshop; left review on 2026-03-17 with inline suggestions (challengeType, intro.json, step 9 typo, console.log regex); waiting for author to address
- **[#66233](https://github.com/freeCodeCamp/freeCodeCamp/pull/66233)** (freeCodeCamp) - fix Python V9 setter examples; requested changes (step 28 seed missing update, step 21 description inaccurate), waiting for author to address
- **[CurriculumExpansion#1136](https://github.com/freeCodeCamp/CurriculumExpansion/pull/1136)** (CurriculumExpansion) - world map workshop prototype; left comment flagging d3.event bug, test.html removal, and cleanup items, waiting for author to address
- **[CurriculumExpansion#1152](https://github.com/freeCodeCamp/CurriculumExpansion/pull/1152)** (CurriculumExpansion) - left comment on 2026-03-17 asking author to test in a curriculum page before updating the prototype; waiting for author response
- **[CurriculumExpansion#1140](https://github.com/freeCodeCamp/CurriculumExpansion/pull/1140)** (CurriculumExpansion) - Proofreading Tool lab prototype; requested changes (folder rename, `analyzeTexts` spelling, `repeatedWordsIndices` typo, user story detail, example function calls); review implementation after next update
- **[CurriculumExpansion#1087](https://github.com/freeCodeCamp/CurriculumExpansion/pull/1087)** (CurriculumExpansion) - Escape Room Code Runner workshop prototype, nudged on 2026-03-17; bring up immediately if activity, otherwise next week
- **[CurriculumExpansion#1071](https://github.com/freeCodeCamp/CurriculumExpansion/pull/1071)** (CurriculumExpansion) - Sensor Burst Analyzer workshop prototype, nudged on 2026-03-16; bring up immediately if activity, otherwise next week
- **[CurriculumExpansion#1078](https://github.com/freeCodeCamp/CurriculumExpansion/pull/1078)** (CurriculumExpansion) - Guild Loot Tracker lab prototype, nudged on 2026-03-16; bring up immediately if activity, otherwise next week
- **[#65643](https://github.com/freeCodeCamp/freeCodeCamp/pull/65643)** (freeCodeCamp) - Story Fragment Shuffler lab, nudged on 2026-03-16; bring up immediately if activity, otherwise next week
- **[#65338](https://github.com/freeCodeCamp/freeCodeCamp/pull/65338)** (freeCodeCamp) - Device Loan Ledger lab, nudged on 2026-03-16; bring up immediately if activity, otherwise next week

### My PRs — Approved, Watching for Merge

- **[#62913](https://github.com/freeCodeCamp/freeCodeCamp/pull/62913)** (freeCodeCamp) - Build a Chart Lab, approved by jdwilkin4, waiting for second review; move back to todo if changes requested
- **[#66215](https://github.com/freeCodeCamp/freeCodeCamp/pull/66215)** (freeCodeCamp) - Express theory block, approved by Sembauke, waiting for second review; move back to todo if changes requested
- **[contribute#1264](https://github.com/freeCodeCamp/contribute/pull/1264)** (contribute) - Seed code indentation and hyphenation rules; waiting for review and merge

### Auto-merge Enabled

- **[#66197](https://github.com/freeCodeCamp/freeCodeCamp/pull/66197)** (freeCodeCamp) - 2026-03-18

### Blocking — Waiting for Merge

- **[contribute#1259](https://github.com/freeCodeCamp/contribute/pull/1259)** and **[contribute#1260](https://github.com/freeCodeCamp/contribute/pull/1260)** (contribute) - Theory lessons guide and labs/quizzes/reviews updates; when both are merged, add to todo: check contribute#1220 and close it if still unupdated, then open a new PR with the detailed `create-new-project` walkthrough.
- **[curriculum-helpers#559](https://github.com/freeCodeCamp/curriculum-helpers/pull/559)** (curriculum-helpers) - When merged, add #64712 back to todo to review.
- **[#64427](https://github.com/freeCodeCamp/freeCodeCamp/pull/64427)** (freeCodeCamp) - When merged, add to todo list: open issue #65007 for contributors (add `help wanted`).
- **[contribute#1220](https://github.com/freeCodeCamp/contribute/pull/1220)** (contribute) - When merged or closed, add to todo list:
  - Open a PR to document CI test behavior (tests for each step run against the seed of the next step, or solution for the last step)
  - Open a PR to add Python 4-space formatting rule to the style guide
  - Open a PR to break down the curriculum helpers docs into smaller focused files
