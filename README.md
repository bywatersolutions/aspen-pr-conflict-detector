# Aspen PR Conflict Detector

Detects open pull requests on the Aspen Discovery repos that change the same code, so you can find out about overlapping work before either PR merges.

This repo just hosts a scheduled workflow that runs [github-community-projects/pr-conflict-detector](https://github.com/github-community-projects/pr-conflict-detector) against:

- [Aspen-Discovery/aspen-discovery](https://github.com/Aspen-Discovery/aspen-discovery)
- [Aspen-Discovery/aspen-lida](https://github.com/Aspen-Discovery/aspen-lida)

## How it works

Hourly on weekdays (and on demand via `workflow_dispatch`), the workflow scans all open PRs in the repos above, including drafts. For each PR it fetches the changed files and modified line ranges, then flags pairs of PRs that touch overlapping line ranges in the same files. Pairs where both PRs have the same author are filtered out.

## Where to look

- **[`pr_conflict_report.md`](./pr_conflict_report.md)**: the latest conflict report, committed back to this repo after every run. Git history on the file shows how conflicts have evolved over time.
- **[`pr_conflict_report.json`](./pr_conflict_report.json)**: the same data in JSON, for tooling.
- Each run's step summary in the [Actions tab](../../actions) shows the report as well.

## Tuning

Knobs worth knowing about in `.github/workflows/pr-conflict-detector.yml`:

- `EXEMPT_PRS: "123,456"` excludes specific PR numbers, useful if a long-lived PR generates constant noise.

The full option list is in the [upstream README](https://github.com/github-community-projects/pr-conflict-detector#configuration).
