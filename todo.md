# Todo List

## Re-review

- Re-review https://github.com/freeCodeCamp/freeCodeCamp/pull/67279 — author pushed new commit after inline suggestions (Oxford commas, REPL spacing, trailing spaces)
- Re-review https://github.com/freeCodeCamp/freeCodeCamp/pull/66510 — author pushed new commit after inline suggestions (exampleConfig → config1, indentation)
- Re-review https://github.com/freeCodeCamp/curriculum-helpers/pull/582 — author pushed new commit after review (getStyleAny tests don't catch the bug)
- Re-review https://github.com/freeCodeCamp/curriculum-helpers/pull/584 — author pushed new commit after review (wrong approach + issue not linked)
- Re-review https://github.com/freeCodeCamp/freeCodeCamp/pull/66298 — Smart Pantry Restocker; author (aBeholic) pushed commit and commented on 2026-03-16 after CHANGES_REQUESTED

## Check In (Stale)

- https://github.com/freeCodeCamp/freeCodeCamp/pull/64427 — inactive for 27 days, need check in
- https://github.com/freeCodeCamp/freeCodeCamp/pull/66867 — inactive for 10 days, need check in
- https://github.com/freeCodeCamp/freeCodeCamp/pull/66936 — inactive for 9 days, need check in
- https://github.com/freeCodeCamp/curriculum-helpers/pull/561 — inactive for 7 days, need check in
- https://github.com/freeCodeCamp/freeCodeCamp/pull/66235 — inactive for 66+ days; material is archived, consider closing
- https://github.com/freeCodeCamp/freeCodeCamp/pull/65643 — inactive for 66+ days, need check in
- https://github.com/freeCodeCamp/CurriculumExpansion/pull/1078 — inactive for 66+ days, need check in

## Triage

- Triage https://github.com/freeCodeCamp/freeCodeCamp/issues/65887 — improve solution download format to ZIP project structure

## Contribute Docs

### To Open

- Open PR to document test execution order in workshop and lab guides: tests for each step run against the seed of the next step, or the solution block for the last step (workshops only)
- Open PR to add a note that `pnpm run develop` must be running for the "View Live Version" link in the Challenge Editor to work (port 8000); applies to workshop and lab guides
- Open PR to explain position within a module: 1-indexed, based on currently existing blocks; applies to workshop and lab guides
- Open PR to document the `intro.json` update step in the workshop and lab creation workflow
- Open PR to add daily challenges docs (how to add new ones, how to test, how to release) — https://github.com/freeCodeCamp/contribute/issues/1249
- Open PR to add Python 4-space indentation style to the style guide
- Open PR to break down the curriculum helpers docs into smaller focused files
- Open PR with detailed create-new-project walkthrough (CLI questions and intended answers)

### To Check (Issues)

- Check https://github.com/freeCodeCamp/contribute/issues/992 — building freeCodeCamp on codespaces doesn't work; no linked PRs
- Check https://github.com/freeCodeCamp/contribute/issues/1189 — failing command for codespaces users, needs docs tweak
- Check https://github.com/freeCodeCamp/contribute/issues/1142 — document curriculum best practices
- Check https://github.com/freeCodeCamp/contribute/issues/1140 — rename "Work on Codebase" to "Basic Git Workflow"
- Check https://github.com/freeCodeCamp/contribute/issues/1139 — add "Returning to freeCodeCamp" guide
- Check https://github.com/freeCodeCamp/contribute/issues/1179 — rework documentation to be task-oriented with Astro templates

### To Review and Update (Pages)

*Review each page for outdated or missing information and open PRs as needed:*

- `how-to-work-on-coding-challenges.mdx` *(in progress — indentation rules, hyphenation)*
- `how-to-work-on-labs.mdx`
- `how-to-work-on-workshops.mdx`
- `how-to-work-on-quizzes.mdx`
- `how-to-work-on-reviews.mdx`
- `how-to-create-catalog-items.mdx`
- `curriculum-file-structure.mdx`
- `codebase-best-practices.mdx`
- `_hooks-shared.mdx`
- `authors-analytics-manual.mdx`
- `courses-vscode-extension.mdx`
- `curriculum-help.mdx`
- `faq.mdx`
- `getting-started.mdx`
- `how-to-add-playwright-tests.mdx`
- `how-to-catch-outgoing-emails-locally.mdx`
- `how-to-contribute-to-the-codebase.mdx`
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
- `how-to-work-on-localized-client-webapp.mdx`
- `how-to-work-on-the-component-library.mdx`
- `how-to-work-on-the-docs-site.mdx`
- `how-to-work-on-tutorials-that-use-coderoad.mdx`
- `intro.mdx`
- `language-lead-handbook.mdx`
- `moderator-handbook.mdx`
- `moderator-onboarding-guide.mdx`
- `reply-templates.mdx`
- `security.mdx`
- `troubleshooting-development-issues.mdx`
- `user-token-workflow.mdx`
- `writing-style-guide.mdx`

## Translations

*Lowest priority — only when all other work is done or unactionable.*

- Review https://github.com/freeCodeCamp/news-translation-tasks/issues/281 — Skeleton Loader Example – How to Build a Skeleton Screen with CSS for Better UX
- Review https://github.com/freeCodeCamp/news-translation-tasks/issues/376 — Python String Manipulation Handbook
- Review https://github.com/freeCodeCamp/news-translation-tasks/issues/526 — Python Requirements.txt
- Review https://github.com/freeCodeCamp/news-translation-tasks/issues/527 — Google Dorking: How to Find Hidden Information on the Web
- Review https://github.com/freeCodeCamp/news-translation-tasks/issues/534 — Microsoft Excel: 14 Time-Saving Keyboard Shortcuts
- Review https://github.com/freeCodeCamp/news-translation-tasks/pull/631 — Come Lavorare con SQLite in Python

## Utils Scripts

*Decide if/how to integrate into regular workflow (`/home/ilenia/freeCodeCamp/utils-scripts`):*

- `merge-conflict-check.sh` — scans open PRs for merge conflict label mismatches; hardcoded PR numbers, last run August 2025
- `inactive-check.sh` — checks for inactive PRs
- `discussing-inactive-check.sh` — checks for inactive PRs in "discussing" status
- `dfs.py` — unknown purpose, investigate

## To Read

<!-- Articles, docs, issues, or threads worth reading when there's time -->

- https://gist.github.com/raisedadead/cc46e3fe8184013741ab14ff10151ebd
- https://github.com/freeCodeCamp/Claude-Code-Handbook
- https://claude.ai/share/0e8394f8-7b9a-4141-973c-2d48790eb0ab

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
- https://code.claude.com/docs/en/keybindings
