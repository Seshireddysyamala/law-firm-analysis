# Finance and Marketing Analysis for a Law Firm

This project showcases a comprehensive data analysis conducted on a law firm's financial and marketing data using Power BI. The analysis aims to extract actionable insights for improving profitability, client retention, and marketing strategies. This project also highlights data manipulation, visualization, and storytelling skills.

---

## 🛠 **Project Overview**
Law firms often face challenges in understanding the financial impact of their case types and client relationships. This project addresses these challenges by analyzing historical data related to revenue, investments, case types, and client contributions. By leveraging Power BI, this project provides dashboards and KPIs to support strategic decision-making.

### **Report Link**
[Interactive Power BI Dashboard](https://shorturl.at/Mt1M6)

### **Key Objectives**
1. **Financial Analysis**:
   - Identify high-revenue case types and clients.
   - Evaluate ROI across case types and investments.
   - Highlight trends in revenue and total investment over time.

2. **Marketing Analysis**:
   - Analyze client retention patterns.
   - Identify popular case types based on frequency and revenue contribution.
   - Showcase high-revenue clients and repeat clients.


---

## 📊 **Data Overview**
The dataset consists of case-related financial and marketing data, including:
- **Date**: The date of each transaction or case.
- **ClientID**: Unique identifier for each client.
- **ClientName**: Name of the client.
- **CaseType**: The type of legal case (e.g., Corporate, Intellectual Property).
- **CaseCount**: Number of cases handled.
- **Revenue**: Revenue generated from cases.
- **TotalInvestment**: Cost or investment incurred for each case.
- **YearMonth**: Aggregated year and month for trend analysis.

---

## 📈 **Key Insights and Findings**

### **Financial Insights**
1. **Revenue and Investment Trends**:
   - Revenue peaked in Q3 of 2012, with a noticeable dip in Q1 2013.
   - Total investment saw consistent growth, highlighting the need for better cost management.
2. **Profitability Analysis**:
   - **Top Performing Case Types**: Intellectual Property and Real Estate contributed the most to revenue and ROI.
   - **Top Clients**: Smith & Partners, Green & Partners, and Adams Legal are the most profitable clients.
3. **ROI Trends**:
   - The overall ROI across all case types is **2.36**, with Intellectual Property cases yielding the highest ROI of **3.1**.

### **Marketing Insights**
1. **Popular Case Types**:
   - Real Estate and Employment cases are the most frequent, contributing to 45% of total case volume.
2. **Client Retention**:
   - Total Clients: **15**
   - Repeat Clients: **5** (33% retention rate).
   - High-Revenue Clients: **4** contributed 60% of the firm's total revenue.
3. **Revenue Distribution**:
   - 70% of revenue comes from the top 5 clients, emphasizing the need for targeted retention strategies.

---

## 📊 **Power BI Dashboards**

### **Dashboard Highlights**
1. **Finance Dashboard**:
   - **Line Chart**: Tracks revenue, total investment, and profit trends over time.
   - **Bar Chart**: Compares revenue and ROI across case types.
   - **Scatter Plot**: Highlights profitability by client.
   - **Tree Map**: Visualizes revenue share by client.

2. **Marketing Dashboard**:
   - **Funnel Chart**: Shows client retention from total clients → repeat clients → high-revenue clients.
   - **Clustered Bar Chart**: Compares case count and revenue by case type.
   - **Line Chart**: Tracks monthly trends in case count.
   - **Pie Chart**: Visualizes case type popularity based on frequency.
### **Dashboard Highlights**
1. **Revenue and Total Investment Trends**:
   - **Visualization**: Line Chart
   - **Insights**: Tracks monthly revenue and investment trends, helping identify high-revenue periods and cost inefficiencies.

2. **Revenue by Case Type**:
   - **Visualization**: Bar Chart
   - **Insights**: Highlights case types like Intellectual Property and Real Estate as the top revenue generators.

3. **Profitability by Client**:
   - **Visualization**: Bar Chart
   - **Insights**: Compares revenue and profit by client, identifying high-value clients like **Smith & Partners**.

4. **ROI by Case Type**:
   - **Visualization**: Bar Chart
   - **Insights**: Evaluates ROI across case types, revealing Intellectual Property as the most cost-efficient service.

5. **Revenue Share by Client**:
   - **Visualization**: Pie Chart
   - **Insights**: Displays revenue distribution among clients, emphasizing reliance on top clients and opportunities for diversification.

6. **Case Count Trends by Month**:
   - **Visualization**: Line Chart
   - **Insights**: Tracks case volumes over time, helping with resource planning.

7. **Popular Cases by Type**:
   - **Visualization**: Clustered Bar Chart
   - **Insights**: Shows the frequency of cases by type. Real Estate is the most frequent case type, followed by Employment and Intellectual Property. These insights guide marketing and resource allocation to align with demand.

8. **Client Retention Analysis**:
   - **Visualization**: Funnel Chart
   - **Insights**: Analyzes client retention, highlighting that 33% of clients are repeat customers and 20% are high-revenue contributors.

---

## 📋 **KPIs (Key Performance Indicators)**

### **Finance KPIs**
- Total Revenue: **$9M**
- Total Investment: **$5M**
- Total Profit: **$4M**
- Average ROI: **2.36**

### **Marketing KPIs**
- Total Clients: **15**
- Repeat Clients: **5**
- High-Revenue Clients: **4**

---

## 🔧 **Technologies Used**
- **Power BI**:
  - For interactive dashboards and storytelling.
- **Power Query**:
  - Data transformation and cleaning.
- **DAX (Data Analysis Expressions)**:
  - Custom measures for ROI, profit, and high-revenue clients.
- **Excel**:
  - Initial exploration and dataset preprocessing.

---

## 🛠 **Key Features**
1. **Data Cleaning and Transformation**:
   - Missing values handled via median imputation.
   - New columns created for ROI and profit calculations.
2. **Custom DAX Measures**:
   - **ROI**: `(Revenue - TotalInvestment) / TotalInvestment`
   - **Profit**: `Revenue - TotalInvestment`
   - **High-Revenue Clients**: Top 20% clients based on revenue.
3. **Interactive Visuals**:
   - Slicers for `Year`, `CaseType`, and `ClientName`.
   - Tooltips to display additional insights for each visualization.

----

## 💡 **Actionable Recommendations**

### Financial Recommendations
1. Focus on case types with high ROI like Intellectual Property and Real Estate.
2. Optimize costs for low-ROI case types to improve profitability.
3. Invest more resources in high-revenue periods (e.g.,Q3).

### Marketing Recommendations
1. Retain high-revenue clients with personalized services to improve the **33% retention rate**.
2. Expand services in Real Estate and Employment case types to leverage popularity.
3. Focus on retaining top clients contributing 60% of the firm's revenue.
----
