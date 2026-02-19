# Data Science Through Baseball

This repo is meant for baseball and sports enthusiasts who want to learn and apply data science concepts through a series of projects and notebooks — all through the familiar and exciting lens of baseball. Whether you're a fantasy baseball player, an aspiring analyst, or just curious about the numbers behind the game, this series will take you from Python fundamentals to applied machine learning using real MLB data.

## Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook or JupyterLab

### Installation

```bash
git clone https://github.com/your-username/baseball-data-science-series.git
cd baseball-data-science-series
pip install -r requirements.txt
```

Individual sections also have their own `requirements.txt` if you prefer to install dependencies as you go.

## Learning Path

The notebooks are designed to be followed in order. Each section builds on the previous one.

### 1. Python Basics

> **Folder:** [`python-basics/`](python-basics/)

A ground-up introduction to Python programming — no prior experience required. Every example uses baseball data to keep things relevant.

| Notebook | Topics |
|----------|--------|
| [01 - Intro to Python](python-basics/01_intro_to_python.ipynb) | Variables, data types, lists, dictionaries, loops, conditionals, functions. Ends with a mini capstone building a player stats report. |
| [02 - Data Manipulation](python-basics/02_data_manipulation.ipynb) | NumPy arrays, Pandas Series & DataFrames, filtering, grouping, merging, pivot tables, and data export — all using MLB batting stats. |
| [03 - Data Visualization](python-basics/03_data_visualization.ipynb) | Matplotlib, Seaborn, and Pandas plotting. Covers line/bar/scatter plots, histograms, heatmaps, pair plots, and subplots. Ends with a multi-panel dashboard capstone. |

### 2. How to Get Baseball Data

> **Folder:** [`how-to-get-baseball-data/`](how-to-get-baseball-data/)

| Notebook | Topics |
|----------|--------|
| [Extracting Baseball Data](how-to-get-baseball-data/extracting_baseball_data.ipynb) | Pulling real data from **pybaseball** (Statcast, Baseball Reference, FanGraphs), **MLB-StatsAPI**, and **pylahman** (historical Lahman database). Includes sample Statcast datasets for Shohei Ohtani and Tarik Skubal's 2024 seasons. |

### 3. Unsupervised Learning Part 1 — Clustering

> **Folder:** [`unsupervised-learning-pt-1-clustering/`](unsupervised-learning-pt-1-clustering/)

| Notebook | Topics |
|----------|--------|
| [Intro to Clustering](unsupervised-learning-pt-1-clustering/intro_to_clustering.ipynb) | Supervised vs. unsupervised learning, K-Means algorithm (step-by-step), feature scaling, the Elbow Method, Silhouette Score. Applied to pitch classification, pitcher archetypes, and team playing styles using Statcast data. |
| Advanced Clustering *(coming soon)* | DBSCAN, hierarchical clustering, Gaussian Mixture Models, and advanced evaluation techniques. |

### More Coming Soon

Future sections and projects are in the works, including:

- Unsupervised Learning Part 2 — Dimensionality Reduction
- Sample projects applying these techniques to real baseball questions

## Sample Projects

> **Folder:** [`sample-projects/`](sample-projects/)

Standalone notebooks that apply concepts from the series to specific baseball analysis problems.

| Project | Status |
|---------|--------|
| Advanced Pitch Clustering | Coming soon |
| Reverse Tunneling Analysis | Coming soon |

## Key Libraries

| Library | Purpose |
|---------|---------|
| `numpy` | Numerical operations and arrays |
| `pandas` | Tabular data manipulation |
| `matplotlib` | Static visualizations |
| `seaborn` | Statistical visualizations |
| `plotly` | Interactive visualizations |
| `scikit-learn` | Machine learning algorithms and evaluation |
| `pybaseball` | Statcast, Baseball Reference, and FanGraphs data |
| `MLB-StatsAPI` | Official MLB statistics API |
| `pylahman` | Historical Lahman baseball database |

## Contributing

Found a bug or have a suggestion? Feel free to open an issue or submit a pull request.
