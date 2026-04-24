# 🛡️ Interactive Insurance Analytics Dashboard
> **An End-to-End BI Solution for Policy Performance, Claim Lifecycle, and Sentiment Analysis**

<p align="center">
  <img src="screenshots/Insurance_Overview.png" width="900" alt="Insurance Dashboard Overview">
  <br>
  <i>Figure 1: Executive Overview – Tracking $600M+ in Total Coverage</i>
</p>

## 📊 Project Overview
[cite_start]This dashboard provides a multi-visual analysis of insurance policy performance, premium revenue, and regional sales trends[cite: 23]. [cite_start]By integrating policy-level data with customer feedback, this solution enables stakeholders to monitor claim statuses and optimize underwriting decisions based on historical revenue patterns[cite: 23, 26].

* [cite_start]**Objective:** Monitor insurance policy performance and premium revenue across categories[cite: 23].
* [cite_start]**Impact:** Identified a **15-20% revenue spike in Q4** vs. Q2, providing data-driven evidence for seasonal underwriting adjustments[cite: 26].

---

## 🛠️ Technical Implementation & Engineering

### 1. Advanced Sentiment Analysis
<p align="center">
  <img src="screenshots/Customer_Sentiment.png" width="800" alt="Customer Sentiment Analysis">
</p>

* **Engineering:** Integrated a Word Cloud visual to process qualitative customer feedback, identifying "Average" and "Good" as dominant sentiment trends.
* **Impact:** Bridges the gap between financial metrics and customer experience to drive retention strategies.

### 2. Multi-Visual Policy Tracking
* [cite_start]**Visual Engineering:** Built a Ribbon Chart to rank over 5 policy categories, surfacing a **3-rank shift** in top-performing policies between Q1 and Q3[cite: 24].
* [cite_start]**Drill-Down Logic:** Designed Matrix and Donut Charts enabling granular drill-down into individual policy-level data for 4+ policy types[cite: 25].

### 3. Claim Lifecycle Management
<p align="center">
  <img src="screenshots/Data_Granularity.png" width="800" alt="Claim Data Granularity">
</p>

* **Logic:** Developed a tracking system for **Pending, Rejected, and Settled** claims across all policy types (Travel, Health, Home, Life, Auto).
* **Impact:** Highlights claim volume distribution, showing "Travel" insurance currently holds the highest claim volume with over **$202M in settled claims**.

---

## 📈 Key Business Insights
* [cite_start]**Revenue Patterns:** Modeled seasonal claims patterns to support underwriting decisions during high-volume quarters[cite: 26].
* [cite_start]**Operational Accuracy:** Configured **scheduled data refresh** on Power BI Service, ensuring report accuracy for a 3-member stakeholder team without manual intervention[cite: 27].
* **Demographic Analysis:** Uncovered that the "Adult" age group represents the highest claim amounts, peaking at nearly **$10M** in total claims.

---

## 📂 Repository Structure
* `/Dashboard`: Insurance_Analytics_Final.pbix
* `/Screenshots`: High-resolution dashboard captures
* `/Data`: (Optional) Schema documentation for SQL cleaning scripts

---

## 🛠️ How to View
1. Download the `.pbix` file from the `/Dashboard` folder.
2. Open using **Power BI Desktop**.
3. (Alternatively) View the [Live Dashboard] (Link your Power BI Service URL here).
