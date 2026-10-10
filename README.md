> Written manually, without AI assistance.

# at1_adsi â€” NBA Player Classification

## What this does

Classifies NBA players from their attributes and statistics with machine
learning â€” including predicting rookie-player longevity. Covers data
cleaning, exploratory data analysis, and modelling experiments in Jupyter
notebooks.

## Business process

Raw player statistics go in; a classification of each player comes out. The
pipeline is: collect the stats â†’ clean them â†’ explore them â†’ train and compare
models â†’ read off which attributes actually predict longevity.

## Technical flow

`image_preprocessing.py`-style preparation aside, the project follows the
standard modelling loop: `notebooks/` for EDA, `src/` for reusable model
code, trained artefacts in `models/`, figures and write-ups in `reports/`.
The full setup guide (virtualenv, `requirements.txt`, `Makefile`,
`tox.ini`) lives in [`at1_adsi/README.md`](at1_adsi/README.md).

## Repository structure

- [`at1_adsi/`](at1_adsi/) â€” the project (cookiecutter data-science layout:
  `src`, `notebooks`, `models`, `reports`, `references`)
- `.gitattributes`, root config â€” repository housekeeping

## How to run

See [`at1_adsi/README.md`](at1_adsi/README.md): create a virtualenv,
install `requirements.txt`, then open the notebooks.
