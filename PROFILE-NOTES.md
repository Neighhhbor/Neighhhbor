# Maintaining this profile

- `README.md` is displayed on the GitHub profile because this public repository matches the account name.
- `assets/header.svg` is the custom terminal illustration. It is self-contained and respects reduced-motion preferences.
- `.github/workflows/snake.yml` generates the contribution animation each day at 02:23 UTC (10:23 China time), and can be run manually from Actions.
- Generated SVGs live on the `output` branch. Bot commits stay off `main`.
- The workflow uses the repository-scoped `GITHUB_TOKEN`; no personal access token or external dashboard service is required. Third-party actions are pinned to commit hashes.
- GitHub may disable scheduled workflows in inactive public repositories. If the graphic stops updating, check Actions and re-enable/run the workflow.
- Featured team repositories are labeled **contributor**, with links to the account's own contributions. Do not imply sole ownership of team projects.
- The four intended profile pins are `polaris-pku/newide-scaffold`, `jiangxxxue/KOCO-bench`, `polaris-pku/acp-client-prototype`, and `Neighhhbor/Schedule`.

The profile uses native GitHub Markdown/HTML and SVG images. Visitors do not need to install anything.
