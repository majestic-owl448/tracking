---
description: Describe when these instructions should be loaded
# applyTo: 'Describe when these instructions should be loaded' # when provided, instructions will automatically be added to the request context when the pattern matches an attached file
---
Provide project context and coding guidelines that AI should follow when generating code, answering questions, or reviewing changes.

## Permanent Instructions

When you are told that an instruction will be a permanent one, add it to this file without needing to be prompted to.

User is majestic-owl448 on GitHub. Whenever you get a link to an issue or PR, automatically and immediately write in the current activity file what the user did in that issue or PR—do not ask for confirmation.

Always fetch PR/issue details via API to see comments and actual activity—never guess what was done based on title or description alone.

Before temporarily removing content from a file (e.g., to stage a partial commit), always create a backup copy of the file first (e.g., `cp file.md file.md.bak`). Restore from the backup afterward and delete the backup once done.

### How to Find PR/Issue Activity

When searching for activity from majestic-owl448 on a PR or issue:
1. First use the API fetch to get basic details
2. If the API doesn't show comments or the activity is unclear, use fetch_webpage to view the actual GitHub page—this reliably shows all comments, review actions, and state changes
3. Look specifically for:
   - Comments from majestic-owl448 in the conversation
   - Review approvals or requested changes
   - PR state changes (opened, closed, reopened)
   - Any actions taken by majestic-owl448 on the PR/issue
4. Use the webpage fetch to search for "majestic-owl448" to find all their activity on the page

### Activity File Format

When creating activity files:
- Do NOT include a `**User:**` line in the activity file
- Make issue/PR numbers clickable links using markdown syntax
- **Day-based format**: Activity files are organized by day of the week (Monday through Sunday)
  - Each day section (e.g., `## Monday, March 9`) should be treated independently
  - Add activity entries under the specific day they occurred
  - **If a PR/issue has activity on multiple days**: Create separate entries under each day's section describing only the activity that occurred on that specific day
    - Example: If PR #12345 was reviewed on Monday and merged on Tuesday, it should appear under both Monday (with review activity) and Tuesday (with merge activity)
  - If new activity occurs on a PR/issue already listed under a specific day, update that day's entry to include the new activity
  - Do not move entries between days or consolidate them across days
- **Legacy format** (for older files): Organize the file into two main sections:
  1. **## My PRs** - Pull requests opened by the user (ordered by PR number, ascending)
  2. **## Pull Requests & Issues** - All other activity including reviews, comments, issues opened, and issues commented on (maintained in ascending numeric order)
- Only include PRs in the "My PRs" section if they were opened by the user (not just commented on)

### Activity Description Format

When recording activity for issues and PRs, use these formats:

- For freeCodeCamp/freeCodeCamp: **[#NUMBER](https://github.com/freeCodeCamp/freeCodeCamp/issues/NUMBER)** - Brief description
- For other repos: **[repo#NUMBER](https://github.com/freeCodeCamp/repo/issues/NUMBER)** - Brief description

Examples: `#66215`, `CurriculumExpansion#1149`, `contribute#1228`, `news#1346`

Guidelines for writing descriptions:
- Start with an action verb (opened, closed, reviewed, submitted, etc.)
- Focus only on what the user did, not on labels, status, or other metadata
- Include key details about the issue/PR (e.g., what problem was addressed)
- Keep it concise and scannable (typically one sentence)
- Do not include links or references to related issues unless crucial to understanding the action
- Only describe activity from the current week; mention previous activity only if needed for context (e.g., updating a PR that was opened previously, or responding to a review that was left in a prior week)
- For PRs in the "My PRs" section, track lifecycle changes (merged or closed) by updating the entry to note the status change (e.g., "PR was merged" or "PR was closed")
- Add `(pr)` or `(issue)` immediately after the markdown link and before the dash to distinguish between pull requests and issues (e.g., `**[#66215](https://github.com/org/repo/pull/66215)** (pr) -` or `**[#66178](https://github.com/org/repo/issues/66178)** (issue) -`)
