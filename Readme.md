<div align="center"> <img src="assets/medicare_banner.svg" alt="MediCare - Healthcare Analytics Dashboard" width="100%" /> <a href="https://github.com/harsh-mish"> <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=24&duration=2800&pause=700&color=0EA5E9&center=true&vCenter=true&width=850&lines=%F0%9F%8F%A5+Transforming+Healthcare+Data+into+Insights;%F0%9F%93%8A+Power+BI+%2B+DAX+%2B+Microsoft+Fabric;%F0%9F%92%8A+Patients+%7C+Hospitals+%7C+Claims+%7C+Treatments;%E2%9C%A8+Medallion+%7C+Star+Schema+%7C+Spark+SQL+%7C+RLS" alt="Typing SVG" /> </a>

<br/><br/>

<img src="https://img.shields.io/badge/DOMAIN-HEALTHCARE-0D9488?style=for-the-badge&logo=healthicons&logoColor=white" /> <img src="https://img.shields.io/badge/POWER%20BI-ANALYTICS-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" /> <img src="https://img.shields.io/badge/MICROSOFT%20FABRIC-DATA%20PLATFORM-0078D4?style=for-the-badge&logo=microsoft&logoColor=white" /> <img src="https://img.shields.io/badge/STATUS-COMPLETED-16A34A?style=for-the-badge&logo=checkmarx&logoColor=white" /> <br/> <img src="https://img.shields.io/badge/🥉🥈🥇%20Medallion%20Architecture-0891B2?style=for-the-badge" /> <img src="https://img.shields.io/badge/🔐%20RLS%20·%20CLS%20·%20OLS-EF4444?style=for-the-badge" /> <img src="https://img.shields.io/badge/🧩%20Star%20Schema-EC4899?style=for-the-badge" /> <br/> <img src="https://img.shields.io/badge/DAX-512BD4?style=flat-square&logo=powerbi&logoColor=white" /> <img src="https://img.shields.io/badge/Power%20Query-00A4EF?style=flat-square" /> <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white" /> <img src="https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" /> <img src="https://img.shields.io/badge/Synthetic%20Data-8B5CF6?style=flat-square" /> <img src="https://img.shields.io/badge/Dashboards-2-F97316?style=flat-square" />

<br/><br/>

🩺 An end-to-end healthcare analytics project to monitor hospital performance, patient activity, financial claims and treatment costs through interactive Power BI dashboards.
</div> <img src="assets/ecg_divider.svg" width="100%" alt="ECG divider" />
🧭 Table of Contents
<div align="center">
🟦	Section	🟩	Section	🟧	Section
1	🔍 Overview	7	📊 Dashboard Overview	13	📁 Project Structure
2	🎯 Objectives	8	📸 Visuals	14	🚀 How to Use
3	🛠️ Tools	9	📈 KPIs	15	📚 Skills Demonstrated
4	🏗️ Architecture · 🥉🥈🥇 Medallion	10	🧮 DAX Measures	16	🔮 Future Enhancements
5	📂 Dataset	11	💡 Insights	17	⚠️ Disclaimer
6	🧩 Data Model · 🔐 Security	12	🎨 Design Highlights	18	👨‍💻 Author
</div> <img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,12,20,24&height=4" width="100%" />
🔍 Project Overview

[!NOTE] MediCare turns scattered healthcare records into one clear, interactive story.

Hospitals generate huge volumes of data every day: patients, admissions, appointments, treatments, doctors, departments, bed utilization and insurance claims. On their own these tables say very little. Together, inside a well-structured model, they show how a healthcare organization is really performing.

This project brings all of these datasets into a star-schema data model and presents them through a two-page Power BI report built for decision makers.

✨ What the solution helps stakeholders understand
<table> <tr> <td width="33%" valign="top">
🏥 Operations

🟦 Overall hospital performance<br/> 🟦 Patient & admission trends<br/> 🟦 Appointment & treatment activity<br/> 🟦 Hospital-wise bed occupancy

