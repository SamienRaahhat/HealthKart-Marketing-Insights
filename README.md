# HealthKart-Marketing-Insights
Simulated influencer marketing campaign data for HealthKart with performance tracking, ROI/ROAS calculation, insights visualization, and campaign summary.

# 💪 HealthKart Influencer ROI Dashboard

A data science project to simulate and analyze influencer marketing campaigns for HealthKart. It evaluates campaign performance using ROI, ROAS, and incremental revenue metrics, built entirely in Jupyter Notebook using Python, Pandas, and Seaborn.

---

## 🔧 Tools Used
- Jupyter Notebook
- Python (pandas, numpy, faker, matplotlib, seaborn)

---

## 📁 Simulated Datasets
| File              | Description |
|-------------------|-------------|
| `influencers.csv` | Influencer name, gender, platform, follower count |
| `posts.csv`       | Post-level reach, likes, comments, platform |
| `tracking_data.csv` | Simulated user orders, revenue by influencer and product |
| `payouts.csv`     | Influencer payments (per post or per order) |

---

## 📊 Metrics Computed
- **ROAS** = Revenue / Ad Spend
- **ROI** = (Revenue – Payout) / Payout
- **Incremental ROAS** = (30% Revenue) / Payout

---

## 🧠 Assumptions
- 30% of revenue is assumed to be incremental
- Payouts are randomly assigned as per-post or per-order
- Orders simulate real behavior using Faker
- Revenue per order: ₹500 to ₹1500

---

## 📈 Features
- Performance tracking of posts and influencers
- ROAS and ROI comparison across personas
- Platform/category-wise insights
- Exportable performance summary to CSV
- Visualizations for top and poor performing influencers

---

## 🚀 How to Run
1. Clone the repo
2. Open Jupyter and run:
   - `simulate_data.ipynb` → creates all 4 datasets
   - `influencer_dashboard.ipynb` → analysis + insights
3. Export insights using `.to_csv()` and `plt.savefig()`

---

## 📎 Deliverables
- 📓 Jupyter notebooks
- 📊 Visualized insights
- 📄 README.md (this file)
- 🧾 PDF insights summary *(optional)*
- 📁 Exported CSV files

---

## 📌 Status
✅ Data simulation complete  
✅ Metrics computed (ROI, ROAS, incremental ROAS)  
✅ Visualizations created  
🔜 Final summary PDF in progress  
🔜 Notebook polishing and GitHub publishing

---

## 🙌 Credits
Made with Intent, 
Samien Raahhat

