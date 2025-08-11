# rsfmri-binder-starter

Non-specialized, no-login workflow for resting-state fMRI ROI time-series visualization (DLPFC & ACC) using Binder + Nilearn.

## How to Launch (update after you create the GitHub repo)
- Replace `<user>` and `<repo>` below with your GitHub user/org and repo name.
- Binder (JupyterLab) will open `notebooks/task1.ipynb` in the browser without any login.

Binder badge (replace placeholders):
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/<user>/<repo>/main?labpath=notebooks%2Ftask1.ipynb)

## Contents
- `notebooks/task1.ipynb` — starter notebook (to be filled with preprocessing, ROI extraction, QC, and plotting steps).
- `environment.yml` — pinned environment for mybinder.
- `LICENSE` — MIT for code.

## Licenses
- **Code:** MIT (see `LICENSE`).
- **Content & documentation (e.g., reports, instructions):** CC BY 4.0 — commercial use allowed.
- **Datasets/Atlases:** Check and cite each source's license separately in the notebook header (e.g., `nilearn.datasets.fetch_development_fmri`, `fetch_coords_dosenbach_2010`).

## Notes
- Binder sessions are ephemeral; save important outputs to your shared Etherpad/Ethercalc links or commit them back to the repo.
- Test your Binder link in an incognito window.
