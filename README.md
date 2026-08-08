# GitHub Codespaces ♥️ Jupyter Notebooks

Welcome to your shiny new codespace! We've got everything fired up and running for you to explore Python and Jupyter notebooks.

You've got a blank canvas to work on from a git perspective as well. There's a single initial commit with what you're seeing right now - where you go from here is up to you!

Everything you do here is contained within this one codespace. There is no repository on GitHub yet. If and when you’re ready you can click "Publish Branch" and we’ll create your repository and push up your project. If you were just exploring then and have no further need for this code then you can simply delete your codespace and it's gone forever.

## Stale issue automation

This repository includes a GitHub Actions workflow at `/home/runner/work/organization/organization/.github/workflows/close-stale-issues.yml` that marks inactive issues as stale and closes them if no follow-up activity is added.

- Schedule: weekly (Monday at 03:00 UTC)
- Manual run: supported through **Run workflow** (`workflow_dispatch`)
- Scope: issues only (pull requests are not processed)
- Thresholds: mark stale after 60 days, close 7 days later
- Exemptions: issues with `pinned`, `security`, or `bug` labels, plus any issue with assignees or milestones

To keep an issue open, add a comment to remove stale state.

To pause automation, disable the workflow in GitHub Actions or remove the `schedule` trigger from the workflow file.
