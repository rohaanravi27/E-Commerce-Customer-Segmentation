 E-Commerce Customer Segmentation Engine 🚀

An end-to-end Python data analytics project engineering a behavioral customer segmentation engine. This application reviews transactional records and maps active buyers into high-impact marketing cohorts using the RFM (Recency, Frequency, Monetary) analytical framework.

## 🛠️ Tech Stack & Core Libraries
- **Language:** Python
- **Libraries:** Pandas, NumPy, Datetime
- **Methodology:** RFM Behavioral Modeling, Data Pipeline Cleaning, Quantile-based Cohort Scoring

## 📈 Data Pipeline Workflow & Structure
1. **Data Review & Sanity Checks:** Isolate missing records, remove negative unit prices, and resolve transaction value returns to ensure analytical integrity.
2. **Metrics Engineering:** Calculate days since last order (Recency), count total distinct transactions (Frequency), and aggregate net purchases per customer ID (Monetary).
3. **Behavioral Cohort Ranking:** Segment rows dynamically using percentiles into automated customer brackets:
   - 🌟 **Champions:** High-frequency, high-margin recent buyers.
   - 🤝 **Loyal Customers:** Frequent buyers highly responsive to brand paths.
   - ⚠️ **At-Risk / Cant Lose Them:** High total spenders who haven't returned recently.
   - 💤 **Hibernating:** Infrequent, low-value buyers requiring reactivation strategies.