</td> <td width="33%" valign="top">
💰 Finance

🟩 Insurance claim distribution<br/> 🟩 Claim approval performance<br/> 🟩 Treatment cost by category<br/> 🟩 Claimed vs approved amounts

</td> <td width="33%" valign="top">
⭐ Experience

🟧 Patient ratings & feedback<br/> 🟧 Department-wise satisfaction<br/> 🟧 Hospital-to-hospital comparison<br/> 🟧 Year-wise movement of ratings

</td> </tr> </table>

[!TIP] 🎯 Primary goal: support data-driven decision-making and give clear visibility into healthcare operations.

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,12,20,24&height=4" width="100%" />
🎯 Project Objectives
🏥 MediCare
🧑 Patient Analytics
Distribution
Activity
🏥 Hospital Performance
Comparison
Multi-KPI view
🛏️ Admissions
Trends
Patterns
🛌 Bed Utilization
Occupancy
Availability
💵 Financial Analysis
Claim amount
Approved amount
🧾 Claim Management
Approved
Pending
Rejected
Partially approved
💊 Treatment Analysis
Cost by category
🖱️ Interactive Reporting
Slicers
Cross-filtering
	🎯 Objective	📝 Description
🟦	Patient Analytics	Monitor patient distribution and activity.
🟩	Hospital Performance	Compare performance across hospitals.
🟨	Admission Analysis	Understand admission trends and patterns over time.
🟧	Bed Utilization	Monitor hospital bed occupancy and availability.
🟥	Financial Analysis	Analyse claim amounts and approved amounts.
🟪	Claim Management	Track approved, pending, rejected and partially approved claims.
🟫	Treatment Analysis	Evaluate treatment costs by treatment category.
⬛	Interactive Reporting	Let users explore insights through slicers and cross-filtering visuals.
<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,12,20,24&height=4" width="100%" />
🛠️ Tools & Technologies
<div align="center"> <img src="https://img.shields.io/badge/Microsoft%20Fabric-0078D4?style=for-the-badge&logo=microsoft&logoColor=white" /> <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" /> <img src="https://img.shields.io/badge/DAX-512BD4?style=for-the-badge&logoColor=white" /> <img src="https://img.shields.io/badge/Power%20Query-00A4EF?style=for-the-badge&logoColor=white" /> <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" /> <img src="https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" /> </div>
	Technology	Purpose
🟦	Microsoft Fabric	Data engineering and lakehouse environment
🏠	Fabric Lakehouse & Notebooks	Medallion architecture (Bronze, Silver, Gold) with Spark SQL
🟨	Power BI	Interactive dashboard development
🔐	RLS, CLS & OLS	Row, column and object level security on the semantic model
🟪	DAX	Measures, calculations and KPIs
🔵	Power Query	Data transformation and preparation
🐬	SQL	Data querying and analysis
🔥	PySpark	Data processing and transformation
<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,12,20,24&height=4" width="100%" />
🏗️ Architecture & Workflow
🧪 GeneratedHealthcare Data
🔥 Spark SQL NotebooksMicrosoft Fabric
🏠 LakehouseTables
🧹 Power QueryTransformation
🧩 Star SchemaData Model
🧮 DAX Measures& KPIs
📊 Power BIDashboard
🪜 Step-by-step
Step		What happens
1	🧪	Generate data: create realistic synthetic healthcare datasets.
2	🔥	Process & store: build Bronze → Silver → Gold layers in a Fabric Lakehouse using Fabric Notebooks (Spark SQL).
3	🧹	Prepare: clean and shape the tables with Power Query.
4	🧩	Model: build fact and dimension tables with proper relationships.
5	🧮	Calculate: write DAX measures for every KPI.
6	📊	Visualize: design two polished report pages with slicers and cross-filtering.
<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,12,20,24&height=4" width="100%" />
🥉🥈🥇 Medallion Architecture
<div align="center"> <img src="https://img.shields.io/badge/🥉%20BRONZE-Raw%20Data-CD7F32?style=for-the-badge" /> <img src="https://img.shields.io/badge/➜-1E293B?style=for-the-badge" /> <img src="https://img.shields.io/badge/🥈%20SILVER-Cleaned%20Data-9CA3AF?style=for-the-badge" /> <img src="https://img.shields.io/badge/➜-1E293B?style=for-the-badge" /> <img src="https://img.shields.io/badge/🥇%20GOLD-Business%20Ready-EAB308?style=for-the-badge" /> </div>

