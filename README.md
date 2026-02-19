# Data Mining Techniques Lab

Short local lab aligned with:
- Lecture 7.1: Data Mining
- Lecture 7.2: Decision Trees

## What is included

- `lab_data_mining_techniques.ipynb`: main lab notebook
- `requirements.txt`: Python dependencies

## Techniques covered

- Data visualization for exploratory analysis
- Clustering with K-Means (with PCA visualization)
- Classification with Decision Trees
- Split criteria comparison: `gini` vs `entropy`
- Missing data handling with imputation:
  - `SimpleImputer` (`mean`, `median`, `most_frequent`)
  - `KNNImputer`
- Overfitting check via depth vs accuracy plots
- Feature importance visualization

## Dataset

The notebook uses the open-source **Wine dataset** loaded via:
- `sklearn.datasets.load_wine`

No manual download is required.

## Local run

```bash
cd /Users/vittoriadiachenko/Projects/data-mining-techniques-lab
python3 -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
jupyter lab
```

Open `lab_data_mining_techniques.ipynb` and run cells top to bottom.

Alternative one-command start:

```bash
cd /Users/vittoriadiachenko/Projects/data-mining-techniques-lab
./start_lab.sh
```
