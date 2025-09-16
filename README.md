# Interaction Map Auto Scan (Binder-ready)

This repo contains a Jupyter notebook and minimal configuration to launch it on Binder.

## Quick start

1. Create a new GitHub repo (e.g., `interaction-map-binder`) and push these files.
2. Click the badge below, or paste your repo URL on [https://mybinder.org](https://mybinder.org).

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/YOUR_GITHUB_USERNAME/interaction-map-binder/HEAD?labpath=Interaction_map_auto_scan_2025.ipynb)

> Replace `YOUR_GITHUB_USERNAME` with your actual username (or `org` name).

## Contents

- `Interaction_map_auto_scan_2025.ipynb` — your original notebook.
- `requirements.txt` — inferred Python dependencies for Binder.
- `.gitignore`

## Notes on dependencies

The requirements were inferred automatically from `import` statements in the notebook. You may need to **add** extra packages (e.g., domain tools) or **pin** versions for reproducibility.

### Possibly non-pip or special packages

The following imports may require a conda install or a custom setup (not available on PyPI by default): None.

### Unknown imports

These imports weren't mapped to pip packages automatically. If they are real packages, add them to `requirements.txt`: None.

## Local run

```bash
pip install -r requirements.txt
jupyter lab
```