[!IMPORTANT] The data is organised using the Medallion Architecture inside a Microsoft Fabric Lakehouse. Each layer is built with Fabric Notebooks (Spark SQL), so data becomes cleaner and more business-ready at every step.

🏠 Microsoft Fabric Lakehouse
Ingest
🔥 Notebook: clean &transform
🔥 Notebook: model &aggregate
🧪 GeneratedHealthcare Data
🥉 BRONZERaw data as ingested
🥈 SILVERCleaned & standardised
🥇 GOLDStar schema, business-ready
🧩 Semantic Model+ DAX Measures
📊 Power BIDashboards
🧱 Layer-by-Layer
	Layer	🎯 Purpose	🔧 What happens in the notebook	📦 Output
🥉	Bronze	Store data exactly as received	Load source files into the Lakehouse with minimal changes, keep the original structure	Raw Delta tables
🥈	Silver	Make data reliable	Remove duplicates, handle nulls, fix data types, standardise names and formats, validate records	Cleaned, conformed Delta tables
🥇	Gold	Make data useful for reporting	Build fact and dimension tables (star schema), join and aggregate, prepare for Power BI	Analytics-ready Fact & Dim tables
🥉 Bronze · Raw Layer
<table> <tr> <td width="55%" valign="top">
📥 Ingests the generated healthcare datasets into the Lakehouse
🗃️ Keeps data as-is for traceability and reprocessing
💾 Stored as Delta tables for reliability
🧾 Covers all ten source tables: Patients, Hospitals, Departments, Doctors, Admissions, Appointments, Treatments, Insurance Claims, Bed Utilization, Patient Feedback
</td> <td width="45%" valign="top"> <img src="https://img.shields.io/badge/Quality-Raw-CD7F32?style=flat-square" /> <img src="https://img.shields.io/badge/Format-Delta-0078D4?style=flat-square" /> <img src="https://img.shields.io/badge/Tool-Fabric%20Notebook-E25A1C?style=flat-square" /> </td> </tr> </table>
🥈 Silver · Cleaned Layer
<table> <tr> <td width="55%" valign="top">
🧹 Removes duplicate and invalid records
🔢 Corrects data types (dates, numbers, text)
🏷️ Standardises column names and values
✅ Applies data quality checks
🔗 Prepares tables so they can be joined reliably
</td> <td width="45%" valign="top"> <img src="https://img.shields.io/badge/Quality-Cleaned-9CA3AF?style=flat-square" /> <img src="https://img.shields.io/badge/Format-Delta-0078D4?style=flat-square" /> <img src="https://img.shields.io/badge/Tool-Spark%20SQL-E25A1C?style=flat-square" /> </td> </tr> </table>
🥇 Gold · Business Layer
<table> <tr> <td width="55%" valign="top">
🧩 Builds the star schema: 6 fact tables and 5 dimension tables
🔗 Defines keys used for relationships in the semantic model
📅 Creates the date dimension for time intelligence
📊 Feeds the Power BI report directly
</td> <td width="45%" valign="top"> <img src="https://img.shields.io/badge/Quality-Business%20Ready-EAB308?style=flat-square" /> <img src="https://img.shields.io/badge/Model-Star%20Schema-0D9488?style=flat-square" /> <img src="https://img.shields.io/badge/Consumer-Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" /> </td> </tr> </table> <details> <summary><b>🔥 Click to view sample Spark SQL pattern for each layer</b></summary>

