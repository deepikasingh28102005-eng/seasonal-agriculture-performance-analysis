# Seasonal Agriculture Performance Analysis

Data analytics project analyzing how agricultural performance — yield, profitability, resource usage and risk — varies across the Kharif, Rabi and Zaid cropping seasons in India.

**VOIS AICTE Major Project — Batch1 2026-2027**
Deepika Singh | B.Tech CSE, Jaypee University of Information Technology (JUIT), Solan | Enrollment No. 241030016

## Problem Statement

Agricultural activities are shaped by seasonal shifts in rainfall, temperature, humidity and resource availability, but raw farm-level data alone doesn't reveal how yield, cost and profitability actually change from one season to the next. This project analyzes a multi-state seasonal farming dataset to uncover meaningful seasonal patterns, trends and relationships, and to turn them into evidence-based recommendations.

## Dataset

- **4,000 farm records** across 3 seasons (Kharif, Rabi, Zaid), 8 states, 10 districts and 8 crops
- 28 features covering climate (rainfall, temperature, humidity), soil (pH, moisture, NPK), inputs (fertilizer, pesticide, irrigation method), and outcomes (yield, cost, revenue, profit, disease/pest risk)
- `seasonal_agriculture_performance_dataset.csv` — raw dataset
- `cleaned_dataset.csv` — cleaned version with derived `Yield_clean` (outlier-capped) and `Profit_margin_pct` columns

## Tech Stack

- **Python 3** — Pandas, NumPy for data cleaning and analysis
- **Matplotlib, Seaborn** — statistical visualization
- **Jupyter Notebook** — documented, reproducible analysis

## Repository Structure

```
├── Seasonal_Agriculture_Performance_Analysis.ipynb   # Full analysis notebook
├── seasonal_agriculture_performance_dataset.csv       # Raw dataset
├── cleaned_dataset.csv                                # Cleaned dataset
├── VOIS_Major_Project_Seasonal_Agriculture_Performance_Analysis.pptx  # Presentation
└── README.md
```

## Key Insights

- **Kharif is the strongest season overall** — highest rainfall (~852 mm), highest average yield (~2.29 t/ha) and highest average profit (~₹1.79 lakh)
- **Zaid is the weakest and riskiest season** — lowest yield (~1.71 t/ha), negative average profit (~₹−25K), and the widest spread of losses
- **Water efficiency, not fertilizer or water volume, is the strongest driver of yield** (r ≈ 0.69) — irrigation quality matters more than input quantity
- **Profit margins are negative on average in every season**, indicating production costs frequently exceed revenue across a large share of farms
- **Disease/pest risk tracks rainfall and humidity**, peaking in the wet Kharif season
- Seasonal advantage varies by crop and by state, so recommendations should be localized rather than one-size-fits-all

## How to Run

1. Clone the repository
   ```
   git clone https://github.com/deepikasingh28102005-eng/seasonal-agriculture-performance-analysis.git
   ```
2. Install dependencies
   ```
   pip install pandas numpy matplotlib seaborn jupyter
   ```
3. Launch the notebook
   ```
   jupyter notebook Seasonal_Agriculture_Performance_Analysis.ipynb
   ```

## Author

**Deepika Singh**
B.Tech CSE, JUIT Solan
GitHub: [@deepikasingh28102005-eng](https://github.com/deepikasingh28102005-eng)
