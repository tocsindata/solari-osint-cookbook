# Maintenance

Normal setup and update entry points are:

- Linux: `./update.sh`
- macOS: `./update-macos.sh`
- Windows PowerShell: `.\\update.ps1`

The scripts verify the repository identity and require the current branch to be `develop` or `develop/*`; they fast-forward, create a Python environment, install dependencies, run static-console and Python tests, and report a missing `SOLARI_API_KEY` without inventing one.

CI uses Python 3.12 and Node.js 20. The last verified develop-baseline CI and cross-platform updater runs passed on 2026-09-01. Live provider tests require an operator-supplied key and remain separately tracked.

See `documentation/human/guides/` for the preserved detailed quickstart, smoke-test, debugging, review, and submission material.
