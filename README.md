<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=00D9FF&center=true&vCenter=true&width=900&lines=Personal+Finance+Intelligent+System;AI+%26+ML-Powered+Financial+Intelligence;ETL+Pipeline+%7C+Anomaly+Detection+%7C+Forecasting;Python+%7C+Streamlit+%7C+Scikit-learn+%7C+Plotly" alt="Typing SVG" />

<br/>
<br/>

<!-- Badges -->
<a href="#">
  <img src="https://img.shields.io/badge/Python-3.8+-blue.svg?style=flat-square&logo=python&logoColor=white" />
</a>
<a href="#">
  <img src="https://img.shields.io/badge/Streamlit-1.28+-red.svg?style=flat-square&logo=streamlit&logoColor=white" />
</a>
<a href="#">
  <img src="https://img.shields.io/badge/Scikit--learn-1.3+-orange.svg?style=flat-square&logo=scikit-learn&logoColor=white" />
</a>
<a href="#">
  <img src="https://img.shields.io/badge/License-MIT-green.svg?style=flat-square" />
</a>
<a href="#">
  <img src="https://img.shields.io/badge/Status-Active-00D9FF?style=flat-square" />
</a>

<br/>
<br/>

<a href="https://github.com/KaizenVH24/VH-Personal_Finance_Intelligent_System">
  <img src="https://img.shields.io/badge/View%20on-GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

</div>

---

## 📊 Overview

**Personal Finance Intelligent System (PFIS)** is an AI & ML-powered financial intelligence dashboard that transforms raw bank transaction data into structured intelligence, risk insights, predictive forecasts, and executive-ready reports.

> **My Contribution:** Built the **ETL pipeline**, **data validation & cleansing logic**, **anomaly detection engine**, and **interactive Streamlit dashboard** for this project.

---

## 🚀 Key Features

| Feature | Description |
|---------|-------------|
| 📄 **Multi-format Ingestion** | PDF, CSV, Excel support with intelligent parsing |
| 🏷️ **Merchant Normalisation** | Cleans messy UPI strings and maps 50+ Indian merchants |
| 🔍 **Anomaly Detection** | Isolation Forest ML model for transaction outlier detection |
| 📊 **Financial Health Score** | Composite 0-100 score with configurable weights |
| 🔄 **Recurring Detection** | Identifies subscriptions, EMIs, and regular transfers |
| 📈 **Predictive Analytics** | Expense and savings forecasting with 95% confidence intervals |
| 💰 **Budget Intelligence** | Per-category budget tracking with alerts |
| 🎯 **Savings Goal Tracker** | Goal-based savings planner with progress visualization |
| 💡 **Automated Insights** | Rule-based, data-driven financial insights |
| 📑 **Executive PDF Report** | Professional report generation with ReportLab |

---

## 📊 Dashboard Pages

| Page | Functionality |
|------|---------------|
| **Overview** | Financial summary, health score gauge, key metrics |
| **Transactions** | Filterable transaction table with anomaly flags |
| **Categories** | Spending breakdown with budget tracking |
| **Forecast** | Expense and savings predictions with confidence intervals |
| **Goals** | Savings goal tracker with projected attainment |

---

## 🏗️ System Architecture

