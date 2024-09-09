# Food Regulations Data Visualization Project

## **Objective**

The goal of this project is to create a Tableau dashboard that provides insights into global food safety and waste management regulations. The analysis focuses on understanding the distribution, frequency, and trends of regulations across different countries to help policymakers and businesses optimize food management strategies.

## **Business Problem**

Food waste and food safety are major global concerns. Governments worldwide introduce and amend regulations to address these issues. However, businesses and policymakers often lack a comprehensive view of these regulations, making it difficult to compare countries and identify gaps. This dashboard aims to:

- **Analyze** which countries have the most regulations on food safety and waste management.
- **Track** regulatory trends over time.
- **Highlight** areas that may need more focus or improvement based on the volume and type of regulations.

## **KPIs**

- **Number of Regulations per Country**: Identify which countries are most active in food safety and waste management regulation.
- **Time Between Original Regulation and Last Amendment**: Track how often regulations are updated or amended.
- **Keyword Focus**: Categorize regulations based on keywords (e.g., "food safety," "waste management") to understand focus areas by region.
- **Regulation Type by Country**: Compare regulation types (policies, laws, amendments) across countries to identify proactive regions.

## **Data Cleaning and Preparation**

### **Step 1: Load the Dataset**

Load the dataset into a Pandas DataFrame for cleaning. The CSV file contains columns such as country, regulation type, date of original text, and keywords.

### **Step 2: Handle Missing Data**

Check for missing values and clean the dataset by filling or removing empty values.

### **Step 3: Parse Dates**

Ensure the date fields are properly formatted for time-based analysis.

### **Step 4: Extract Additional Information**

For better analysis, extract additional features such as the year of regulation and the time between the original text and the last amendment.

### **Step 5: Export Cleaned Data for Tableau**

Export the cleaned dataset as a CSV file for use in Tableau.

## **Tableau Visualization Steps**

### **Step 1: Import the Cleaned Dataset**

Open Tableau and load the `Cleaned_Food_Regulations.csv` file. Review the dataset schema, ensuring all fields are appropriately typed (especially the date fields).

### **Step 2: Create Key Visualizations**

- **Top 10 Countries by Food Regulation Activity:**
  - **Chart Type:** Horizontal Bar Chart
  - **Data:** Show the top 10 countries with the highest number of regulations
  - **Insights:** Identifying the most active countries in regulating food safety and waste management.

- **Global Food Regulations by Country:**
  - **Chart Type:** Filled Map
  - **Data:** Plot the number of regulations per country
  - **Insights:** Visualizing the distribution of regulations across different countries.

- **Annual Trends in Food Regulations:**
  - **Chart Type:** Bar Chart
  - **Data:** Count of regulations by year (use the Year field)
  - **Insights:** Analyzing the evolution of food regulations over the years.

- **Regulation Type Distribution by Country:**
  - **Chart Type:** Pie Chart or Stacked Bar Chart
  - **Data:** Compare regulation types (policies, laws, amendments) across countries
  - **Insights:** Breaking down the types of regulations by country.

### **Step 3: Design the Dashboard**

Combine all visualizations into a single interactive dashboard. Add filters for country and year, allowing users to explore regulations by specific regions and timeframes. Include KPIs at the top, such as "Total Number of Regulations" and "Average Amendment Lag."

## **Real-World Application**

This dashboard can help:

- **Food Businesses:** Track and comply with regulations in countries where they operate, identifying regions with stricter or evolving laws.
- **Policymakers:** Understand gaps in their regulatory environment by benchmarking their country against others, and track the effectiveness of existing regulations over time.
- **NGOs and Researchers:** Focus advocacy efforts on regions that have less regulatory focus on food safety and waste management, helping reduce global food waste.

## **Conclusion**

This project bridges the gap between data visualization and regulatory analysis. By transforming raw data into meaningful insights, businesses and policymakers can make more informed decisions to address global food safety and waste management challenges.
