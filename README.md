# Global Craft Brewery Database 2026

Prosty folder do samodzielnej analizy datasetu Kaggle:
https://www.kaggle.com/datasets/kanchana1990/global-craft-brewery-database-2026

## Co jest gotowe

- `brewery_ds` jako lokalne virtualenv
- pliki datasetu w `data/raw/`
- czysty notebook w `notebooks/analysis.ipynb`
- lekkie `requirements.txt`

## Pliki danych

W `data/raw/` są:

- `global_craft_brewery_database_2026.csv`
- `global-craft-brewery-database-2026.zip`

## Start

PowerShell:

```powershell
.\brewery_ds\Scripts\Activate.ps1
jupyter lab
```

Potem otwórz `notebooks/analysis.ipynb`.

## Odtworzenie środowiska

```powershell
python -m venv brewery_ds
.\brewery_ds\Scripts\Activate.ps1
python -m pip install -r requirements.txt
```
