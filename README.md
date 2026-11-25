# Computational Physics – Notebooks

Jupyter notebooks for the exercises of *Computational Physics* (260069-1 PUE, University of Vienna, WS 2026/27).
They run in the browser, no installation needed.

| Exercise | Notebook | Launch |
|---|---|---|
| 7 – LU decomposition | `notebooks/07_lu_decomposition.ipynb` | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/c-abird/compphys-notebooks/HEAD?labpath=notebooks/07_lu_decomposition.ipynb) |

## How to use

1. Click the Binder badge (or scan the QR code on the exercise sheet). The first start can take a few minutes.
2. Fill in the gaps marked `# YOUR CODE HERE` and delete the line `raise NotImplementedError`.
   The check cell after each gap prints ✓ or ✗.
3. **Save your work:** Binder sessions are temporary and are deleted after a few minutes of inactivity.
   Download the notebook (*File → Download*) and any files it writes (e.g. `my_lu.py`).

## Local run (optional)

```sh
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt jupyterlab
jupyter lab
```
