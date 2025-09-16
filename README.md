# Predicting Players' Income on Madden NFL 24

**Author:** Chuhan Tang  

---

## Project Overview
This capstone project analyzes player data from Madden NFL 24 to predict football players' **total income**, defined as the sum of `total_salary` and `signing_bonus`. Although the data comes from a simulation game, it is partially based on real-life player characteristics and reflects general patterns observed in professional football. The goal is to identify key correlates of player income and provide insights for a general audience.

---

## Dataset
- **Source:** [Kaggle – Madden 24 Player Ratings](https://www.kaggle.com/datasets/dtrade84/madden-24-player-ratings)  
- **File:** `maddennfl24fullplayerratings.csv`  
- **Observations:** 2368 players  
- **Features:** 67 columns describing various characteristics of each player  
- **Target Variable:** `total_income` = `total_salary` + `signing_bonus`  

---

## File Structure
- `main.ipynb` : Jupyter notebook with data cleaning, exploration, analysis, and modeling  
- `README.md` : Project description and instructions  

---

## Requirements
- **Python** >= 3.10  
- **Packages:** pandas, numpy, matplotlib, seaborn, scikit-learn, jupyter  

Install packages via pip:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
