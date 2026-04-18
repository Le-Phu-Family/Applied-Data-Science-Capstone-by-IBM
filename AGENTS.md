# AGENTS.md

Guidance for AI coding agents working in this repository.

## Project Scope
- This is an IBM Applied Data Science Capstone notebook workspace.
- Most work happens in Jupyter notebooks across these folders:
  - collect the data/
  - eda/
  - interactive visual/
  - predictive analysis/
  - report/
- Primary local data artifacts are in data/.

## Start Here
- Read [README.md](README.md) first.
- Prefer keeping analysis changes inside existing notebooks unless asked to create standalone scripts.

## Notebook-First Workflow
- Open and run notebooks in order of project stages:
  1. collect the data
  2. eda
  3. interactive visual
  4. predictive analysis
  5. report
- Preserve existing cell order and narrative markdown when editing lab notebooks.
- Keep code changes minimal and scoped to the requested task.

## Environment and Dependencies
- No dependency lockfile is present; infer required packages from notebook imports.
- Common packages used here: pandas, numpy, matplotlib, seaborn, requests, beautifulsoup4, folium, ipython-sql, prettytable.
- Some notebooks include browser-specific patterns such as piplite and from js import fetch. If running locally, replace these with standard Python equivalents (pip-installed packages and requests/pandas URL loading) only when needed for the task.

## Data and Paths
- Keep generated CSV outputs in data/ unless the user asks otherwise.
- Use relative paths and keep folder names unchanged (some include spaces).
- Do not rename existing notebooks or directories without explicit user approval.

## Editing Conventions
- Prefer surgical edits over large notebook rewrites.
- Maintain existing naming conventions and assignment-style task headings used in the notebooks.
- When adding new cells, include a short markdown heading describing purpose.

## Validation
- Validate by running the edited notebook cells relevant to the requested change.
- For SQL notebooks, verify %sql cells still execute after changes.
- If execution requires unavailable external network resources, explain the limitation and provide a local fallback path.

## What To Avoid
- Do not add unrelated tooling/config files unless explicitly requested.
- Do not remove existing outputs or markdown instructions that are part of lab deliverables.
