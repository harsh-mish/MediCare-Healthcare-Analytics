# 🏥 MediCare – Healthcare Analytics Dashboard

### Transforming Healthcare Data into Meaningful Insights

<p>
  <img src="https://img.shields.io/badge/Domain-Healthcare-0D9488?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Power%20BI-Analytics-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/Microsoft%20Fabric-Data%20Platform-0078D4?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Completed-16A34A?style=for-the-badge" />
</p>

**An end-to-end healthcare analytics project designed to monitor hospital performance, patient activity, financial claims, and treatment costs through interactive Power BI dashboards.**

</div>

---

## 📌 Table of Contents

* [Project Overview](#-project-overview)
* [Project Objectives](#-project-objectives)
* [Tools & Technologies](#-tools--technologies)
* [Dataset Overview](#-dataset-overview)
* [Data Model](#-data-model)
* [Dashboard Overview](#-dashboard-overview)
* [Key Performance Indicators](#-key-performance-indicators)
* [Key Business Insights](#-key-business-insights)
* [Project Structure](#-project-structure)
* [How to Use](#-how-to-use)
* [Future Enhancements](#-future-enhancements)
* [Disclaimer](#-disclaimer)

---

## 🔍 Project Overview

MediCare is a healthcare analytics and business intelligence project developed to transform healthcare-related data into meaningful and actionable insights.

Healthcare organizations generate large amounts of data related to patients, admissions, appointments, treatments, hospitals, doctors, bed utilization, and insurance claims.

This project brings these datasets together through a structured data model and interactive Power BI dashboards.

The solution helps stakeholders understand:

* Overall hospital performance.
* Patient and admission trends.
* Appointment and treatment activity.
* Hospital-wise bed occupancy.
* Insurance claim distribution.
* Claim approval performance.
* Treatment costs across different categories.

The primary goal is to support data-driven decision-making and improve visibility into healthcare operations.

---

## 🎯 Project Objectives

| Objective             | Description                                                      |
| --------------------- | ---------------------------------------------------------------- |
| Patient Analytics     | Monitor patient distribution and activity.                       |
| Hospital Performance  | Compare performance across hospitals.                            |
| Admission Analysis    | Understand admission trends and patterns.                        |
| Bed Utilization       | Monitor hospital bed occupancy.                                  |
| Financial Analysis    | Analyse claim amounts and approved amounts.                      |
| Claim Management      | Track approved, pending, rejected and partially approved claims. |
| Treatment Analysis    | Evaluate treatment costs by treatment category.                  |
| Interactive Reporting | Enable users to explore insights through slicers and visuals.    |

---

## 🛠️ Tools & Technologies

<p>
<img src="https://img.shields.io/badge/Microsoft%20Fabric-0078D4?style=flat-square&logo=microsoft&logoColor=white" />
<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" />
<img src="https://img.shields.io/badge/DAX-512BD4?style=flat-square" />
<img src="https://img.shields.io/badge/Power%20Query-00A4EF?style=flat-square" />
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" />
</p>

| Technology       | Purpose                                    |
| ---------------- | ------------------------------------------ |
| Microsoft Fabric | Data engineering and lakehouse environment |
| Power BI         | Interactive dashboard development          |
| DAX              | Measures, calculations and KPIs            |
| Power Query      | Data transformation and preparation        |
| SQL              | Data querying and analysis                 |
| PySpark          | Data processing and transformation         |

---

## 📂 Dataset Overview

The project uses generated healthcare data covering different aspects of hospital operations.

### Main Tables

| Table Name       | Description                                       |
| ---------------- | ------------------------------------------------- |
| Patients         | Patient demographics and registration information |
| Hospitals        | Hospital details and location information         |
| Departments      | Hospital department information                   |
| Doctors          | Doctor details and specializations                |
| Admissions       | Patient admission and discharge records           |
| Appointments     | Appointment details and waiting times             |
| Treatments       | Treatment types and treatment costs               |
| Insurance Claims | Insurance claim amounts and approval details      |
| Bed Utilization  | Total, occupied and available beds                |
| Patient Feedback | Patient ratings and feedback categories           |

### Dataset Summary

The project includes multiple healthcare datasets covering:

* 25K+ patient records
* 100K appointment records
* 75K treatment records
* 40K insurance claim records
* 35K admission records
* 25K patient feedback records
* 8 hospitals

*Record counts represent the generated project datasets and may vary after filtering or data cleaning.*

---

## 🧩 Data Model

The project uses fact and dimension tables to organize healthcare information for analytical reporting.

### Fact Tables

* Fact Admissions
* Fact Appointments
* Fact Treatments
* Fact Insurance Claims
* Fact Bed Utilization
* Fact Patient Feedback

### Dimension Tables

* Dim Patient
* Dim Hospital
* Dim Department
* Dim Doctor
* Dim Date

The data model is designed to support analytical relationships and cross-filtering between related healthcare entities.

---

## 📊 Dashboard Overview

The MediCare dashboard is organized into two major analytical pages.

### 🏠 1. Executive Overview

This page provides a high-level view of healthcare operations and hospital performance.

**Key Visualizations:**

* Total Patients
* Total Admissions
* Total Appointments
* Total Treatments
* Average Patient Rating
* Admission Trends
* Hospital-wise Bed Occupancy Rate
* Hospital Comparison

**Interactive Slicers:**

* Year
* Hospital Name
* Department Name
* Insurance Type
* Hospital Type

#### Dashboard Screenshot

![MediCare Executive Overview](Screenshots/Executive_Overview.png)

---

### 💰 2. Financial & Claims Analysis

This page focuses on financial claim performance and treatment costs.

**Key Performance Indicators:**

* Total Claim Amount
* Approved Amount
* Total Treatment Cost
* Claim Approval Rate

**Key Visualizations:**

* Claims by Status
* Claim Amount vs Approved Amount
* Monthly Claim Trends
* Treatment Cost by Treatment Type
* Claim Status Summary

**Interactive Slicers:**

* Year
* Month Name
* Claim Status
* Treatment Type

#### Dashboard Screenshot

![MediCare Financial and Claims Analysis](Screenshots/Financial_Claims_Analysis.png)

---

## 📈 Key Performance Indicators

| KPI                  | Business Purpose                             |
| -------------------- | -------------------------------------------- |
| Total Patients       | Measures the overall patient population      |
| Total Admissions     | Tracks hospital admission activity           |
| Total Appointments   | Measures appointment volume                  |
| Total Treatments     | Tracks treatment activity                    |
| Average Rating       | Measures patient satisfaction                |
| Bed Occupancy Rate   | Evaluates hospital bed utilization           |
| Total Claim Amount   | Measures the total value of insurance claims |
| Approved Amount      | Tracks the amount approved by insurers       |
| Claim Approval Rate  | Measures the proportion of approved claims   |
| Total Treatment Cost | Evaluates treatment-related costs            |

---

## 💡 Key Business Insights

The dashboard enables stakeholders to investigate questions such as:

1. Which hospital has the highest patient volume?
2. How do admissions change over time?
3. Which hospital has the highest bed occupancy rate?
4. Which hospitals have comparatively higher admission activity?
5. What proportion of claims are approved, pending or rejected?
6. How does the approved amount compare with the total claim amount?
7. Which treatment category contributes the highest treatment cost?
8. How do claim amounts change across different months?
9. How does patient feedback vary across departments?
10. How can hospital performance be compared using multiple KPIs?

---

## 📁 Project Structure

```text
MediCare-Healthcare-Analytics/
│
├── Dashboard/
│   └── MediCare_Dashboard.pbix
│
├── Screenshots/
│   ├── Executive_Overview.png
│   └── Financial_Claims_Analysis.png
│
├── Data/
│   └── Dataset_Information.md
│
├── SQL/
│   └── SQL_Queries.sql
│
├── Notebooks/
│   └── Data_Transformation_Notebooks/
│
└── README.md
```

*Include only the folders and files that are actually available in your repository.*

---

## 🚀 How to Use

Follow these steps to explore the project:

1. Clone or download this repository.
2. Open the `Dashboard` folder.
3. Download the Power BI `.pbix` file.
4. Open it using Microsoft Power BI Desktop.
5. Explore the Executive Overview page.
6. Navigate to Financial & Claims Analysis.
7. Use the available slicers to filter and analyse the data.

**Note:** If your report uses external data sources or a Fabric workspace, those connections may need to be configured in your own environment.

---

## 🔮 Future Enhancements

Potential improvements for the project include:

* Additional hospital operational analytics.
* Doctor performance analysis.
* Advanced patient satisfaction analysis.
* More detailed insurance claim monitoring.
* Real-time healthcare data integration.
* Advanced predictive analytics.
* Enhanced drill-through reporting.

---

## ⚠️ Disclaimer

This project is developed for educational, portfolio and analytical demonstration purposes.

The healthcare dataset used in this project is generated/synthetic and does not represent actual patients, hospitals, medical records, or insurance transactions.

The dashboard is not intended for clinical diagnosis, medical treatment decisions, or real-world financial decisions.

---

## 👨‍💻 Author

<div align="center">

### Harsh Mishra

**Computer Science Engineering Graduate | Data Analytics | Data Engineering**

<p>
  <a href="https://github.com/harsh-mish">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

*Turning data into insights and insights into better decisions.*

</div>

---

<div align="center">

### 🏥 MediCare – Better Health. Brighter Tomorrow.

**Thank you for exploring this project!**

⭐ If you find this project useful, consider giving the repository a star.

</div>

