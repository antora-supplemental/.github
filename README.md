# antora-supplemental organization .github

This repo holds **workflow templates** for the organization. When members create a new workflow (Actions → New workflow → Set up a workflow yourself), these templates appear in the sidebar alongside GitHub’s built-in templates.

- **Antora to GitHub Pages** – Build Antora docs and deploy to GitHub Pages. Shown when the repo has `antora-playbook.yml` or `docs/antora.yml`.

To add more templates, add a `.yml` and matching `.properties.json` under `workflow-templates/`. See [Creating workflow templates for your organization](https://docs.github.com/en/actions/using-workflows/creating-starter-workflows-for-your-organization).
