# Workflows

This repository maintains reusable GitHub workflow templates under `workflows/`.
Generated IP repositories can include the `check-workflow-sync.yml` workflow to
pull updates from this folder and stage them for manual activation.

## Workflow sync behavior

The `workflows/check-workflow-sync.yml` workflow in generated IP repositories:

- Runs on a daily schedule and via `workflow_dispatch`.
- Fetches the list of `*.yml`/`*.yaml` files from this repo’s `workflows/` folder.
- Downloads each file into `.github/workflows-staged/` of the IP repo.
- Commits the staged files to the default branch.
- Opens a new issue on each run, listing the staged files and instructions to
  copy them into `.github/workflows/` to activate them.

Notes:

- The sync workflow does not modify `.github/workflows/` directly because
  GitHub restricts automated updates to workflow files without extra
  permissions.
- Activation is manual: copy from `.github/workflows-staged/` to
  `.github/workflows/` as needed.

## Adding new workflow templates

1. Add the new workflow file to `workflows/` in this repository.
2. The next sync run in generated IP repositories will stage the file under
   `.github/workflows-staged/` and open an issue with the file name.
