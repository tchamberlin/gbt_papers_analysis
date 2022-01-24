# GBT Papers Analysis

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/tchamberlin/gbt_papers_analysis/main?labpath=gbt_papers_analysis.ipynb)

Proof of concept for matching GBT papers to "science category" via the [Unified Astronomy Thesaurus](https://astrothesaurus.org/)


See the "Binder" link above for an interactive notebook with no extra steps.

See [gbt_papers_analysis.ipynb](./gbt_papers_analysis.ipynb) for a static representation (faster, but not interactive)

Or, continue below to run/edit locally

## Installation

```bash
# Must use Python 3.9+ (3.8 might also work, but definitely nothing below that due to f-string syntax)
python3.9 -m venv /path/to/venv
# Enter virtual environment
source /path/to/venv/bin/activate
# optional, but a good idea to update pip and build tools
pip install -U pip setuptools
pip install -r requirements.txt
```

## Run

```bash
# Open the notebook directly in Jupyter Lab
jupyter lab ./gbt_papers_analysis.ipynb
```