[!TIP] Illustrative patterns only. Each block is one %%sql cell in a Fabric Notebook. Replace file paths, table names and column names with your own.

🥉 Bronze: load raw data

sql
%%sql
-- Cell 1: expose the raw file as a temporary view
CREATE OR REPLACE TEMPORARY VIEW raw_patients
USING CSV
OPTIONS (path 'Files/raw/patients.csv', header 'true', inferSchema 'true')
sql
%%sql
-- Cell 2: save it as a Delta table, no business changes
CREATE OR REPLACE TABLE bronze_patients
USING DELTA
AS
SELECT * FROM raw_patients

🥈 Silver: clean and standardise

sql
%%sql
-- Remove duplicates and nulls, fix data types, standardise text
CREATE OR REPLACE TABLE silver_patients
USING DELTA
AS
SELECT
    PatientID,
    INITCAP(TRIM(Gender))     AS Gender,
    TO_DATE(RegistrationDate) AS RegistrationDate
FROM (
    SELECT *,
           ROW_NUMBER() OVER (PARTITION BY PatientID ORDER BY RegistrationDate DESC) AS rn
    FROM bronze_patients
    WHERE PatientID IS NOT NULL
)
WHERE rn = 1

🥇 Gold: build the model tables

sql
%%sql
-- Dimension table for the star schema
CREATE OR REPLACE TABLE gold_dim_patient
USING DELTA
AS
SELECT PatientID, Gender, RegistrationDate
FROM silver_patients
sql
%%sql
-- Date dimension for time intelligence (adjust the date range)
CREATE OR REPLACE TABLE gold_dim_date
USING DELTA
AS
SELECT
    d                      AS Date,
    YEAR(d)                AS Year,
    MONTH(d)               AS MonthNumber,
    DATE_FORMAT(d, 'MMMM') AS MonthName
FROM (
    SELECT EXPLODE(SEQUENCE(DATE'2020-01-01', DATE'2025-12-31', INTERVAL 1 DAY)) AS d
)
</details>
✨ Why Medallion?
	Benefit	What it gives this project
🔁	Reprocessing	Raw data is always preserved in Bronze
🧼	Data quality	Issues are fixed once in Silver, not in every report
⚡	Performance	Gold tables are shaped for fast Power BI queries
🧩	Clear separation	Each layer has one job, which makes debugging easier
📈	Scalability	New tables or sources can be added layer by layer
<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,12,20,24&height=4" width="100%" />
📂 Dataset Overview

The project uses generated (synthetic) healthcare data covering the main areas of hospital operations.

🔢 Dataset at a Glance
<div align="center"> <img src="https://img.shields.io/badge/🧑%20Patients-25K%2B-0D9488?style=for-the-badge" /> <img src="https://img.shields.io/badge/📅%20Appointments-100K-3B82F6?style=for-the-badge" /> <img src="https://img.shields.io/badge/💊%20Treatments-75K-8B5CF6?style=for-the-badge" /> <br/> <img src="https://img.shields.io/badge/🧾%20Claims-40K-F59E0B?style=for-the-badge" /> <img src="https://img.shields.io/badge/🛏️%20Admissions-35K-EF4444?style=for-the-badge" /> <img src="https://img.shields.io/badge/⭐%20Feedback-25K-EC4899?style=for-the-badge" /> <img src="https://img.shields.io/badge/🏥%20Hospitals-8-16A34A?style=for-the-badge" /> </div>

[!NOTE] Record counts represent the generated project datasets and may vary after filtering or data cleaning.

📚 Main Tables
	📋 Table	📝 Description
