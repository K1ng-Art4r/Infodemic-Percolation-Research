# Infodemic Percolation Research

Research project on modeling the spread of misinformation and fact-checking in online social networks using competitive percolation theory.

---

## Overview

This repository contains the code, notebooks, and supporting materials for a scientific research project dedicated to studying **infodemics**—the large-scale spread of misinformation in online social networks.

The project investigates how misinformation propagates through network structures, how echo chambers and bridge links influence diffusion, and how different fact-checking strategies affect the overall dynamics.

The research consists of two complementary parts:

1. **Synthetic competitive percolation model** — an artificial social network used to study information diffusion under controlled conditions.
2. **Empirical validation on the Hoaxy dataset** — verification of the proposed hypotheses using a real-world Twitter retweet network.

---

## Research Goals

The main objective of this research is to answer the following questions:

- Under what conditions does local misinformation become a large-scale infodemic?
- How do echo chambers influence information diffusion?
- What role do bridge links between communities play?
- Which fact-checking strategies are the most effective?
- Can the synthetic model explain patterns observed in real social media data?

---

## Repository Structure

```text
Infodemic-Percolation-Research/
│
├── notebooks/
│   ├── 01_synthetic_infodemic_percolation_model.ipynb
│   └── 02_hoaxy_empirical_validation.ipynb
│
├── data/
│   ├── README.md
│   └── sample/
│
├── results/
│   ├── figures/
│   │   ├── synthetic/
│   │   └── hoaxy/
│   │
│   └── tables/
│       ├── synthetic/
│       └── hoaxy/
│
├── docs/
│   ├── research_summary.md
│   └── methodology.md
│
├── requirements.txt
├── .gitignore
└── README.md
```

---

## Project Workflow

```
Synthetic Network
        │
        ▼
Competitive Percolation Model
        │
        ▼
Monte Carlo Simulation
        │
        ▼
Sensitivity Analysis
        │
        ▼
Empirical Validation (Hoaxy)
        │
        ▼
Research Conclusions
```

---

## Notebooks

### 1. Synthetic Competitive Percolation Model

`notebooks/01_synthetic_infodemic_percolation_model.ipynb`

This notebook introduces the proposed theoretical model.

It includes:

- generation of synthetic social networks;
- echo chamber modeling;
- bridge link generation;
- influencer modeling;
- competitive spreading of misinformation and fact-checking;
- Monte Carlo simulations;
- phase transition analysis;
- intervention strategy comparison;
- visualization of simulation results.

---

### 2. Hoaxy Empirical Validation

`notebooks/02_hoaxy_empirical_validation.ipynb`

This notebook validates the proposed model using the public Hoaxy dataset.

Main analyses include:

- retweet graph construction;
- Louvain community detection;
- bridge vs intra-community analysis;
- PageRank and k-core analysis;
- empirical percolation threshold estimation;
- temporal centrality analysis;
- targeted vs random intervention strategies.

---

## Key Research Ideas

The project treats misinformation and fact-checking as two competing spreading processes over a social graph.

The study focuses on:

- network topology;
- community structure;
- bridge edges;
- influencer effects;
- intervention timing;
- competitive diffusion;
- critical percolation thresholds.

---

## Technologies

- Python
- Google Colab
- Jupyter Notebook
- NumPy
- Pandas
- NetworkX
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn
- python-louvain

---

## Data

The repository contains:

- synthetic network generation code;
- experimental notebooks;
- selected figures and tables.

The full Hoaxy dataset is **not included** because it is downloaded automatically inside the validation notebook from the public source.

---

## Results

The repository contains selected figures and tables illustrating:

- network topology;
- spreading dynamics;
- strategy comparison;
- bridge analysis;
- phase diagrams;
- empirical validation results.

---

## How to Run

Clone the repository:

```bash
git clone https://github.com/K1ng-Art4r/Infodemic-Percolation-Research.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Open the notebooks:

```text
notebooks/01_synthetic_infodemic_percolation_model.ipynb

notebooks/02_hoaxy_empirical_validation.ipynb
```

or launch them directly in Google Colab.

---

## Open in Google Colab

After uploading the repository to GitHub, replace `YOUR_USERNAME` with your GitHub username.

Notebook 1:

https://colab.research.google.com/github/YOUR_USERNAME/Infodemic-Percolation-Research/blob/main/notebooks/01_synthetic_infodemic_percolation_model.ipynb

Notebook 2:

https://colab.research.google.com/github/YOUR_USERNAME/Infodemic-Percolation-Research/blob/main/notebooks/02_hoaxy_empirical_validation.ipynb

---

## Future Work

Possible extensions of the project include:

- temporal network evolution;
- multi-layer social networks;
- adaptive user behavior;
- heterogeneous spreading probabilities;
- reinforcement-learning-based intervention strategies;
- integration with additional real-world datasets.

---

## Citation

If you use this repository in academic work, please cite the corresponding research paper (if available) or reference this repository.

---

## Author

**K1ng-Art4r**

Research project in network science, computational social science, and misinformation dynamics.
