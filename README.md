# Customer Insights Analytics

> **End-to-End Data Analysis Project:** Transforming raw e-commerce data into actionable business intelligence through Python analysis and interactive Tableau dashboards.

[![Python](https://img.shields.io/badge/Python-3.12-blue.svg)](https://www.python.org/)
[![Tableau](https://img.shields.io/badge/Tableau-Public-orange.svg)](https://public.tableau.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

[🔗 **Live Tableau Dashboard**]
(https://public.tableau.com/views/Customer_Data_to_Insight/ExecutiveSummary?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) 

---

## 📊 Project Overview

This project demonstrates a complete data analytics workflow, from raw data extraction to executive-level insights. The analysis examines **48 customers** with **completed orders** from an e-commerce platform, representing **$110,300** in confirmed revenue over a **98-day period** (Jan-Apr 2018).

### Key Achievement

**Identified $45,500 in at-risk revenue (41% of total)** and discovered a **2.6x CLV lift opportunity** from converting one-time buyers to repeat customers.

---

## 🎯 Business Problem

An e-commerce company needed to:
- ✅ Understand customer value segmentation and identify high-value customers
- ✅ Identify at-risk customers with declining engagement
- ✅ Analyze order completion rates and revenue trends
- ✅ Develop data-driven retention and growth strategies
- ✅ Optimize payment methods and reduce cart abandonment

---

## 🛠️ Technologies Used

| Category | Tools |
|----------|-------|
| **Programming** | Python 3.12 |
| **Data Processing** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn |
| **Business Intelligence** | Tableau Public |
| **Development** | Jupyter Notebook |
| **Version Control** | Git, GitHub |

---

## 📁 Project Structure

```
customer-insights-analytics/
│
├── customer_data_insight.ipynb          # Main analysis notebook (Jupyter)
├── README.md                            # Project documentation
├── Business_Insights_Report.txt         # Comprehensive business intelligence report
├── data_dictionary.csv                  # Field definitions and use cases
│
├── raw_data/                            # Original source data
│   ├── raw_customers.csv                # Customer master data (100 records)
│   ├── raw_orders.csv                   # Order transactions (99 records)
│   └── raw_payments.csv                 # Payment details (113 records)
│
├── output_data/                         # Cleaned & processed datasets
│   ├── customer_insights_dashboard.csv  # Main dashboard dataset (48 customers)
│   ├── summary_statistics.csv           # Key metrics (20 KPIs)
│   ├── segment_analysis.csv             # Customer segmentation (3 segments)
│   ├── monthly_performance.csv          # Time-series metrics (4 months)
│   ├── payment_method_analysis.csv      # Payment insights (4 methods)
│   ├── top_20_customers.csv             # VIP customer list (top 20)
│   ├── order_status_breakdown.csv       # Order funnel (5 statuses)
│   └── data_dictionary.csv              # Field definitions
│
├── figures/                             # Generated visualizations (PNG)
│   ├── 1_clv_distribution.png
│   ├── 2_top_10_customers.png
│   ├── 3_customer_segmentation.png
│   ├── 4_revenue_by_segment.png
│   ├── 5_order_status.png
│   ├── 6_payment_method_revenue.png
│   ├── 7_orders_revenue_correlation.png
│   └── 8_customer_behavior_comparison.png
│
└── tableau_dashboard/                   # Tableau files
    ├── Customer_Insights_Dashboard.twbx # Packaged Tableau workbook
    └── tableau_dashboard_screenshot.png # Dashboard preview
```

---

## 📈 Key Findings

### 💰 Customer Segmentation
- **High Value** (>$2,749): 16 customers (33%) → **$65,800 revenue (60%)**
- **Medium Value** ($1,500-$2,749): 14 customers (29%) → **$30,100 revenue (27%)**
- **Low Value** (<$1,500): 18 customers (38%) → **$14,400 revenue (13%)**

### 🎯 Revenue Concentration (Pareto Analysis)
- Top **20% of customers** generate **41.3% of revenue** ($45,600)
- Single top customer (Howard R.) contributes **9% of total revenue** ($9,900)
- **High customer concentration = elevated business risk**

### 🔄 Customer Behavior
| Customer Type | Count | % | Avg CLV | CLV Lift |
|---------------|-------|---|---------|----------|
| **One-Time Buyers** | 33 | 69% | $1,542 | - |
| **Repeat Customers** | 15 | 31% | $3,960 | **2.6x** |

### 📊 Operational Metrics
- **Order Completion Rate:** 67.7%
- **Return Rate:** 6.1%
- **Average CLV:** $2,297.92
- **Customers At Risk:** 40 (no purchase in 30+ days)

### 📅 Revenue Trends (Monthly)
| Month | Revenue | Completion Rate |
|-------|---------|-----------------|
| January 2018 | $42,400 | 82.8% |
| February 2018 | $40,000 | 96.3% |
| March 2018 | $27,900 | 48.6% |
| April 2018 | $0 | 0% (in progress) |

---

## 🎨 Tableau Dashboard Features

### Interactive Visualizations
1. **KPI Cards:** 5 key metrics at a glance
2. **Revenue by Segment:** Pie chart showing value distribution
3. **Top 20 Customers:** Bar chart with revenue rankings
4. **Monthly Performance:** Dual-axis trend analysis
5. **Customer Type Analysis:** Stacked bar comparing segments
6. **Customer Matrix:** Scatter plot (orders vs revenue)
7. **At-Risk Alert:** Highlighted customers needing attention

### Dashboard Capabilities
- ✅ Filter by customer segment (High/Medium/Low Value)
- ✅ Drill-down into individual customer details
- ✅ Time-series trend analysis
- ✅ Interactive tooltips with customer names and metrics

---

## 💡 Business Recommendations

### 1. VIP Retention Program (Priority: CRITICAL)
**Target:** Top 10 customers ($45,500 revenue at risk)
- Dedicated account manager
- 15% loyalty discount
- Quarterly check-ins
- **Expected Impact:** Protect 41% of revenue stream

### 2. One-Time Buyer Conversion Campaign
**Target:** 33 one-time buyers
- "Welcome Back" 15% discount at Day 30
- Personalized product recommendations
- **Expected Impact:** $12,725-$17,815 additional revenue (Year 1)

### 3. At-Risk Customer Re-engagement
**Target:** 40 customers (>30 days inactive)
- Automated email sequence
- Exclusive "We miss you" offer
- **Expected Impact:** 25-30% reactivation rate

### 4. Payment Optimization
- Streamline credit card checkout (53% of revenue)
- Add Apple Pay / Google Pay
- **Expected Impact:** 10-15% reduction in cart abandonment

---

## 🚀 Getting Started

### Prerequisites
```bash
Python 3.12+
Tableau Desktop or Tableau Public
Git
```

### Installation

1. **Clone the repository:**
```bash
git clone https://github.com/farzana-bhuiyan-meem/customer-insights-analytics.git
cd customer-insights-analytics
```

2. **Create virtual environment:**
```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
```

3. **Install dependencies:**
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

4. **Run the analysis:**
```bash
jupyter notebook customer_data_insight.ipynb
```

5. **Open Tableau Dashboard:**
- Open `tableau_dashboard/Customer_Insights_Dashboard.twbx` in Tableau
- Or view online: [Live Dashboard Link]
(https://public.tableau.com/views/Customer_Data_to_Insight/ExecutiveSummary?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## 📊 Data Dictionary

| Field | Description | Use Case |
|-------|-------------|----------|
| `customer_id` | Unique customer identifier | Tracking individual customers |
| `segment_label` | Customer value tier (High/Medium/Low) | Targeted marketing campaigns |
| `total_revenue` | Customer lifetime value | VIP program eligibility |
| `revenue_rank` | Rank by total revenue | Identify top customers |
| `is_top_20_pct` | Top 20% revenue contributor flag | Priority account management |
| `at_risk_flag` | Inactive >30 days | Re-engagement campaigns |
| `customer_type` | One-Time or Repeat buyer | Retention strategy |
| `days_since_last_order` | Days since last purchase | Churn prediction |

---

## 📝 Analysis Methodology

### Data Pipeline
1. **Extraction:** Load raw CSV files (customers, orders, payments)
2. **Cleaning:** Handle missing values, standardize formats, validate data quality
3. **Transformation:** Aggregate payments, calculate CLV metrics, join datasets
4. **Segmentation:** Percentile-based value tiers (33rd, 67th percentiles)
5. **Analysis:** Statistical analysis, correlations, Pareto analysis
6. **Visualization:** 8 professional charts + interactive Tableau dashboard
7. **Reporting:** Executive summary with actionable recommendations

### Key Calculations
- **Customer Lifetime Value (CLV):** Sum of all completed order values per customer
- **Customer Segments:** Based on revenue percentiles (Low: 0-33%, Medium: 33-67%, High: 67-100%)
- **At-Risk Flag:** Last order >30 days ago
- **CLV Lift:** Repeat customer avg CLV / One-time buyer avg CLV
- **Pareto Analysis:** Cumulative revenue contribution by customer rank

---

## 🎓 Skills Demonstrated

- ✅ End-to-end data analysis workflow
- ✅ Data cleaning and validation
- ✅ Customer segmentation (RFM-style analysis)
- ✅ Statistical analysis and correlation
- ✅ Business intelligence reporting
- ✅ Interactive dashboard design
- ✅ Data storytelling and visualization
- ✅ Python programming (Pandas, NumPy, Matplotlib)
- ✅ Tableau dashboard development
- ✅ Git version control

---

## 📊 Results & Impact

### Financial Projections (12 Months)

| Scenario | Revenue Growth | Investment | ROI |
|----------|---------------|------------|-----|
| **Conservative (25%)** | +$27,575 | $8,824 | 212% |
| **Moderate (35%)** | +$38,605 | $11,030 | 250% |
| **Optimistic (50%)** | +$55,150 | $13,236 | 317% |

### Success Metrics
- **Customer Lifetime Value:** $2,298 → $2,872 (+25%)
- **Repeat Purchase Rate:** 31% → 45-50%
- **Revenue from Top 20%:** 41% → 60-65%
- **Order Frequency:** 1.4 → 1.9-2.1 orders per customer

---


## 🙏 Acknowledgments

- Dataset inspired by dbt's Jaffle Shop demo
- Analysis framework based on e-commerce best practices
- Tableau Public for hosting interactive dashboards

---
🔗 **Live Dashboard:** [View on Tableau Public]
(https://public.tableau.com/views/Customer_Data_to_Insight/ExecutiveSummary?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
