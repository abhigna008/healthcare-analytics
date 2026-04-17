# 🏥 Papollo Apotheke - Healthcare Operations Dashboard

## 📊 Overview
This project is a comprehensive business intelligence solution designed for hospital administrators. The dashboard provides a "single pane of glass" to manage patient workflows, analyze clinical diagnostic trends, and monitor financial performance (Billing vs. Health Insurance). 

The goal of this project was to transform raw clinical admission and billing data into actionable insights that can improve operational efficiency and patient care quality.

---

## 📌 Dashboard Previews

### 1️⃣ Master Executive View
This view shows high-level KPIs and aggregate trends for the entire hospital.

![Master Dashboard View](YOUR_IMAGE_LINK_HERE)

### 2️⃣ Granular Patient Lookup (Search & Filter Feature)
This view demonstrates the dashboard's powerful filtering capability. By selecting a specific **Patient_ID**, the entire dashboard cross-filters to show a personalized snapshot of that individual's journey:
* **Specific Diagnosis:** Instantly identifies the patient's condition (e.g., Pneumonia, Flu).
* **Financial Summary:** Shows the exact **Billing Amount** vs. **Health Insurance** coverage for that specific ID.
* **Timeline:** Displays the Admit, Discharge, and Follow-up dates for that specific patient record.
* **Doctor Assignment:** Shows which doctor treated them and the feedback score associated with that visit.

![Granular Patient View](YOUR_IMAGE_LINK_HERE)

---

## 💡 Key Business Insights

| Analysis Area | Visual | Business Value |
| :--- | :--- | :--- |
| **Financials** | Billing vs. Insurance | Visualizes the "revenue gap" (uncovered costs), helping administrators optimize billing and insurance negotiations. |
| **Logistics** | Bed Occupancy | Identifies "Private" vs "General" room demand to prioritize future resource allocation. |
| **Clinical** | Diagnosis Funnel | Tracks common ailments (Viral Infection, Flu) to forecast seasonal staffing and medicine inventory levels. |
| **Quality** | Doctor Satisfaction | Provides immediate feedback on patient satisfaction across the medical team. |

---

## 🛠️ Technical Implementation

* **Data Transformation:** Used Power Query to handle complex date formatting and data cleaning.
* **UI/UX Design:** Created a custom "App-like" interface using card layouts and a consistent medical color palette.
* **Granular Filtering:** Built a search-based slicer for **Patient_ID** that enables "Drill-Down" functionality across all visuals.

---

## 🚀 How to View this Project

I have uploaded the actual **`Healthcare_Analysis.pbix`** file to this repository. You can download it to explore the interactivity. I have also attached screenshots of the dashboard in the folder Dashboard_Screenshots for your reference.

### ⚠️ Note on Interactive Link:
Because I am using a personal Power BI version (without a Pro/Premium Organizational account), I cannot provide a live "Publish to Web" link. However, the provided **Screenshots** and the **Source File** fully document the design and functionality of the tool.
