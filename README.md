<div align="center">

<!-- Animated Header -->
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=30&pause=1000&color=00D9FF&center=true&vCenter=true&width=1000&lines=Personal+Finance+Intelligent+System;AI+%26+ML-Powered+Financial+Intelligence;ETL+Pipeline+%7C+Anomaly+Detection+%7C+Forecasting;Python+%7C+Streamlit+%7C+Scikit-learn+%7C+Plotly;Built+by+Tejas+Chavan+%26+Team" alt="Typing SVG" />

<br/>
<br/>

<!-- Project Badges -->
<a href="#">
  <img src="https://img.shields.io/badge/Python-3.8%2B-3776AB?style=for-the-badge&logo=python&logoColor=white" />
</a>
<a href="#">
  <img src="https://img.shields.io/badge/Streamlit-1.28%2B-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" />
</a>
<a href="#">
  <img src="https://img.shields.io/badge/Scikit--learn-1.3%2B-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
</a>
<a href="#">
  <img src="https://img.shields.io/badge/Plotly-5.0%2B-3F4F75?style=for-the-badge&logo=plotly&logoColor=white" />
</a>
<a href="#">
  <img src="https://img.shields.io/badge/License-MIT-00D9FF?style=for-the-badge&logo=opensourceinitiative&logoColor=white" />
</a>

<br/>

<a href="#">
  <img src="https://img.shields.io/badge/Status-Active-00D9FF?style=for-the-badge" />
</a>
<a href="#">
  <img src="https://img.shields.io/badge/Version-2.0-00D9FF?style=for-the-badge" />
</a>

<br/>
<br/>

<!-- Repository Link -->
<a href="https://github.com/KaizenVH24/VH-Personal_Finance_Intelligent_System">
  <img src="https://img.shields.io/badge/📂%20View%20on%20GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>
<a href="#">
  <img src="https://img.shields.io/badge/🚀%20Live%20Demo-00D9FF?style=for-the-badge&logo=streamlit&logoColor=white" />
</a>

</div>

---

## 📊 Overview

**Personal Finance Intelligent System (PFIS)** is an AI & ML-powered financial intelligence dashboard that transforms raw bank transaction data into structured intelligence, risk insights, predictive forecasts, and executive-ready reports.

<p align="center">
  <img src="https://img.shields.io/badge/📈%20Data%20Ingestion-00D9FF?style=flat-square" />
  <img src="https://img.shields.io/badge/🤖%20Anomaly%20Detection-00D9FF?style=flat-square" />
  <img src="https://img.shields.io/badge/📊%20Forecasting-00D9FF?style=flat-square" />
  <img src="https://img.shields.io/badge/📑%20PDF%20Reports-00D9FF?style=flat-square" />
  <img src="https://img.shields.io/badge/💡%20Automated%20Insights-00D9FF?style=flat-square" />
</p>

---

## 👤 My Contribution to PFIS

| Component | What I Built | Skills Demonstrated |
|-----------|--------------|---------------------|
| 🔄 **ETL Pipeline** | Multi-format ingestion (PDF, CSV, Excel) with intelligent parsing | Data Engineering, Python |
| ✅ **Data Validation** | Column detection, deduplication, currency stripping, sign handling | Data Quality, Data Cleaning |
| 🏷️ **Merchant Normalisation** | Cleaned UPI strings, mapped 50+ Indian merchants | Data Transformation, Regex |
| 🔍 **Anomaly Detection** | Isolation Forest + statistical thresholding for outlier detection | Machine Learning, Scikit-learn |
| 📊 **Streamlit Dashboard** | Interactive UI with 5 pages: Overview, Transactions, Categories, Forecast, Goals | UI Development, Streamlit |
| 📈 **Data Aggregator** | Time-based aggregation and feature engineering | Data Analysis, Pandas |

---

## 🚀 Key Features

