## 📁 Code Directory — QuantPulse

This folder contains **all source code and experimental notebooks** developed for the **QuantPulse: Short-Term Portfolio Optimizer** project.

The codebase is organised to reflect the **end-to-end workflow**, starting from data collection and preprocessing, through short-term price prediction, and finally to portfolio optimisation and evaluation.

**Note:** Util and Data files are not included included here

### 📌 Folder Structure and Purpose

The notebooks in this directory broadly follow the pipeline below:

#### 1️⃣ Data Collection & Updating

* Scripts for downloading and updating **hourly stock and index data** using the Yahoo Finance API
* Ensures consistent timestamps and rolling data availability

#### 2️⃣ Data Analysis & Feature Engineering

* Exploratory Data Analysis (EDA)
* Statistical analysis of returns (normality, stationarity)
* Correlation analysis and risk–return visualisation
* Construction of lag-based and seasonal features used for prediction

#### 3️⃣ Short-Term Price Prediction

* Rolling **XGBoost-based prediction framework**
* One-hour-ahead price forecasting
* Conversion of predicted prices into expected short-term returns
* Prediction files generated separately for each asset

#### 4️⃣ Portfolio Optimisation

This folder includes implementations and experiments related to **multiple portfolio optimisation techniques**.

✔ **Methods included in the final project, report, and presentation:**

* Efficient Frontier (Mean–Variance Optimisation)
* Bayesian Portfolio Optimisation
* Hierarchical Equal Risk Contribution (HERC)

🧪 **Experimental / exploratory methods (not included in final results):**

* Classical Risk Parity
* Exponentially Weighted Covariance-based optimisation
* Bayesian Black–Litterman–style formulations
* Reinforcement Learning–based portfolio optimisation
* Heuristic and rule-based allocation strategies

These experimental notebooks are retained for **completeness, learning reference, and future extension**, but are **not used for reported results**.
