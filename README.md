# Ichimoku Signal Analysis Across Timeframes and Strategies.

**Goal:** Utilize various Ichimoku trading strategies across assets for performance  
**Result:** Certain strategies successfully outperformed buy-and-hold  
**Tech:** Python, scikit-learn, pandas, matplotlib, Jupyter.

## Quick Links
- ▶️ Notebook: [`notebooks/analysis.ipynb`](notebooks/analysis.ipynb)
- 📄 Report (PDF): [`report/report.pdf`](report/report.pdf)

## TL;DR
- Cleaned missing values, added shifted time horizon for crytpo variant of Ichimoku
- Compared strategies of Kumo twists, kijun bounces, and edge-to-edge trades
- Strategies seem unrelated to "logic" behind matching them to a given asset

## How to Run
```bash
# clone
git clone https://github.com/<davidbjackson>/ichimoku-signal-analysis.git
cd ichimoku-signal-analysis

# create env (conda) OR pip
conda env create -f environment.yml && conda activate ichimoku-signal-analysis
# OR
python -m venv .venv && source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt

# launch notebook
jupyter notebook notebooks/analysis.ipynb
```
# When Running Notebook
Rerunning cells more than one time will brick certain sections; run once in order
