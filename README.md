# actions
My GitHub Actions

## Actions

### changed-files
Get changed files when pull request.

- Definition: [changed-files](./.github/actions/changed-files/action.yml)
- Example: [example-changed-files.yaml](./.github/workflows/example-changed-files.yaml)

## Callable Workflows

### renovate.yaml
Validate and Dry-run of the renovate config.

- Definition: [renovate.yaml](./.github/workflows/renovate.yaml)
- Example: [example-renovate.yaml](./.github/workflows/example-renovate.yaml)

### notify-to-slack.yaml
Notify to Slack.

- Definition: [notify-to-slack.yaml](./.github/workflows/notify-to-slack.yaml)
- Example: [example-notify-to-slack.yaml](./.github/workflows/example-notify-to-slack.yaml)

### tagging.yaml
Create git tag and GitHub Release.

- Definition: [tagging.yaml](./.github/workflows/tagging.yaml)
- Example: [example-tagging.yaml](./.github/workflows/example-tagging.yaml)

## Release
1. Open [Tagging and Release action page](https://github.com/korosuke613/actions/actions/workflows/tagging.yaml).
2. Click `Run workflow`.
3. Input version.
4. Click `Run workflow`.
