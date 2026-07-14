# CodeAlpha Data Analytics Internship - Project 2: Data Visualization

This repository contains the complete **Data Visualization & Analytics** project developed for the CodeAlpha Data Analytics Internship. 

## 📌 Project Overview
This project presents an in-depth exploratory data analysis and visual storytelling showcase utilizing player performance records leading up to the **FIFA World Cup 2026**. By leveraging Matplotlib and Seaborn, we identify key valuation trends, demographic metrics, and playing style correlations to help sport organizations make data-driven scouting decisions.

---

## 📊 Dataset Description
The dataset contains **54,602 rows** and **75 features**, documenting player profiles, match conditions, and performance metrics:
- **Demographics:** Age, Position, Nationality, Club, Preferred Foot.
- **Financials:** Market Value (EUR).
- **Physical Profiles:** Stamina, Top Speed, Distance Covered, Accelerations.
- **In-Game Actions:** Goals, Assists, Key Passes, Tackles, Clearances, Saves.
- **Advanced Performance Scores:** Overall Rating, Creativity, Clutch Performance, Consistency.

---

## 🛠️ Technologies Used
- **Language:** Python
- **Data Manipulation:** `pandas`, `numpy`
- **Visualization:** `matplotlib`, `seaborn`
- **Environment:** Jupyter Notebook

---

## 🚀 Installation & Usage

1. **Clone this repository:**
   ```bash
   git clone https://github.com/yourusername/CodeAlpha_Data-Visualization.git
   cd CodeAlpha_Data-Visualization
   ```

2. **Install the required libraries:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook:**
   ```bash
   jupyter notebook notebook/Data_Visualization.ipynb
   ```

---

## 📂 Project Structure
```
CodeAlpha_Data-Visualization/
│
├── data/
│   └── dataset.csv              # FIFA World Cup 2026 dataset
│
├── notebook/
│   └── Data_Visualization.ipynb # Main analysis notebook
│
├── images/
│   └── generated_visualizations/# Saved visual assets
│       ├── age_distribution.png
│       ├── correlation_heatmap.png
│       ├── market_value_by_position.png
│       ├── position_distribution.png
│       └── rating_vs_value.png
│
├── requirements.txt             # Project library dependencies
├── README.md                    # Project documentation
└── .gitignore                   # Files to ignore in Git
```

---

## 📈 Visualizations Included

1. **Age Distribution (`images/generated_visualizations/age_distribution.png`):** Identifies peak maturity playing brackets.
2. **Player Positions Count (`images/generated_visualizations/position_distribution.png`):** Shows tactical role representations.
3. **Market Value by Position (`images/generated_visualizations/market_value_by_position.png`):** Investigates pricing differentials across positions.
4. **Player Rating vs. Market Value (`images/generated_visualizations/rating_vs_value.png`):** Displays the exponential pricing curve for elite performers.
5. **Key Metrics Correlation Heatmap (`images/generated_visualizations/correlation_heatmap.png`):** Discovers ties between ratings, goals, assists, and market value.

---

## 💡 Key Insights
- **The Superstar Premium:** Valuations grow exponentially once overall ratings surpass **8.0**. Target players in the **7.5 to 8.0** range for high-ROI signings.
- **Defensive Value Gap:** High-quality defensive traits do not strongly correlate with market value, allowing budget-friendly construction of highly solid defenses.
- **Physical Trait Arbitrage:** Raw fitness parameters (like stamina or speed) do not heavily inflate market prices, offering high-workrate players at discounts.