🟦	Patients	Patient demographics and registration information
🟩	Hospitals	Hospital details and location information
🟨	Departments	Hospital department information
🟧	Doctors	Doctor details and specializations
🟥	Admissions	Patient admission and discharge records
🟪	Appointments	Appointment details and waiting times
🟫	Treatments	Treatment types and treatment costs
🔵	Insurance Claims	Insurance claim amounts and approval details
🟢	Bed Utilization	Total, occupied and available beds
🟡	Patient Feedback	Patient ratings and feedback categories
<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,12,20,24&height=4" width="100%" />
🧩 Data Model

The report follows a star schema: fact tables hold the measurable events, and dimension tables give the context used for slicing and filtering.

<table> <tr> <td width="50%" valign="top">
🟧 Fact Tables
Table	Captures
Fact Admissions	Admission & discharge events
Fact Appointments	Appointments & waiting times
Fact Treatments	Treatment types & costs
Fact Insurance Claims	Claimed/approved amounts, status
Fact Bed Utilization	Total, occupied, available beds
Fact Patient Feedback	Ratings & feedback categories
</td> <td width="50%" valign="top">
🟩 Dimension Tables
Table	Role
Dim Patient	Who received care
Dim Hospital	Where care was delivered
Dim Department	Which department
Dim Doctor	Who provided care
Dim Date	When it happened
</td> </tr> </table>
🧑 Dim Patient
🏥 Dim Hospital
🏢 Dim Department
👨‍⚕️ Dim Doctor
📅 Dim Date
🛏️ Fact Admissions
📅 Fact Appointments
💊 Fact Treatments
🧾 Fact Insurance Claims
🛌 Fact Bed Utilization
⭐ Fact Patient Feedback

[!IMPORTANT] 🔗 The model is built for one-to-many relationships and smooth cross-filtering between related healthcare entities.

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,12,20,24&height=4" width="100%" />
🔐 Data Security (RLS, CLS, OLS)
<div align="center"> <img src="https://img.shields.io/badge/🧑‍💼%20RLS-Row%20Level%20Security-0D9488?style=for-the-badge" /> <img src="https://img.shields.io/badge/🏛️%20CLS-Column%20Level%20Security-8B5CF6?style=for-the-badge" /> <img src="https://img.shields.io/badge/🗂️%20OLS-Object%20Level%20Security-EF4444?style=for-the-badge" /> </div>

[!IMPORTANT] Healthcare data is sensitive by nature. MediCare applies three layers of security so each user sees only the data they are allowed to see.

	🔒 Security	📖 What it controls	🧪 Example in MediCare
🟦	RLS · Row Level	Which rows a user can see	A hospital manager sees only their own hospital's patients, admissions and claims
🟪	CLS · Column Level	Which columns a user can see	Sensitive columns such as patient identifiers or claim amounts are hidden from roles that don't need them
🟥	OLS · Object Level	Which tables or columns exist for a user	The financial claims table is completely hidden from non-finance roles
👤 User signs in
🎭 Assigned Role
🟥 OLSWhich tables / objects?
🟪 CLSWhich columns?
🟦 RLSWhich rows?
📊 PersonalisedReport View
🎭 Example Role Design

[!TIP] Illustrative roles. Edit this table to match the roles you actually created.

	🎭 Role	🟦 RLS (rows)	🟪 CLS (columns)	🟥 OLS (tables)
🟩	Executive	All hospitals	All columns	All tables
🟨	Hospital Manager	Own hospital only	Limited sensitive columns	Operational tables
🟧	Finance Analyst	All hospitals	Claim and cost columns visible	Claims & treatment tables visible
🟥	Department Viewer	Own department only	Sensitive columns hidden	Financial tables hidden
<details> <summary><b>🧮 Click to view a sample RLS rule (DAX)</b></summary>

[!NOTE] Defined in Power BI Desktop under Modeling → Manage roles. The filter is applied on a dimension table and flows to the related fact tables through the relationships.