| # | Feature | Description |
|---|---------|-------------|
| 1 | 📄 **Multi-format Ingestion** | PDF, CSV, Excel support with intelligent parsing |
| 2 | 🏷️ **Merchant Normalisation** | Cleans messy UPI strings and maps 50+ Indian merchants |
| 3 | 🔍 **Anomaly Detection** | Isolation Forest ML model for transaction outlier detection |
| 4 | 📊 **Financial Health Score** | Composite 0-100 score with configurable weights |
| 5 | 🔄 **Recurring Detection** | Identifies subscriptions, EMIs, and regular transfers |
| 6 | 📈 **Predictive Analytics** | Expense and savings forecasting with 95% confidence intervals |
| 7 | 💰 **Budget Intelligence** | Per-category budget tracking with alerts |
| 8 | 🎯 **Savings Goal Tracker** | Goal-based savings planner with progress visualization |
| 9 | 💡 **Automated Insights** | Rule-based, data-driven financial insights |
| 10 | 📑 **Executive PDF Report** | Professional report generation with ReportLab |

---

## 📊 Dashboard Pages

<table>
<tr>
<th width="20%">Page</th>
<th width="40%">Functionality</th>
<th width="40%">Key Metrics</th>
</tr>
<tr>
<td>📊 <b>Overview</b></td>
<td>Financial summary, health score gauge, key metrics</td>
<td>Balance, Income, Expenses, Savings Rate, Health Score</td>
</tr>
<tr>
<td>📋 <b>Transactions</b></td>
<td>Filterable transaction table with anomaly flags</td>
<td>Date, Description, Amount, Category, Anomaly Flag</td>
</tr>
<tr>
<td>📁 <b>Categories</b></td>
<td>Spending breakdown with budget tracking</td>
<td>Category-wise Spend, Budget Utilization, Trends</td>
</tr>
<tr>
<td>📈 <b>Forecast</b></td>
<td>Expense and savings predictions with confidence intervals</td>
<td>3-Month Forecast, Confidence Intervals</td>
</tr>
<tr>
<td>🎯 <b>Goals</b></td>
<td>Savings goal tracker with projected attainment</td>
<td>Goal Progress, Monthly Required Savings, Timeline</td>
</tr>
</table>

---

## 🏗️ System Architecture
┌─────────────────────────────────────────────────────────────────────────────────────┐
│                                   UI LAYER                                          │
│                              Streamlit — app.py                                    │
│                                                                                     │
│        ┌──────────────┐  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐      │
│        │   Overview   │  │ Transactions │  │  Categories  │  │   Forecast   │      │
│        └──────────────┘  └──────────────┘  └──────────────┘  └──────────────┘      │
│        ┌──────────────┐                                                             │
│        │    Goals     │                                                             │
│        └──────────────┘                                                             │
└────────────────────────────────────────┬────────────────────────────────────────────┘
                                         │
                                         ▼
┌─────────────────────────────────────────────────────────────────────────────────────┐
│                               BUSINESS LOGIC LAYER                                  │
│                                      utils/                                         │
│                                                                                     │
│  ┌─────────────────┐  ┌─────────────────┐  ┌─────────────────┐                     │
│  │   data_loader   │  │   categorizer   │  │   aggregator    │                     │
│  └─────────────────┘  └─────────────────┘  └─────────────────┘                     │
│                                                                                     │
│  ┌─────────────────┐  ┌─────────────────┐  ┌─────────────────┐                     │
│  │ anomaly_detector│  │   health_score  │  │    recurring    │                     │
│  └─────────────────┘  └─────────────────┘  └─────────────────┘                     │
│                                                                                     │
│  ┌─────────────────┐  ┌─────────────────┐  ┌─────────────────┐                     │
│  │   forecasting   │  │  savings_pred   │  │    insights     │                     │
│  └─────────────────┘  └─────────────────┘  └─────────────────┘                     │
│                                                                                     │
│  ┌─────────────────────────────────────────────────────────────────────┐            │
│  │                        report_generator                             │            │
│  └─────────────────────────────────────────────────────────────────────┘            │
└────────────────────────────────────────┬────────────────────────────────────────────┘
                                         │
                                         ▼
