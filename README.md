# investment-thesis
investment-thesis

## Push updates to Git

Use these steps after editing files in this repository:

```bash
git status
git add <file-or-folder>
git commit -m "Describe the update"
git push origin main
```

If you are on a different branch, replace `main` with your branch name.

## Pull new-energy data

Run this before refreshing the scorecard:

```bash
python3 scripts/pull_new_energy_data.py --days 45
```

The script writes BSE quote and announcement API snapshots under `data/new-energy/`.