DAX
-- Role: Hospital Manager A
-- Table filter on 'Dim Hospital'
'Dim Hospital'[HospitalName] = "Your Hospital Name"

For dynamic security, a mapping table of user emails and hospitals can be used together with USERPRINCIPALNAME().

</details> <details> <summary><b>🛠️ How CLS and OLS are configured</b></summary>
RLS is created in Power BI Desktop (Manage roles) and users are assigned to roles in the Power BI Service.
CLS and OLS are set on the semantic model's roles, using external tooling such as Tabular Editor.
Always validate with View as role before publishing.
</details>

[!WARNING] Security roles apply to report viewers. Workspace Admins, Members and Contributors, and anyone with edit access to the semantic model, are not restricted by RLS. Share the report with viewers through an app or Viewer access.

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,12,20,24&height=4" width="100%" />
📊 Dashboard Overview

The MediCare report is organized into two analytical pages.

<table> <tr> <td width="50%" valign="top">
🏠 Page 1 · Executive Overview
<img src="https://img.shields.io/badge/Focus-Operations-0D9488?style=flat-square" />

A high-level command center for hospital operations and performance.

🟦 KPI Cards

Total Patients
Total Admissions
Total Appointments
Total Treatments
Average Patient Rating

🟩 Visuals

Admission Trends
Hospital-wise Bed Occupancy Rate
Hospital Comparison

🟧 Slicers

Year · Hospital Name
Department Name
Insurance Type · Hospital Type
</td> <td width="50%" valign="top">
💰 Page 2 · Financial & Claims
<img src="https://img.shields.io/badge/Focus-Finance-F59E0B?style=flat-square" />

A focused view of claim performance and treatment costs.

🟦 KPI Cards

Total Claim Amount
Approved Amount
Total Treatment Cost
Claim Approval Rate

🟩 Visuals

Claims by Status
Claim Amount vs Approved Amount
Monthly Claim Trends
Treatment Cost by Treatment Type
Claim Status Summary

🟧 Slicers

Year · Month Name
Claim Status · Treatment Type
</td> </tr> </table> <img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,12,20,24&height=4" width="100%" />
📸 Visuals

Explore the screenshots of the MediCare Healthcare Analytics Dashboard:

🏠 View Executive Overview
💰 View Financial & Claims Analysis
<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,12,20,24&height=4" width="100%" />
📈 Key Performance Indicators
<div align="center"> <img src="https://img.shields.io/badge/🧑%20Total%20Patients-Executive-0D9488?style=for-the-badge" /> <img src="https://img.shields.io/badge/🛏️%20Total%20Admissions-Executive-3B82F6?style=for-the-badge" /> <img src="https://img.shields.io/badge/📅%20Appointments-Executive-8B5CF6?style=for-the-badge" /> <br/> <img src="https://img.shields.io/badge/💊%20Treatments-Executive-EC4899?style=for-the-badge" /> <img src="https://img.shields.io/badge/⭐%20Avg%20Rating-Executive-F59E0B?style=for-the-badge" /> <img src="https://img.shields.io/badge/🛌%20Bed%20Occupancy-Executive-16A34A?style=for-the-badge" /> <br/> <img src="https://img.shields.io/badge/💵%20Claim%20Amount-Financial-EF4444?style=for-the-badge" /> <img src="https://img.shields.io/badge/✅%20Approved%20Amount-Financial-14B8A6?style=for-the-badge" /> <img src="https://img.shields.io/badge/📊%20Approval%20Rate-Financial-F97316?style=for-the-badge" /> <img src="https://img.shields.io/badge/🏷️%20Treatment%20Cost-Financial-6366F1?style=for-the-badge" /> </div> <br/>
	📌 KPI	🎯 Business Purpose	📄 Page