┌─────────────────────────────────────────────────────────────────────────────────────┐
│                           STATISTICAL & ML LAYER                                    │
│                                                                                     │
│                                                                                     │
│        ┌─────────────────────────┐          ┌─────────────────────────┐            │
│        │    Isolation Forest     │          │   Linear Regression     │            │
│        │     (Anomaly Detection) │          │    (Forecasting)        │            │
│        └─────────────────────────┘          └─────────────────────────┘            │
│                                                                                     │
│        ┌─────────────────────────┐          ┌─────────────────────────┐            │
│        │ Statistical Thresholding│          │    Rule Heuristics      │            │
│        │  (Outlier Identification)│         │  (Recurring Detection)  │            │
│        └─────────────────────────┘          └─────────────────────────┘            │
│                                                                                     │
└────────────────────────────────────────┬────────────────────────────────────────────┘
                                         │
                                         ▼
┌─────────────────────────────────────────────────────────────────────────────────────┐
│                               CONFIGURATION LAYER                                   │
│                                      config.py                                      │
│                                                                                     │
│                                                                                     │
│        ┌─────────────────────────────────────────────────────────────────┐          │
│        │                                                                 │          │
│        │  • Health Score Weights    • Anomaly Thresholds                │          │
│        │  • Budget Allocations      • Merchant Mapping Dictionary       │          │
│        │  • Category Mapping        • Recurring Detection Rules         │          │
│        │  • Forecasting Periods     • Savings Goal Parameters           │          │
│        │                                                                 │          │
│        └─────────────────────────────────────────────────────────────────┘          │
│                                                                                     │
└────────────────────────────────────────┬────────────────────────────────────────────┘
                                         │
                                         ▼
┌─────────────────────────────────────────────────────────────────────────────────────┐
│                                DATA INPUT LAYER                                     │
│                                                                                     │
│                                                                                     │
│          ┌─────────────┐    ┌─────────────┐    ┌─────────────────────┐             │
│          │    PDF      │    │    CSV      │    │  Excel (.xlsx/.xls) │             │
│          │  (pdfplumber)│   │  (pandas)   │    │    (openpyxl)      │             │
│          └─────────────┘    └─────────────┘    └─────────────────────┘             │
│                                                                                     │
└─────────────────────────────────────────────────────────────────────────────────────┘
This layered separation ensures the UI layer never contains business logic, the ML layer never touches the config, and every module can be swapped or extended independently.

    A[Data Input Layer<br/>PDF · CSV · Excel] --> B[Configuration Layer<br/>config.py]
    B --> C[Statistical & ML Layer<br/>Isolation Forest · Linear Regression]
    C --> D[Business Logic Layer<br/>utils/]
    D --> E[UI Layer<br/>Streamlit — app.py]
    
    D --> D1[data_loader]
    D --> D2[categorizer]
    D --> D3[aggregator]
    D --> D4[anomaly_detector]
    D --> D5[health_score]
    D --> D6[recurring]
    D --> D7[forecasting]
    D --> D8[savings_pred]
    D --> D9[insights]
    D --> D10[report_generator]
    
    E --> E1[Overview]
    E --> E2[Transactions]
    E --> E3[Categories]
    E --> E4[Forecast]
    E --> E5[Goals]
🛠️ Tech Stack
<table> <tr> <th>Layer</th> <th>Technology</th> <th>Purpose</th> </tr> <tr> <td>🎨 <b>UI</b></td> <td>Streamlit</td> <td>Interactive dashboard and navigation</td> </tr> <tr> <td>📊 <b>Visualization</b></td> <td>Plotly</td> <td>Charts, gauges, and time series</td> </tr> <tr> <td>📦 <b>Data</b></td> <td>Pandas, NumPy</td> <td>Manipulation and numerical computation</td> </tr> <tr> <td>🧠 <b>ML</b></td> <td>Scikit-learn</td> <td>Isolation Forest, Linear Regression</td> </tr> <tr> <td>📄 <b>PDF Ingestion</b></td> <td>pdfplumber</td> <td>Bank statement parsing</td> </tr> <tr> <td>📑 <b>PDF Export</b></td> <td>ReportLab</td> <td>Executive report generation</td> </tr> <tr> <td>📊 <b>Spreadsheet</b></td> <td>openpyxl</td> <td>Excel read/write</td> </tr> </table>
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
🧠 Core Capabilities
<details> <summary><b>1 — Transaction Intelligence Engine</b></summary>
Automatic column detection with descriptive error messages

Currency symbol and comma stripping from amount fields

Parenthesis-format negative number support

Deduplication on date + description + amount

