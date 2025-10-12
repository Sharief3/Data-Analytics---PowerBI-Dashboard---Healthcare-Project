# Papolla Health Care

## Project Objective
   - To build an end-to-end power BI dashboard using the polo health care dataset
   - To analyse and visualize specific client requirement, including patient data, billing information, bed accupancy, and doctor feedback 

## Data Set Used
<a href=" past it link ">Data set</a>

## The setup(Questions)
- Patient info according to patient_Id
- Billing information
- Bed accupancy breakdown
- Overall feedback for Doctor
- Diagnosis -Wise stats
- Billing vs Insurance stats

## Process


1.  **Review Data and Define Requirements:** The process began by reviewing the available Polo Health Care dataset columns (such as Patient ID, Admit Date, Diagnosis, Billing Amount, etc.) and noting the specific requirements provided by the client (such as displaying Patient Info, Billing Info, Bed Occupancy, and Doctor Feedback)
2.  **Sketch a Blueprint (Layout Planning):** A rough sketch or blueprint was created to ideate and visualize the dashboard layout, determining which elements should appear prominently (like Patient ID slicers and key dates/amounts at the top) and which analyses (graphs) should appear below 
3.  **Connect and Transform Data:**
    *   The Google Sheets dataset link was copied and connected to Power BI using the Get Data function 
    *   The Power Query Editor was utilized to transform the data 
    *   The first row was promoted to be used as column headers 
    *   Data types for all columns were checked and set correctly (e.g., dates for dates, text for diagnosis, numeric/integer for amounts) 
4.  **Set Up Dashboard Canvas:** The data was loaded , and the visual layout was configured by setting a pre-designed template image as the Canvas Background, setting the transparency to zero, and fitting the image.
5.  **Build Core Filtering and Key Metrics:**
    *   A **Patient ID Slicer** was inserted and configured as a dropdown menu for selecting individual patient data 
    *   **Card visuals** were created to display key patient information upon selection: Admit Date, Discharge Date, Follow Up Date, and Bill Amount 
    *   The Billing Amount visual was formatted to display units in Millions (M) and currency in Indian Rupees (₹) 
    *   A second Slicer was added to control the overall **Date Range** based on the Admit Date 
6.  **Create Analytical Visualizations:** The remaining client requirements were fulfilled by building specific charts and formatting them according to the dashboard theme:
    *   A **Column Chart** was used to show the **Bed Occupancy Breakdown** (Private, General, ICU) 
    *   A **Donut Chart** was used to visualize the **Doctor Feedback/Ratings** 
    *   A **Funnel Chart** was used to show **Diagnosis-wise Stats**, highlighting the trend of the most common illnesses 
    *   A **Line Chart** was used to show the **Billing Amount versus Health Insurance Amount** comparison, typically using the Diagnosis Type on the X-axis for context

## Dashboard 
https://github.com/Sharief3/Data-Analytics---PowerBI-Dashboard---Healthcare-Project/blob/main/Dashboard.png

## Project Insights

### 1. Patient-Specific Tracking (The Basics)
The most immediate insight is the ability to instantly pull up crucial details for **any single patient** by selecting their ID

*   **Key Dates:** Quickly identify when a patient was **Admitted, Discharged**, and when their **Follow Up Date** is scheduled
*   **Total Cost:** See the patient's **total Bill Amount** right away 

### 2. Resource Utilization
The dashboard tracks how hospital resources are being used:

*   **Bed Type:** Shows the **count of patients** across different types of bed occupancy, such as **Private, General, and ICU**, using a Column Chart 

### 3. Service Quality
Insights into service quality are provided:

*   **Doctor Ratings:** Displays the **overall feedback/ratings for doctors** (out of five) using a Donut Chart

### 4. Medical Trends
The analysis reveals common health issues:

*   **Diagnosis Trends:** A Funnel Chart shows the distribution and **trend of different illnesses** (e.g., Viral Infection, Typhoid, Malaria), helping identify the most common diagnoses among patients [4, 8, 9].

### 5. Financial Analysis
The project compares costs and coverage:

*   **Cost Gap:** Compares the **Billing Amount versus the Health Insurance Amount** using a Line Chart [10, 11]. This helps visualize the difference in total cost versus coverage across various diagnosis types [9, 12].

## Conclusion
The conclusion of the project is the successful development and deployment of a comprehensive, interactive Power BI dashboard focused on healthcare data.

In simple terms, the project concluded with:

1.  **A Functional, Interactive Dashboard:** A high-quality Power BI dashboard was built using the Polo Health Care dataset, fulfilling all required client specifications
2.  **Immediate Patient Insight:** The dashboard provides the capability to instantly pull up crucial details for any single patient, including their **Admit Date, Discharge Date, Follow Up Date, and total Bill Amount** 
3.  **Operational and Financial Clarity:** The final product offers clear visualization of key metrics, such as the breakdown of **Bed Occupancy** (Private, General, ICU), **Doctor Feedback/Ratings**, **Diagnosis Trends** (e.g., Viral Infection, Typhoid), and a crucial comparison chart showing the **Billing Amount versus the Health Insurance Amount** across different diagnoses 
4.  **Portfolio Readiness:** The resulting interactive dashboard is **published GitHub 