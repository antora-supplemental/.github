# antora-supplemental organization: `.github`

Canonical **public-repo** organization configuration.

## Purpose

GitHub organization-level community and workflow configuration for the organization's **public** repositories:

* Brand assets under `assets/` (`logo.svg`, `logo-avatar.svg`, `logo-256.png`)
* Starter workflow templates under `workflow-templates/`
* Org profile README under `profile/`

Private repositories use the sibling [`.github-private`](https://github.com/antora-supplemental/.github-private) repository — not a personal bootstrap fork.

## Brand assets

Org mark and avatar files live under `assets/`. Upload `logo-256.png` in GitHub organization profile settings when changing the avatar. Keep copies in sync with `.github-private/assets/` and the welcome-site / docs overlays when the mark changes. Details: [`assets/README.md`](assets/README.md).

## Workflow templates

To add organization workflow starter templates, place template files under `workflow-templates/` following GitHub's documentation:

https://docs.github.com/en/actions/using-workflows/creating-starter-workflows-for-your-organization

## See also

* Private org config: https://github.com/antora-supplemental/.github-private
* Docs hub (Actions / Pages): https://antora-supplemental.github.io/docs/docs/antora-github-actions.html