🟦	Total Patients	Measures the overall patient population	🏠 Executive
🟦	Total Admissions	Tracks hospital admission activity	🏠 Executive
🟦	Total Appointments	Measures appointment volume	🏠 Executive
🟦	Total Treatments	Tracks treatment activity	🏠 Executive
🟨	Average Rating	Measures patient satisfaction	🏠 Executive
🟩	Bed Occupancy Rate	Evaluates hospital bed utilization	🏠 Executive
🟥	Total Claim Amount	Total value of insurance claims	💰 Financial
🟥	Approved Amount	Amount approved by insurers	💰 Financial
🟧	Claim Approval Rate	Proportion of approved claims	💰 Financial
🟪	Total Treatment Cost	Evaluates treatment-related costs	💰 Financial
<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,12,20,24&height=4" width="100%" />
🧮 Sample DAX Measures

[!TIP] Example patterns for the KPIs above. Adjust table and column names to match your model.

<details open> <summary><b>🟦 Executive Overview measures</b></summary>
DAX
Total Patients = DISTINCTCOUNT ( 'Dim Patient'[PatientID] )

Total Admissions = COUNTROWS ( 'Fact Admissions' )

Average Rating = AVERAGE ( 'Fact Patient Feedback'[Rating] )

Bed Occupancy Rate % =
DIVIDE (
    SUM ( 'Fact Bed Utilization'[OccupiedBeds] ),
    SUM ( 'Fact Bed Utilization'[TotalBeds] )
)
</details> <details open> <summary><b>🟧 Financial & Claims measures</b></summary>
DAX
Total Claim Amount = SUM ( 'Fact Insurance Claims'[ClaimAmount] )

Approved Amount = SUM ( 'Fact Insurance Claims'[ApprovedAmount] )

Claim Approval Rate % =
DIVIDE (
    CALCULATE (
        COUNTROWS ( 'Fact Insurance Claims' ),
        'Fact Insurance Claims'[ClaimStatus] = "Approved"
    ),
    COUNTROWS ( 'Fact Insurance Claims' )
)

Total Treatment Cost = SUM ( 'Fact Treatments'[TreatmentCost] )
</details> <img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,12,20,24&height=4" width="100%" />
💡 Key Business Insights

The dashboard helps answer questions like these:

#	❓ Question	📄 Where to find it
1️⃣	Which hospital has the highest patient volume?	🏠 Executive
2️⃣	How do admissions change over time?	🏠 Executive
3️⃣	Which hospital has the highest bed occupancy rate?	🏠 Executive
4️⃣	Which hospitals have comparatively higher admission activity?	🏠 Executive
5️⃣	What proportion of claims are approved, pending or rejected?	💰 Financial
6️⃣	How does the approved amount compare with the total claim amount?	💰 Financial
7️⃣	Which treatment category contributes the highest treatment cost?	💰 Financial
8️⃣	How do claim amounts change across different months?	💰 Financial
9️⃣	How does patient feedback vary across departments?	🏠 Executive
🔟	How can hospital performance be compared using multiple KPIs?	🏠💰 Both
<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,12,20,24&height=4" width="100%" />
🎨 Design & UX Highlights
	Feature	Why it matters
🎛️	Slicer-driven exploration	Filter by year, hospital, department, insurance type, claim status and more.
🔄	Cross-filtering visuals	Click any chart element to update the rest of the page.
🧭	Two-page storytelling	Operations first, finance second.
🎨	Consistent healthcare theme	Teal-based palette with KPI cards for quick scanning.
🧱	Reusable star-schema model	Easy to extend with new facts or dimensions.
<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,12,20,24&height=4" width="100%" />
📁 Project Structure
text
MediCare-Healthcare-Analytics/
│
├── 📊 Dashboard/
│   └── MediCare_Dashboard.pbix
│
├── 🖼️ Screenshots/
│   ├── Executive_Overview.png
│   └── Financial_Claims_Analysis.png
│
├── 📂 Data/
│   └── Dataset_Information.md
│
├── 🐬 SQL/
│   └── SQL_Queries.sql
│
├── 🔥 Notebooks/
│   └── Data_Transformation_Notebooks/
│
└── 📘 README.md

