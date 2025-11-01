You are part of a DevOps team at a startup developing a web-based product. To ensure code quality, maintainable history, and automated changelog generation, your company has adopted Conventional Commits as a standard for commit messages.

Format: <type>(<scope>): <description>
Types include: feat, fix, chore, docs, style, refactor, perf, test, build, ci, revert.

The goal of this activity is to implement a GitHub Action that enforces commit message standards on Pull Requests (PRs). This workflow will:
-> Automatically validate all commits in PR.
-> Reject PRs containing commits that do not follow the regex.
-> Provide clear error messages for developers.
