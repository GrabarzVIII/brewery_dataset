# Global Craft Brewery Database 2026

Repository for manual analysis of the Kaggle dataset:
https://www.kaggle.com/datasets/kanchana1990/global-craft-brewery-database-2026

## Current project structure

```text
.
|-- brewery_ds/
|-- data/
|   |-- raw/
|   |   |-- global_craft_brewery_database_2026.csv
|   |   `-- global-craft-brewery-database-2026.zip
|   `-- README.md
|-- notebooks/
|   |-- analysis.ipynb
|   `-- README.md
|-- LICENSE
|-- README.md
`-- requirements.txt
```

## What is included

- `brewery_ds/` with the local Python environment
- `data/raw/` with the downloaded dataset files
- `notebooks/analysis.ipynb` with the analysis notebook
- `requirements.txt` with the project dependencies

## Data files

The following raw files are available in `data/raw/`:

- `global_craft_brewery_database_2026.csv`
- `global-craft-brewery-database-2026.zip`

## Notebook

The main analysis lives in `notebooks/analysis.ipynb`.

## Getting started

```powershell
.\brewery_ds\Scripts\Activate.ps1
jupyter lab
```

Then open `notebooks/analysis.ipynb`.

## Recreate the environment

```powershell
python -m venv brewery_ds
.\brewery_ds\Scripts\Activate.ps1
python -m pip install -r requirements.txt
```
