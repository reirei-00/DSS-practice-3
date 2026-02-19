# Data Mining Techniques Lab

Short local lab aligned with:
- Lecture 7.1: Data Mining
- Lecture 7.2: Decision Trees

## What is included

- `lab_data_mining_techniques.ipynb`: main lab notebook on Iris (executed with outputs)
- `lab_data_mining_techniques_taxi.ipynb`: advanced lab notebook on Taxi trips (executed with outputs)
- `lab_missing_age_imputation_titanic.ipynb`: focused lab on missing female age + imputation distortion (executed with outputs)
- `data/taxis.csv`: local taxi dataset used by the advanced notebook
- `data/titanic.csv`: local Titanic dataset used by the imputation-distortion lab
- `requirements.txt`: Python dependencies
- `start_lab.sh`: one-command local launcher

## Techniques covered

- Data visualization for exploratory analysis
- Clustering with K-Means (with PCA visualization)
- Classification with Decision Trees
- Split criteria comparison: `gini` vs `entropy`
- Missing data handling with `SimpleImputer` (`mean`, `median`, `most_frequent`)
- Missing data handling with `KNNImputer`
- Overfitting check via depth vs accuracy plots
- Feature importance visualization
- Output interpretation comments after result cells
- 10 assignment variants for 10 students

## Dataset

Notebook versions and datasets:
- `lab_data_mining_techniques.ipynb` uses **Iris** via `sklearn.datasets.load_iris`
- `lab_data_mining_techniques_taxi.ipynb` uses a local open-source **Taxi trips** dataset at `data/taxis.csv`
- `lab_missing_age_imputation_titanic.ipynb` uses a local open-source **Titanic** dataset at `data/titanic.csv`

No manual download is required.

## Quick start

```bash
cd /Users/vittoriadiachenko/Projects/data-mining-techniques-lab
./start_lab.sh
```

## Manual start

```bash
cd /Users/vittoriadiachenko/Projects/data-mining-techniques-lab
python3 -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
jupyter lab
```

Open `lab_data_mining_techniques.ipynb` and run cells top to bottom.
Or open `lab_data_mining_techniques_taxi.ipynb` for the more complex taxi-focused version.
Or open `lab_missing_age_imputation_titanic.ipynb` for the missing-age imputation distortion case study.
