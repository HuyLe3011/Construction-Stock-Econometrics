# 🏗️ Econometric Analysis of Stock Prices in the Construction Industry

## 📌 Project Overview
This repository contains the dataset and analytical code for the research paper: *"Factors Affecting Construction Industry Stock Prices on the Ho Chi Minh City Stock Exchange"*. 

🏆 **Awarded Third Prize at the Digital Transformation Scientific Conference 2025.**

The project investigates the macroeconomic and internal fundamental factors driving asset pricing for 33 construction enterprises listed on the HOSE using a 5-year balanced panel data set. Advanced econometric modeling was applied to rigorously test and identify statistically significant predictors of stock returns.

## 🗂️ Project Structure
* `data/`: Contains the balanced panel dataset (`panel_data.csv`) and the list of statistical commands (`stata_commands.csv`) covering variables such as Firm Size, ROA, ROE, Leverage (DE), and Industry P/E.
* `notebooks/`: 
  * `01_econometric_analysis_and_testing.ipynb`: Jupyter notebook demonstrating Exploratory Data Analysis (EDA), correlation matrix generation, and econometric modeling.

## 🚀 Key Technologies & Methodologies
* **Programming & Tools:** Python (Pandas, NumPy, Seaborn) and Stata.
* **Econometric Models:** Pooled Ordinary Least Squares (OLS), Fixed Effects Model (FEM), Random Effects Model (REM).
* **Robustness & Statistical Testing:** Feasible Generalized Least Squares (FGLS), Generalized Method of Moments (GMM), Hausman Test, Wooldridge Test (addressing heteroskedasticity, autocorrelation, and endogeneity).

## ⚙️ How to Run
1. Clone this repository:
```bash
git clone [https://github.com/HuyLe3011/Construction-Stock-Econometrics.git](https://github.com/HuyLe3011/Construction-Stock-Econometrics.git)
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

3. Open the `notebooks/` directory to review the analysis pipeline.

## ⚠️ Known Limitations & Future Work
Although the econometric models successfully identified key pricing drivers while passing rigorous statistical tests, the research acknowledges the following boundaries:

* **Sample Size Constraints:** The empirical analysis is localized to 33 construction enterprises over a 5-year period. Future research will expand the dataset across multiple sectors and extended timeframes (spanning multiple economic cycles) to verify the cross-sectional robustness of the identified factors.
* **Data Frequency Limitations:** Panel data models relying on low-frequency (annual/quarterly) fundamental metrics cannot capture short-term market microstructure dynamics or sudden liquidity shocks.
* **Non-Linear Relationships:** OLS and Panel models assume linear relationships. Future studies will explore machine learning techniques to capture non-linear and interactive effects between macroeconomic variables and stock prices.
