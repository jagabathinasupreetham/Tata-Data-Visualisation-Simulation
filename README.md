# Tata - Data Visualisation: Empowering Business with Effective Insights

## 📊 Project Overview
This repository contains the work and deliverables for the **Tata Data Visualisation Job Simulation** via Forage. The objective of this project was to analyze transactional retail data and build an executive-level Tableau dashboard to answer four strategic business questions for the CEO and CMO regarding seasonal revenue trends, international expansion, and high-value customer retention.

---

## 📂 Dataset Information (`online_retail.csv`)
* **Source:** Online retail transactional dataset representing sales from a UK-based online retail company.
* **Data Cleaning & Preparation:** 
  * Filtered out canceled transactions and returns by removing negative or zero quantities (`Quantity >= 1`).
  * Removed unverified or zero unit-price entries (`UnitPrice >= 0.01`).
  * Created a calculated revenue field (`Revenue = Quantity * UnitPrice`) for accurate financial modeling at the line-item level.

---

## 📈 Key Insights & Dashboard Breakdown

1. **2011 Monthly Revenue Trend (CEO Scenario):**
   * Revenue remained steady between £500K and £750K through August, followed by an aggressive Q4 surge that peaked in November at **over £1.45M**.
   * *Recommendation:* Supply chain and inventory ramp-up must begin by mid-August to prevent stockouts during the peak Q4 holiday season.

2. **Top 10 International Markets (CMO Scenario):**
   * **The Netherlands** and **EIRE (Ireland)** lead non-UK revenue generation (~£280K each), followed closely by Germany, France, and Australia.
   * *Recommendation:* Target localized marketing campaigns in Western Europe and establish regional logistics hubs to reduce cross-border delivery friction.

3. **High-Value Customer Concentration (CEO Scenario):**
   * Heavy B2B wholesale concentration, with individual top clients (e.g., Customer `14646` and `18102`) generating over £250K+ each, and the top 10 customers accounting for **£1.5M+**.
   * *Recommendation:* Implement a dedicated Key Account Management (KAM) program to secure long-term retention of top-tier wholesale accounts.

4. **Global Product Demand Footprint (CMO Scenario):**
   * Visualized unit demand across global territories, identifying strong organic traction in Australia alongside early North American and East Asian reach.

---

## 🛠️ Tools & Technologies Used
* **Tableau Desktop / Tableau Public:** Data transformation, calculated fields, hierarchy mapping, and interactive dashboard design.
* **Microsoft Excel / CSV:** Initial data review, validation, and sanitation.

---

## 🚀 How to View This Project
1. Download the **`Tata_Online_Retail_Analysis.twbx`** packaged workbook from this repository.
2. Open the file using **Tableau Desktop** or free **Tableau Reader** to explore the interactive dashboard and filters.
