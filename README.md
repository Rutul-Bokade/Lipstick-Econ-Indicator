# Lipstick Index 2.0
Small demo: Google Trends, sample social posts, and sample stock + macro CSVs.
Run `run_pipeline.py` to see example outputs in outputs/figures.
# 💄 Lipstick Index 2.0

This project reimagines the classic **Lipstick Index** (cosmetic sales as a recession signal) using **Google Trends, social media sentiment, beauty stock prices, and macroeconomic data**.

## 📂 Repository Structure
- `data/` → Sample CSVs for trends, social, stocks, macro
- `src/` → Modular Python scripts (data loading, sentiment, visualization, modeling)
- `notebooks/` → Jupyter notebook for exploration
- `outputs/` → Figures + reports
- `run_pipeline.py` → Main script to run the analysis

## ⚡ Workflow
1. Load data (`data_loader.py`)
2. Run sentiment analysis on social posts (`sentiment_analysis.py`)
3. Generate visualizations (`visualization.py`)
4. Build regression models linking sentiment to stock prices (`modeling.py`)

## 🚀 How to Run
```bash
pip install -r requirements.txt
python run_pipeline.py
Author: Rutul Bokade