[!NOTE] Include only the folders and files that are actually available in your repository.

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,12,20,24&height=4" width="100%" />
🚀 How to Use
<table> <tr> <td align="center" width="14%">📥<br/><b>1</b><br/>Clone / download the repo</td> <td align="center" width="14%">📂<br/><b>2</b><br/>Open the <code>Dashboard</code> folder</td> <td align="center" width="14%">⬇️<br/><b>3</b><br/>Download the <code>.pbix</code> file</td> <td align="center" width="14%">💻<br/><b>4</b><br/>Open in Power BI Desktop</td> <td align="center" width="14%">🏠<br/><b>5</b><br/>Explore Executive Overview</td> <td align="center" width="14%">💰<br/><b>6</b><br/>Go to Financial & Claims</td> <td align="center" width="14%">🎛️<br/><b>7</b><br/>Use slicers to analyse</td> </tr> </table>
bash
git clone https://github.com/harsh-mish/MediCare-Healthcare-Analytics.git

[!WARNING] If your report uses external data sources or a Fabric workspace, those connections may need to be configured in your own environment.

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,12,20,24&height=4" width="100%" />
📚 Skills Demonstrated
<div align="center"> <img src="https://img.shields.io/badge/Medallion%20Architecture-CD7F32?style=for-the-badge" /> <img src="https://img.shields.io/badge/RLS%20%7C%20CLS%20%7C%20OLS-EF4444?style=for-the-badge" /> <img src="https://img.shields.io/badge/Data%20Modeling-0D9488?style=for-the-badge" /> <img src="https://img.shields.io/badge/DAX-512BD4?style=for-the-badge" /> <img src="https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" /> <img src="https://img.shields.io/badge/Power%20Query-00A4EF?style=for-the-badge" /> <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" /> <img src="https://img.shields.io/badge/Dashboard%20Design-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" /> <img src="https://img.shields.io/badge/Healthcare%20Domain-EC4899?style=for-the-badge" /> </div> <br/>
	🧠 Area	🔧 What this project shows
🟦	Data Modeling	Star schema, fact/dimension design, relationships
🟪	DAX	KPI measures, ratios, filter context
🟧	Data Engineering	Spark SQL transformations in a Fabric Lakehouse
🔵	Power Query	Cleaning and shaping data
🐬	SQL	Querying and validating data
🟨	Dashboard Design	Layout, slicers, storytelling, UX
🟥	Domain Thinking	Healthcare operations and insurance analytics
<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,12,20,24&height=4" width="100%" />
🔮 Future Enhancements
 🏥 Additional hospital operational analytics
 👨‍⚕️ Doctor performance analysis
 ⭐ Advanced patient satisfaction analysis
 🧾 More detailed insurance claim monitoring
 ⚡ Real-time healthcare data integration
 🤖 Advanced predictive analytics
 🔎 Enhanced drill-through reporting
<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,12,20,24&height=4" width="100%" />
⚠️ Disclaimer

[!CAUTION] This project is developed for educational, portfolio and analytical demonstration purposes.

The healthcare dataset is generated/synthetic and does not represent actual patients, hospitals, medical records or insurance transactions.

The dashboard is not intended for clinical diagnosis, medical treatment decisions or real-world financial decisions.

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,12,20,24&height=4" width="100%" />
👨‍💻 Author
<div align="center">
Abhishek Mishra

Computer Science Engineering Graduate · Data Analytics · Data Engineering

<a href="https://github.com/harsh-mish"> <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /> </a>

Turning data into insights and insights into better decisions. 💡

<br/>
🏥 MediCare · Better Health. Brighter Tomorrow.

Thank you for exploring this project!

⭐ If you find it useful, consider giving the repository a star.

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20,24&height=140&section=footer" width="100%" /> </div>