```text
┌─────────────────────────────────────────────────┐
│                  UI Layer                        │
│          Streamlit — app.py                      │
│   Overview · Transactions · Categories ·         │
│   Forecast · Goals                               │
└────────────────────┬────────────────────────────┘
                     │
┌────────────────────▼────────────────────────────┐
│             Business Logic Layer                 │
│                  utils/                          │
│                                                  │
│  data_loader      categorizer    aggregator      │
│  anomaly_detector health_score   recurring       │
│  forecasting      savings_pred   insights        │
│  report_generator                                │
└────────────────────┬────────────────────────────┘
                     │
┌────────────────────▼────────────────────────────┐
│         Statistical & ML Layer                   │
│   Isolation Forest · Linear Regression           │
│   Statistical Thresholding · Rule Heuristics     │
└────────────────────┬────────────────────────────┘
                     │
┌────────────────────▼────────────────────────────┐
│          Configuration Layer                     │
│                config.py                         │
│  All thresholds, weights, budgets, merchant map  │
└────────────────────┬────────────────────────────┘
                     │
┌────────────────────▼────────────────────────────┐
│            Data Input Layer                      │
│       PDF · CSV · Excel (.xlsx / .xls)           │
└─────────────────────────────────────────────────┘
🛠️ Tech Stack
Layer	Technology	Purpose
UI	Streamlit	Interactive dashboard and navigation
Visualization	Plotly	Charts, gauges, and time series
Data	Pandas, NumPy	Manipulation and numerical computation
ML	Scikit-learn	Isolation Forest, Linear Regression
PDF Ingestion	pdfplumber	Bank statement parsing
PDF Export	ReportLab	Executive report generation
Spreadsheet	openpyxl	Excel read/write
📦 Installation
Prerequisites
Python 3.8 or higher

pip package manager

Setup
bash
# Clone the repository
git clone https://github.com/KaizenVH24/VH-Personal_Finance_Intelligent_System.git
cd VH-Personal_Finance_Intelligent_System

# Create and activate virtual environment
python -m venv venv

# Windows
venv\Scripts\activate

# macOS / Linux
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run the application
streamlit run app.py
The application will open in your default browser at http://localhost:8501.

📁 Project Structure
text
pfis/
│
├── app.py                          # UI layer — Streamlit pages and layout
├── config.py                       # Central config — all tuneable parameters
├── requirements.txt
├── README.md
├── .gitignore
│
├── .streamlit/
│   └── config.toml                 # Dark theme enforcement
│
├── utils/
│   ├── __init__.py
│   ├── data_loader.py              # Multi-format ingestion and cleaning
│   ├── categorizer.py              # Merchant normalisation and categorisation
│   ├── anomaly_detector.py         # Statistical + Isolation Forest detection
│   ├── aggregator.py               # Time features and aggregation helpers
│   ├── health_score.py             # Composite 0-100 scoring engine
│   ├── forecasting.py              # Linear regression expense forecasting
│   ├── savings_prediction.py       # Linear regression savings forecasting
│   ├── recurring.py                # Subscription and EMI detection
│   ├── insights.py                 # Rule-based insight generation
│   └── report_generator.py         # ReportLab PDF export
│
└── assets/
    ├── sample_transactions.csv     # 4-month CSV sample
    ├── sample_transactions.xlsx    # Same data as Excel workbook
    └── sample_transactions.pdf     # Same data as bank statement PDF
📊 Sample Data
Three sample files are included in assets/ covering November 2025 through February 2026 (771 transactions):

File	Format	Use
sample_transactions.csv	4 columns: date, description, amount, balance	Direct upload to PFIS
sample_transactions.xlsx	Transactions + Monthly Summary sheet	Upload or open in Excel
sample_transactions.pdf	Bank statement layout	Tests PDF parser
Transaction types covered: Daily interest credits, monies transfers, Zerodha trades, loan EMIs, food delivery, e-commerce, transport, subscriptions, utilities, bill payments, salary credits, peer UPI transfers, and cashback credits.

🧠 Core Capabilities
1 — Transaction Intelligence Engine
Automatic column detection with descriptive error messages

Currency symbol and comma stripping from amount fields

Parenthesis-format negative number support

Deduplication on date + description + amount

Merchant normalisation from messy UPI strings

Transaction type assignment based on amount sign

2 — Anomaly and Risk Detection
Statistical thresholding: threshold = mean(expenses) + k × std(expenses)

Isolation Forest anomaly detection on expense amounts

Configurable contamination rate and multiplier

3 — Financial Health Scoring (0-100)
text
Final Score = BASE_HEALTH_SCORE (60)
            + savings_contribution (up to +40)
            - large_transaction_penalty (up to -20)
            - anomaly_penalty (up to -10)
            - concentration_penalty (up to -10)
            → clamped to [0, 100]
Score	Status
80–100	Excellent Financial Health
60–79	Financially Stable
40–59	Some Financial Risk
0–39	High Financial Risk
4 — Recurring Transaction Detection
Same merchant across multiple months

Amounts match within ±5% tolerance

Output includes merchant, category, average amount, frequency, active months

Used for total monthly committed spend calculation

5 — Predictive Analytics
Linear regression on monthly aggregated data

3-month forecast with 95% confidence intervals

Available for total expenses or individual categories

Savings forecast with green/red bar visualization

6 — Budget Intelligence
Global monthly budget tracking with over/under delta

Per-category budget tracking with usage percentage

Visual status indicators (🟢/🟡/🔴)

7 — Savings Goal Tracker
Required monthly savings calculation

Progress bar showing projected attainment

On-track/behind-pace status with exact gap

3-month savings forecast overlay

8 — Automated Insight Engine
Rule-based, deterministic, data-driven insights

Savings rate classification

Top spending category identification

Spending concentration warnings

Anomaly and large transaction reporting

Investment presence analysis

9 — Executive PDF Report
ReportLab-generated A4 PDF

Financial summary table

Health score breakdown

Expenses by category

Automated insights as bullet points

⚙️ Configuration
All system parameters are centralized in config.py:

python
# Health Score Configuration
BASE_HEALTH_SCORE = 60
MAX_SAVINGS_CONTRIBUTION = 40
MAX_LARGE_TXN_PENALTY = 20
MAX_ANOMALY_PENALTY = 10
MAX_CONCENTRATION_PENALTY = 10

# Anomaly Detection
BIG_TRANSACTION_MULTIPLIER = 2.0
ANOMALY_CONTAMINATION = 0.1

# Recurring Detection
RECURRING_MIN_OCCURRENCES = 2
RECURRING_AMOUNT_TOLERANCE = 0.05

# Forecasting
FORECAST_PERIODS = 3

# Budgets
DEFAULT_CATEGORY_BUDGETS = {
    "Food": 5000,
    "Transport": 3000,
    "Shopping": 4000,
    # ... more categories
}
🎯 Engineering Principles
Principle	Implementation
Modular Architecture	Each util is standalone, independently importable
Config-Driven	No magic numbers anywhere in code
Defensive Ingestion	Every parse step uses coerce, not raise
Correct Sign Handling	Amount sign determines transaction direction
Separation of Concerns	app.py contains zero calculations
Explainable ML	Isolation Forest for detection; scoring uses interpretable ratios
Deterministic Outputs	Same input always produces same results
Dark-First Design	Framework-level dark theme enforcement
⚠️ Known Limitations
PDF parser is calibrated for a specific bank statement layout (Indian savings accounts)

Forecasting uses linear regression — with limited data, confidence intervals are wide

Recurring detection requires at least 2 months of data

PDF report does not embed charts (roadmap item)

No persistent storage — all analysis is session-scoped

🗺️ Roadmap
□ Prophet-based seasonal forecasting
□ Charts embedded in PDF report via Plotly image export
□ Real-time bank API ingestion
□ PostgreSQL backend for persistent storage
□ User authentication and session management
□ KMeans behavioural clustering for spending archetypes
□ Multi-user analytics with isolated data namespaces
□ REST API backend separated from Streamlit UI
□ Parser extension for additional bank statement formats
👥 Authors
Author	Role
Vinay Hulsurkar	Project Lead
Gayatri Ghorpade	ML & Forecasting
Tejas Chavan	ETL Pipeline, Data Validation, Dashboard	⬅️ Me
Jitendra Chaudhary	PDF Report & Testing
🙏 My Contribution to PFIS
Component	What I Built
ETL Pipeline	Multi-format ingestion (PDF, CSV, Excel) with intelligent parsing
Data Validation	Column detection, deduplication, currency stripping, sign handling
Merchant Normalisation	Cleaned UPI strings, mapped 50+ Indian merchants
Anomaly Detection	Isolation Forest + statistical thresholding for outlier detection
Streamlit Dashboard	Interactive UI with 5 pages: Overview, Transactions, Categories, Forecast, Goals
Data Aggregator	Time-based aggregation and feature engineering
📄 License
This project is licensed under the MIT License — see the LICENSE file for details.
