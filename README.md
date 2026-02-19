# Data Mining Techniques Lab

Short local lab aligned with:
- Lecture 7.1: Data Mining
- Lecture 7.2: Decision Trees

## What is included

- `lab_data_mining_techniques.ipynb`: main lab notebook (executed with outputs)
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

The notebook uses the open-source **Iris** dataset loaded via:
- `sklearn.datasets.load_iris`

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
