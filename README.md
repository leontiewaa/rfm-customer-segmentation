# 🛍️ RFM Analysis: Customer Segmentation for E-Commerce

**RFM segmentation** (Recency, Frequency, Monetary) to identify key customer groups and generate actionable business recommendations.

**Business Impact:** The analysis revealed that **52% of customers are at risk** (Hibernating + Lost segments), representing an opportunity to recover ~R$8M in potential revenue through re-engagement campaigns.

**Interactive Dashboard:**  
[![View Dashboard](https://img.shields.io/badge/View-Tableau_Dashboard-blue?style=for-the-badge&logo=tableau)](https://public.tableau.com/app/profile/anastasya.l6624/viz/RFMAnalysisforCustomerSegmentation_17803974889450/Dashboard1?publish=yes)

## 📊 Key Insights

## 📊 Key Insights

| Segment | Number of Customers | Avg. Revenue (R$) |
|---------|---------------------|-------------------|
| Champions (Gold) | 11,928 | 273.51 |
| Regular | 17,556 | 181.86 |
| Hibernating | 24,013 | 173.74 |
| Lost | 24,060 | 161.47 |
| Loyal Customers | 9,290 | 101.82 |
| New Customers | 9,246 | 57.19 |

## 📈 Visualizations

### Customer Distribution by Segment
![Segments](outputs/segment_distribution.png)

### Average Revenue by Segment
![Monetary](outputs/monetary_by_segment.png)

---

## 💡 Business Recommendations

| Segment | Action |
|---------|--------|
| 🏆 **Champions** | VIP program, personalized discounts, exclusive offers |
| 💎 **Loyal Customers** | Loyalty program, cross-sell, referral program |
| 🆕 **New Customers** | Welcome email sequence, first-purchase discount |
| 😴 **Hibernating** | Re-activation email with 10–15% promo code |
| 📉 **Lost** | Win-back campaign (if economically viable) |
| 👥 **Regular** | Gradual engagement increase |

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| **Python (pandas, numpy)** | Data processing and cleaning |
| **Python (matplotlib, seaborn)** | Visualization |
| **Tableau Public** | Interactive dashboard |
| **Jupyter Notebook** | Development environment |

---

## 🔧 How to Reproduce

1. Clone the repository:
   ```bash
   git clone https://github.com/leontiewaa/rfm-customer-segmentation.git
Install dependencies:

bash
pip install pandas numpy matplotlib seaborn
Launch Jupyter Notebook and open notebooks/01_RFM_Analysis.ipynb
Load the dashboard in Tableau Public using data/for_tableau.csv
## 📂 Data Source

Brazilian E-Commerce Public Dataset by Olist — real e-commerce data (100k+ orders).

## 📅 Status

✅ Project completed — June 2026
📌 Next project: Cohort retention analysis