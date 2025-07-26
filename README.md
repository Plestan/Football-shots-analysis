# Football Shots Dataset Analysis

This project presents an analysis of a comprehensive football (soccer) shots dataset from the English Premier League. The aim is to explore shot performance, identify players who overperform their expected goals (xG), and analyze the best areas of the pitch for scoring opportunities.

---

## Dataset Description

The dataset is sourced from [Kaggle: Shots Dataset for Football/Soccer](https://www.kaggle.com/datasets/mat126/shots-dataset-for-footballsoccer?resource=download).

It contains **442,592** entries with **23 columns**, capturing detailed information about shots taken during Premier League matches. The data includes:

- Match and player identifiers
- Shot location coordinates on the pitch
- Expected Goals (xG) values for each shot
- Shot outcomes (goal or miss)
- Various contextual features (match minute, body part used, assist type, etc.)

This rich dataset enables in-depth analysis of shot-taking behavior and player performance in different pitch zones.

---

## Analysis Workflow

### 1. Import and Preliminary Data Exploration

- Load the dataset and inspect its structure.
- Clean and preprocess data as needed (handle missing values, data types).
- Conduct initial exploratory data analysis (EDA) to understand distributions of key variables like shots, goals, and xG.

### 2. Overperforming Players: Goals vs Expected Goals (xG)

- Calculate total goals and total xG per player.
- Identify players who have scored significantly more goals than their expected goals (overperformers).
- Visualize the comparison to highlight exceptional finishing ability or clinical performance.

### 3. Analysis of the Best Areas of the Field

- Map shot locations onto the pitch.
- Analyze shot success rates and average xG by different zones on the field.

---

## How to Use This Repository

- Clone the repo and download the dataset from Kaggle.
- Run the provided Jupyter notebooks or scripts step-by-step following the analysis workflow.
- Visualizations and summary tables will guide your understanding of player performance and spatial shot analysis.

---

## Conclusion

This analysis provides actionable insights into which players outperform their expected scoring rates and where on the pitch teams generate the most valuable chances. It serves as a useful resource for football analysts, coaches, and fans interested in data-driven performance evaluation.

---

*Feel free to contribute or raise issues for further improvements.*
