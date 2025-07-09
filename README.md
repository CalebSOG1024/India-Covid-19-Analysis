# India COVID-19 2020 Analysis: Building Interactive Excel Dashboard for Disease Prevention and Driving Healthcare Organization Forward.
## Table Of Contents
- [Description](#description)
- [Business Introduction](#businessintroduction)
- [Business Problem](#businessproblem)
- [Aim of This Project](#aimofthisproject)
- [Processes](processes)
- [Insights](#insights)
- [Recommendations](#recommendations)

### Description
This project assesses the impact of Covid-19 in India during 2020 by identifying patterns in infection rates, recovery efficiency, and mortality distribution across states, in order to support public health decisions and response planning.

![India_Covid19_Analysis_Dashboard](https://github.com/user-attachments/assets/d2692a5e-a523-420b-bed8-32e94a83dd2c)

### Business Introduction
HealthIntel Analytics is a data-driven healthtech startup dedicated to researching and interpreting COVID-19 case trends developing in India during the critical year of 2020. The startup leverages public health datasets, epidemiological models, and machine learning to provide actionable insights for healthcare organizations, policy makers, and NGOs; her core mission is to empower India’s healthcare ecosystem with accurate, real-time insights on COVID-19 transmission, recovery, and mortality patterns—helping drive better resource allocation, response strategies, and health outcomes.

### Business Problem
In 2020, India faced a rapidly evolving COVID-19 crisis marked by significant regional disparities in infection spread, recovery rates, and mortality. However, many healthcare organizations were challenged by the lack of real-time analytics and actionable intelligence to support data-driven decisions. The absence of an integrated view into testing adequacy, hospital capacity, and high-risk zones limited the ability to respond effectively—especially in underserved states and rural areas. This gap highlighted the urgent need for predictive, scalable analytics platforms that translate raw data into strategic insights for better pandemic response and preparedness.

### Aim of This Project
The aim of this project is to develop a comprehensive, data-driven analytical framework that empowers healthcare organizations and government agencies in India to respond more effectively to the COVID-19 pandemic by delivering timely, accurate, and region-specific insights. The project seeks to integrate national and regional COVID-19 data—including case counts, testing rates, hospital capacity, mortality, and recovery trends—into an interactive and predictive dashboard by leveraging advanced analytics, visualizations, and trend analysis, the project will help identify emerging hotspots, evaluate healthcare readiness, and optimize the allocation of critical resources such as ICU beds, oxygen supplies, and medical personnel. Ultimately, the goal is to support proactive, evidence-based decision-making to reduce mortality, improve recovery rates, and ensure equitable healthcare response—particularly in underserved and high-risk areas.

### Processes
The processes employed in carrying out this project are:

Step 1: Data Cleaning and Transformation

 Tool: Excel Data Cleaning Features
   - Inspected the Dataset
   - Reviewed the rows and columns for structure, column headers, and data types.
   - Identified missing values, duplicates, and inconsistent formats
   - Removed Unnecessary Columns
   - Deleted irrelevant or empty columns (e.g., unused identifiers, redundant notes).
   - Renamed Column Headers
   - Renamed column names to be clear, consistent, and analysis-ready, such as Confirmed Cases, Recovered, Deaths, Date, State/UT, etc.
   - Handled Missing or Incomplete Data
   - Used filter or Go To Special > Blanks to identify blanks
   - Filled missing values using forward fill or calculated estimates (e.g., using averages)
   - Removed rows with critical missing data
   - Corrected Inconsistent Formats
   - Ensured dates were in proper date format using DATEVALUE() or Text to Columns.
   - Standardized text entries (e.g., Maharashtra vs. maharashtra) using PROPER() or UPPER() functions.
   - Removed Duplicates to eliminate repeated rows based on key columns (e.g., Date + State).

Step 2: Analysis and Dashboard Creation

 Tool: Pivot Tables and Slicers
    - Inserted my cleaned dataset into Pivot Tables
    - Created Key Pivot Tables
    - Added slicers for interactive filtering
### Insights
1  Time Series Trends
  - The recovery trends are: 232,063 in June, 139,507 in May, 30,657 in April, 1,269 in March, 2 in February and none in January.
  - The mortality trends are: 8,526 in June, 4,090 in May, 1,039 in April, 34 in March; With January and February having none.

2  State-wise Performance
  - The top 5 states by recovery rate are: Maharashtra at 125,907, Tamil Nadu at 58,619, Delhi at 57,570, Gujarat at 25,595 and Uttar Pradesh at 17,175; With Union Territory of Chandigarh having the least.
  - The top 5 states by mortality rate are: Maharashtra at 6,170, Delhi at 2,175, Gujarat at 1,663, Tamil Nadu at 757, and West Bengal at 555; With Mizoram having the least.

3  Overall Cases AnalysisMaharashtra had the overall confirmed cases of 132,077, recovered cases of 125,907 and death cases of 6,170.
  - Delhi had the overall confirmed cases of 59,745, recovered cases of 57,570 and death cases of 2,175.
  - Tamil Nadu had the overall confirmed cases of 59,376, recovered cases of 58,619 and death cases of 757; With Union Territory of Chandigarh having none.

### Recommendations
  - Medical facilities should be distributed evenly to the different states of the country.
  - Highly trained medical personnel should be allocated to the all health centers in the states.
  - Increase retention rate in high quality health-internship students to assist in the care of the casualties.
  - Social distancing and other good practices should be encouraged amongst the people.
