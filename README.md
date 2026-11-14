# 👋 Hi, I'm Shiyan Jiang

### 📊 Python · SQL · R · Data Analysis
*Building reliable data workflows with Python, SQL and R. Combining a background in live-service game operations with a master's in computational methods and hands-on experience in data pipelines, automated testing and analysis.*

---

## 🚀 About Me
- 🎓 **Master in Communication and Information Studies** | University of Groningen, Netherlands
- 🎮 **Background**: 4+ years in the game industry. Partnered with live-ops to turn retention, DAU, churn and monetization reports into design decisions, and ran server-segmented A/B tests on bundles and events.
- 🎯 **Focus**:  **Python**, **SQL**, **R** and **data visualization**. 

---

## 🛠️ Tech Stack
- **Data Analysis**: Python (Pandas, NumPy), SQL, R, ETL
- **Visualization**: Matplotlib, Seaborn, Plotly, Streamlit
- **NLP & Research**: NLTK, Sentiment Analysis, Topic Modeling, Quantitative Content Analysis
- **Tools**: Jupyter Notebooks, Git, pytest, VS Code, Figma

---

## 📂 Key Data Projects

### ⚽ [Chemistry XI: Match Event Analysis Pipeline](https://github.com/FlyingCitroen/chemistry-xi)
**Microsoft × Premier League Hackathon | Python, Streamlit, pytest**
- **Objective**: Replay time-ordered match events and flag player pairs whose pass success consistently beats a team baseline.
- **Approach**: Python pipeline with a deterministic rule engine, Beta smoothing over a rolling 10-pass window, five link states, JSON overlay output and a Streamlit app. 33 pytest tests. LLM narration via the GitHub Models API, with a verifier that rejects any number or player name the engine did not produce.
- **Note**: Uses simulated, partly scripted data. It validates the pipeline only and makes no claim about real football.

### 🎓 [The Evolution of Gaming Aesthetics and Community in the 1990s](https://github.com/FlyingCitroen/EGM_Analysis)
**Graduate Thesis Project | Electronic Gaming Monthly, 1990–1999**
- **Challenge**: Collected all editorials and game reviews from 120 magazine issues through web scraping and manual extraction.
- **Approach**: Python topic modeling and sentiment analysis on the editorials, with heat maps and word clouds; review scores analyzed by year and platform.
- **Outcome**: Traced how editorial themes, sentiment and review scores shifted over the decade, including around the 2D-to-3D console transition.

### 🛒 [Olist E-Commerce Sales Analysis](https://github.com/FlyingCitroen/olist-sales-analysis)
**Python, pandas, SQL (SQLite), matplotlib**
- **Objective**: Answer four business questions on a Brazilian marketplace dataset (about 99,000 orders): demand by state, cancellation rate, monthly sales and top product categories.
- **Approach**: Merged 7 relational tables into one order-item level table with row-count checks and `validate=` at every join. Aggregated payments and reviews to one row per order to avoid double-counted money. Repeated all four analyses in SQL and checked the results against pandas.
- **Outcome**: Found that 467 canceled or unavailable orders still had item rows and excluded them from sales (0.72% of item value). Demand is concentrated in three southeastern states (66.6% of orders); 2018 sales growth came almost entirely from order volume, not order value.

### 🧹 [Online Retail: Data Cleaning Case Study](https://github.com/FlyingCitroen/online-retail)
**Python, pandas**
- **Objective**: Show how data-cleaning decisions change the business conclusions drawn from a UK online retailer's transaction data (541,909 lines, Dec 2010 – Dec 2011).
- **Approach**: Removed 5,268 duplicate rows, classified rows that are not sales (cancellations, likely stock write-offs, bad-debt entries, zero-price lines) and reconciled row counts at every step. Defined two sales measures, gross and net of cancellations, and compared them.
- **Outcome**: The cancellation rate falls from ~8.4% to ~4.8% of gross sales once ten non-typical lines (six "AMAZON FEE" entries, two very large orders, one manual adjustment) are excluded. Best-seller rankings by units and by revenue also change once cancelled orders are deducted. The UK accounts for ~84.6% of gross sales.

---

## 📫 Connect with me:
- 📧 Email: shiyan.jiang@outlook.com
