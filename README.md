# Commit conventions

PR titles feed the changelog. Titles must start with `chore`, `fix`, or `feat`.

**Lint PR Title** runs on `workflow_dispatch` and on every pull request. It uses `COMMITLINT_TOKEN` (repository) and `COMMITLINT_SHARED_TOKEN` (organization, selected for this repo) against the internal commitlint API.
