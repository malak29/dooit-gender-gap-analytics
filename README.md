---

# 📊 Gender Disparity in Medical Payments – Dooit Project

An end-to-end machine learning and data analytics pipeline built to uncover gender-based disparities in medical device and healthcare payments using three years of Open Payments data. This project was developed as part of an experiential industry capstone for [Dooit](https://www.dooit.biz/), a leadership development firm.

---

## 🎯 Project Objective

To investigate and visualize trends in gender-based payment disparities across specialties, companies, and payment types in the U.S. medical sector, enabling Dooit to offer more targeted leadership interventions and advocacy for women in healthcare.

---

## 🛠️ Tech Stack

* **Languages:** Python (3.10), SQL
* **Libraries:** Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, Plotly
* **ML Models:** KMeans Clustering, DBSCAN, Isolation Forest
* **Pipeline Tools:** Jupyter, PySpark, Airflow
* **Storage & Processing:** CSV, Parquet
* **Version Control:** Git + GitHub

---

## 🔄 Data Pipeline

1. **Data Source:** 3 years of U.S. Open Payments Data (2021–2023)
2. **Preprocessing:**

   * Merged general and research payments
   * Cleaned and standardized physician names, NPI IDs, and specialties
   * Mapped gender and payment type splits
3. **Feature Engineering:**

   * Payment categories, company name normalization
   * Gender ratios per category and specialty
4. **EDA:**

   * Payment trends over time, gender split per specialty
   * Highlighted key gaps using stacked bar and violin plots
5. **ML & Clustering:**

   * KMeans and DBSCAN for specialty grouping
   * Outlier detection on high-disparity payments
6. **Insights Generation:**

   * Narrowed gender gap by 51% overall from 2021–2023
   * 300% rise in female non-physician practitioner payments
   * 43% gender gap reduction in physicians

---

## 📈 Key Findings

* **60% more** spent on male promotions than females across top 20 companies.
* **80.6% of physician payments** went to males vs. 13.2% to females in 2023.
* **Speaker payments** showed a **20% gender gap improvement**, while consulting and royalties showed widening gaps.
* Female representation increased significantly in **nurse practitioners**, but decreased for **certified nurse-midwives**.
* General **gender payment gap dropped from \$5.5M to \$2.7M** over 3 years.

---

## 💡 Recommendations to Dooit

* Focus leadership development workshops on male-dominated specialties.
* Launch structured mentorships for women in research and consulting.
* Engage top-paying companies for equity-focused policy advocacy.
* Design dashboards for ongoing disparity monitoring using this pipeline.

---
