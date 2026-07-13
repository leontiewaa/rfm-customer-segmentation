# 🛍️ RFM Analysis: Customer Segmentation for E-Commerce

**RFM segmentation** (Recency, Frequency, Monetary) to identify key customer groups and generate actionable business recommendations.

**Business Impact:** The analysis revealed that **50% of customers are at risk or already lost** (At Risk + Lost segments), representing ~R$8M in revenue that the business risks losing.

**Interactive Dashboard:**  
[![View Dashboard](https://img.shields.io/badge/View-Tableau_Dashboard-blue?style=for-the-badge&logo=tableau)](https://public.tableau.com/app/profile/anastasya.l6624/viz/RFMAnalysisforCustomerSegmentation_17803974889450/Dashboard1?publish=yes)

---

## 📋 Project Overview

Olist is a Brazilian e-commerce marketplace. Using transactional data from 100k+ orders, customers were segmented by purchasing behavior to identify retention opportunities and prioritize marketing efforts.

**Hypotheses going in:** Most customers are one-time buyers with low retention — a common pattern in e-commerce marketplaces.

---

## 📊 Key Insights

| Segment | Customers | Avg. Revenue (R$) | Total Revenue (R$) |
|---------|-----------|-------------------|-------------------|
| Champions | 12,585 | 274.79 | 3,458,275 |
| Loyal Customers | 23,515 | 113.92 | 2,678,728 |
| New Customers | 11,975 | 160.96 | 1,927,469 |
| At Risk | 24,067 | 164.55 | 3,960,340 |
| Lost | 23,953 | 166.16 | 3,980,056 |

**Key finding:** 96% of customers made only 1 purchase (median Frequency = 1), confirming low retention across the platform.

---

## 📈 Visualizations

### Customer Distribution by Segment
![Segments](outputs/segment_distribution.png)

### Average Revenue by Segment
![Monetary](outputs/monetary_by_segment.png)

---

## 💡 Business Recommendations

| Priority | Segment | Action |
|----------|---------|--------|
| 🔴 **1** | **At Risk** | Re-engagement campaign — R$4M revenue at stake |
| 🟡 **2** | **Champions** | VIP program, exclusive offers — protect highest-value customers (avg R$275) |
| 🟡 **3** | **Loyal Customers** | Upgrade path to Champions via loyalty program and cross-sell |
| 🟢 **4** | **Lost** | Win-back campaign only if economically viable (Recency > 500 days) |

---

## 🔧 How to Reproduce

1. Clone the repository:
   ```bash
   git clone https://github.com/leontiewaa/rfm-customer-segmentation.git
   cd rfm-customer-segmentation
   ```

2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn kaggle
   ```

3. Set up Kaggle API credentials (`~/.kaggle/kaggle.json`)

4. Download the dataset:
   ```bash
   kaggle datasets download -d olistbr/brazilian-ecommerce --unzip -p data/raw
   ```

5. Open and run `notebooks/RFM_analysis_olist.ipynb`

---

## 🛠️ Stack

| Tool | Purpose |
|------|---------|
| **Python (pandas, numpy)** | Data processing and cleaning |
| **Python (matplotlib, seaborn)** | Visualization |
| **Tableau Public** | Interactive dashboard |
| **Jupyter Notebook** | Development environment |

---

## 📂 Data Source

[Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) — real e-commerce data (100k+ orders), Kaggle.

---

## 📅 Status

✅ Completed — July 2026  
📌 Next: Cohort retention analysis