Merchant normalisation from messy UPI strings

Transaction type assignment based on amount sign

</details><details> <summary><b>2 — Anomaly and Risk Detection</b></summary>
Statistical thresholding: threshold = mean(expenses) + k × std(expenses)

Isolation Forest anomaly detection on expense amounts

Configurable contamination rate and multiplier

</details><details> <summary><b>3 — Financial Health Scoring (0-100)</b></summary>
text
Final Score = BASE_HEALTH_SCORE (60)
            + savings_contribution (up to +40)
            - large_transaction_penalty (up to -20)
            - anomaly_penalty (up to -10)
            - concentration_penalty (up to -10)
            → clamped to [0, 100]
Score	Status
80–100	✅ Excellent Financial Health
60–79	🟢 Financially Stable
40–59	🟡 Some Financial Risk
0–39	🔴 High Financial Risk
</details><details> <summary><b>4 — Recurring Transaction Detection</b></summary>
Same merchant across multiple months

Amounts match within ±5% tolerance

Output includes merchant, category, average amount, frequency, active months

Used for total monthly committed spend calculation

</details><details> <summary><b>5 — Predictive Analytics</b></summary>
Linear regression on monthly aggregated data

3-month forecast with 95% confidence intervals

Available for total expenses or individual categories

Savings forecast with green/red bar visualization

</details>
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
    "Entertainment": 2000,
    "Utilities": 3000,
    # ... more categories
}
🎯 Engineering Principles
<table> <tr> <th>Principle</th> <th>Implementation</th> </tr> <tr> <td>📦 <b>Modular Architecture</b></td> <td>Each util is standalone, independently importable</td> </tr> <tr> <td>⚙️ <b>Config-Driven</b></td> <td>No magic numbers anywhere in code</td> </tr> <tr> <td>🛡️ <b>Defensive Ingestion</b></td> <td>Every parse step uses coerce, not raise</td> </tr> <tr> <td>✅ <b>Correct Sign Handling</b></td> <td>Amount sign determines transaction direction</td> </tr> <tr> <td>🔀 <b>Separation of Concerns</b></td> <td>app.py contains zero calculations</td> </tr> <tr> <td>🧠 <b>Explainable ML</b></td> <td>Isolation Forest for detection; scoring uses interpretable ratios</td> </tr> <tr> <td>🔄 <b>Deterministic Outputs</b></td> <td>Same input always produces same results</td> </tr> <tr> <td>🌙 <b>Dark-First Design</b></td> <td>Framework-level dark theme enforcement</td> </tr> </table>
⚠️ Known Limitations
PDF parser is calibrated for a specific bank statement layout (Indian savings accounts)

Forecasting uses linear regression — with limited data, confidence intervals are wide

Recurring detection requires at least 2 months of data

PDF report does not embed charts (roadmap item)

No persistent storage — all analysis is session-scoped

🗺️ Roadmap
Status	Feature
⬜	Prophet-based seasonal forecasting
⬜	Charts embedded in PDF report via Plotly image export
⬜	Real-time bank API ingestion
⬜	PostgreSQL backend for persistent storage
⬜	User authentication and session management
⬜	KMeans behavioural clustering for spending archetypes
⬜	Multi-user analytics with isolated data namespaces
⬜	REST API backend separated from Streamlit UI
⬜	Parser extension for additional bank statement formats
👥 Authors
<table> <tr> <th>Author</th> <th>Role</th> <th>Contributions</th> </tr> <tr> <td><b>Vinay Hulsurkar</b></td> <td>Project Lead</td> <td>Architecture, ML Models, Project Management</td> </tr> <tr> <td><b>Gayatri Ghorpade</b></td> <td>ML & Forecasting</td> <td>Isolation Forest, Linear Regression, Health Score</td> </tr> <tr> <td><b>Tejas Chavan</b></td> <td>ETL & Dashboard</td> <td>⬅️ ETL Pipeline, Data Validation, Streamlit Dashboard</td> </tr> <tr> <td><b>Jitendra Chaudhary</b></td> <td>PDF & Testing</td> <td>PDF Report Generation, QA, Testing</td> </tr> </table>
📄 License
This project is licensed under the MIT License — see the LICENSE file for details.
