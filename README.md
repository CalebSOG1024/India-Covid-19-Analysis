# India COVID-19 2020 Analysis: Trends, Risks, and Public Health Implications; Building Interactive Excel Dashboard for Disease Prevention and Driving Healthcare Organization Forward.
### Description
This project involved cleaning and modeling large-scale COVID-19 case data — including confirmed cases, recoveries, deaths, and testing rates — across Indian states and union territories.
### Business Introduction
HealthIntel Analytics is a data-driven healthtech startup dedicated to researching and interpreting COVID-19 case trends developing in India during the critical year of 2020. The startup leverages public health datasets, epidemiological models, and machine learning to provide actionable insights for healthcare organizations, policy makers, and NGOs; her core mission is to empower India’s healthcare ecosystem with accurate, real-time insights on COVID-19 transmission, recovery, and mortality patterns—helping drive better resource allocation, response strategies, and health outcomes.
### Business Problem
In 2020, India faced a rapidly evolving COVID-19 crisis marked by significant regional disparities in infection spread, recovery rates, and mortality. However, many healthcare organizations were challenged by the lack of real-time analytics and actionable intelligence to support data-driven decisions. The absence of an integrated view into testing adequacy, hospital capacity, and high-risk zones limited the ability to respond effectively—especially in underserved states and rural areas. This gap highlighted the urgent need for predictive, scalable analytics platforms that translate raw data into strategic insights for better pandemic response and preparedness.
### Aim of This Project
The aim of this project is to develop a comprehensive, data-driven analytical framework that empowers healthcare organizations and government agencies in India to respond more effectively to the COVID-19 pandemic by delivering timely, accurate, and region-specific insights. The project seeks to integrate national and regional COVID-19 data—including case counts, testing rates, hospital capacity, mortality, and recovery trends—into an interactive and predictive dashboard by leveraging advanced analytics, visualizations, and trend analysis, the project will help identify emerging hotspots, evaluate healthcare readiness, and optimize the allocation of critical resources such as ICU beds, oxygen supplies, and medical personnel. Ultimately, the goal is to support proactive, evidence-based decision-making to reduce mortality, improve recovery rates, and ensure equitable healthcare response—particularly in underserved and high-risk areas.
### Processes
The processes employed in carrying out this project are:
1 Step 1: Data Cleaning and Transformation
- Inspected the Dataset
- Reviewed the rows and columns for structure, column headers, and data types.
- Identified missing values, duplicates, and inconsistent formats
- Removed Unnecessary Columns
- Deleted irrelevant or empty columns (e.g., unused identifiers, redundant notes).
- Renamed Column Headers
- Renamed column names to be clear, consistent, and analysis-ready, such as
- Confirmed Cases, Recovered, Deaths, Date, State/UT, etc.
- Handled Missing or Incomplete Data
- Used filter or Go To Special > Blanks to identify blanks
- Filled missing values using forward fill or calculated estimates (e.g., using averages)
- Removed rows with critical missing data
- Corrected Inconsistent Formats
- Ensured dates were in proper date format using DATEVALUE() or Text to Columns.
- Standardized text entries (e.g., Maharashtra vs. maharashtra) using PROPER() or UPPER() functions.
- Removed Duplicates to eliminate repeated rows based on key columns (e.g., Date + State).
