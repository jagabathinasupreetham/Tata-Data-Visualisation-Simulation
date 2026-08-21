# Tata - Data Visualisation: Empowering Business with Effective Insights

## 🖼️ Dashboard Preview
<p align="center">
  <img src="dashboard-preview.png" alt="Tata Data Visualisation Dashboard" width="850"/>
</p>

---

## 📊 Project Overview
This repository contains the deliverables and project files for the **Tata Data Visualisation Job Simulation** via Forage. The objective was to analyze transactional retail data and build an executive-level Tableau dashboard to address four strategic business questions for the CEO and CMO regarding seasonal revenue spikes, international market expansion, and high-value customer retention.

---

## 📂 Dataset & Data Cleaning (`online_retail.csv`)
* **Source:** Transactional retail dataset from a UK-based online retailer.
* **Data Preparation Steps:**
  * **Removed Returns & Invalid Quantities:** Filtered out negative or zero quantities (`Quantity >= 1`) to eliminate order cancellations.
  * **Sanitized Pricing:** Removed zero and unverified unit prices (`UnitPrice >= 0.01`).
  * **Calculated Revenue:** Created a custom line-item revenue field (`Revenue = Quantity * UnitPrice`) for accurate financial modeling.

---

## 📈 Key Insights & Strategic Breakdown

1. **2011 Monthly Revenue Trend (CEO Scenario):**
   * Revenue remained steady between £500K and £750K from January through August, followed by an aggressive Q4 surge peaking in November at **over £1.45M**.
   * *Strategic Recommendation:* Supply chain procurement, warehouse staffing, and inventory buffering must be finalized by **mid-August** to prevent fulfillment bottlenecks during the Q4 rush.

2. **Top 10 International Markets (CMO Scenario):**
   * **The Netherlands** and **EIRE (Ireland)** lead non-UK revenue generation (~£280K each), closely followed by Germany, France, and Australia.
   * *Strategic Recommendation:* Focus digital marketing budgets on Western Europe and establish a regional European fulfillment center to cut delivery times.

3. **High-Value Customer Concentration (CEO Scenario):**
   * Heavy B2B wholesale concentration, with top individual clients (e.g., Customer `14646` and `18102`) driving over £250K+ each, and the top 10 customers generating **£1.5M+** in total sales.
   * *Strategic Recommendation:* Implement a dedicated Key Account Management (KAM) program with custom wholesale pricing tiers to secure multi-year retention.

4. **Global Product Demand Footprint (CMO Scenario):**
   * Visualized global unit demand, highlighting strong organic traction in Australia and steady early reach across North America and East Asia.

---

## 🛠️ Tools & Technologies Used
* **Tableau Desktop / Tableau Public:** Data transformation, calculated fields, and interactive dashboard design.
* **Microsoft Excel / CSV:** Initial data validation and sanitation.

---

## 🚀 How to View This Project
1. Download the **`Tata_Online_Retail_Analysis.twbx`** packaged workbook from this repository.
2. Open the file using **Tableau Desktop** or free **Tableau Reader** to explore the interactive dashboard.
