# Wesleyan Data Analysis and Interpretation Specialization

A reproducible portfolio documenting coursework, data pipelines, statistical analyses, and machine learning models for the **Wesleyan University Data Analysis and Interpretation Specialization** (Coursera).

**Live Portfolio:** [https://tariq-k-dev.github.io/wesleyan-data-analysis/](https://tariq-k-dev.github.io/wesleyan-data-analysis/)

---

## 📌 Project Overview

This repository houses the code, analysis write-ups, and interactive Quarto website tracking progress through the 5-course specialization track:

1. **Course 1: Data Management and Visualization** (`C01-Data-Management-and-Visualization/`)
2. **Course 2: Data Analysis Tools** (`C02-Data-Analysis-Tools/`)
3. **Course 3: Regression Modeling in Practice** (`C03-Regression-Modeling-in-Practice/`)
4. **Course 4: Machine Learning for Data Analysis** (`C04-Machine-Learning-for-Data-Analysis/`)
5. **Course 5: Data Analysis and Interpretation Capstone** (`C05-Data-Analysis-and-Interpretation-Capstone/`)

---

## 📊 Primary Dataset

Rather than utilizing the default course survey datasets, this specialization project centers on global climate and economic metrics:

* **Dataset:** Our World in Data (OWID) CO2 & Greenhouse Gas Dataset
* **Source:** [Our World in Data GitHub Repository](https://github.com/owid/co2-data)
* **Scope:** 50,000+ country-level annual records (1750–present), filtered to post-1990 sovereign nations.
* **Key Metrics:** GDP per capita, per capita CO2/methane emissions, energy intensity, and renewable energy adoption shares.

---

## 🛠️ Tech Stack & Tooling

* **Language:** Python 3.12+
* **Environment & Package Manager:** `uv`
* **Data Processing & Analytics:** `pandas`, `numpy`, `scipy`, `statsmodels`, `scikit-learn`
* **Visualization:** `seaborn`, `matplotlib`
* **Publishing Framework:** [Quarto](https://quarto.org/) rendered to GitHub Pages
* **IDE & Workflow:** Visual Studio Code, Git, Quarto CLI

---

## 📁 Repository Structure

```bash
wesleyan-data-analysis/
├── _quarto.yml                        # Global Quarto website configuration
├── index.qmd                          # Portfolio home page / post listing
├── favicon.png                        # Website favicon icon
├── README.md                          # Project documentation
├── data/                              # Centralized dataset storage
│   ├── owid-co2-data.csv
│   └── owid-co2-codebook.csv
├── C01-Data-Management-and-Visualization/
│   ├── module1-research-question/     # Research question & hypotheses
│   ├── module2-first-program/         # Data loading & frequency distributions
│   ├── module3-managing-data/         # Data cleaning & feature engineering
│   └── module4-visualizing-data/      # Univariate & bivariate visualizations
├── C02-Data-Analysis-Tools/           # ANOVA, Chi-Square, Pearson Correlation
├── C03-Regression-Modeling-in-Practice/# Multiple Linear & Logistic Regression
├── C04-Machine-Learning-for-Data-Analysis/# Decision Trees, Lasso, k-Means
└── C05-Data-Analysis-and-Interpretation-Capstone/# Final Capstone Project

```
