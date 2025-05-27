# Rare Event Estimation in Option Portfolios

This project was developed as part of the "Simulation numérique aléatoire" course at École polytechnique.

It focuses on estimating probabilities of rare events and quantiles in portfolios composed of European options (calls and puts), using various Monte Carlo-based techniques.

## 🔢 Problem Description

We simulate the terminal value of portfolios composed of European options, where each asset follows a geometric Brownian motion.

The goal is to estimate:
- Probabilities of rare events,
- Quantiles of the distribution of the porfolios value (e.g. 99.99999% quantile).

## 🧠 Methods Implemented

- **Naive Monte Carlo**: empirical estimation using direct sampling.
- **Importance Sampling (IS)**:
  - Via Brownian drift change,
  - Via Esscher transform (exponential tilt).
- **Quantile estimation** under IS using weighted empirical CDF.
- **Splitting methods** for more robust rare event estimation.

## 📦 Files

- `Rapport_SNA.pdf`: full mathematical report (in French),
- `notebook.ipynb`: all experiments and results in Python,
- `photos/`: figures generated for the report,
- `requirements.txt`: Python dependencies.

## ⚙️ Installation

Clone the repo and install dependencies:

```bash
git clone https://github.com/astride11/Random-Numerical-Simulation-for-Rare-Events.git
cd Random-Numerical-Simulation-for-Rare-Events
pip install -r requirements.txt
```

## 👨‍🔬 Authors

- Mallo Poundi Christel Astride  
- Dzikouk Frank Dilane  

---

## 🗓 Submission

May 2025

