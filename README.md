# Bike Sales Dashboard (Excel Project)

![Dashboard Preview](Dashboard_Screenshot.png)

## 📌 Project Overview
This project involves analyzing a dataset of bike buyers to identify trends and key demographics. The goal was to transform raw data into an interactive dashboard that helps stakeholders understand customer purchasing behavior based on age, income, commute distance, and car ownership.

## 📂 Data Source
* **Dataset:** Bike Buyers Dataset (Excel).
* **Description:** The dataset contains demographics and purchasing history of customers.
* **Key Fields:** ID, Marital Status, Gender, Income, Children, Education, Occupation, Home Owner, Cars, Commute Distance, Region, Age, Purchased Bike.

## 🛠️ Tools Used
* **Microsoft Excel:**
    * Data Cleaning & Processing
    * Pivot Tables & Pivot Charts
    * Slicers for interactivity
    * Dashboard Design

## 🧹 Data Cleaning & Preparation
Before analysis, the raw data underwent a cleaning process to ensure accuracy:
1.  **Removed Duplicates:** Checked for and removed duplicate customer records to ensure data integrity.
2.  **Standardized Values:**
    * Converted "M" and "S" in Marital Status to "Married" and "Single".
    * Converted "M" and "F" in Gender to "Male" and "Female".
3.  **Currency Formatting:** Applied currency formatting to the Income column to improve readability.
4.  **Age Brackets:** Created a nested `IF` formula to categorize customers into age groups:
    * **Adolescent:** < 31
    * **Middle Age:** 31 - 54
    * **Old:** 55+

## 📊 Key Insights & Analysis
The dashboard reveals several important trends influencing bike sales:

### 1. Income & Gender
* **Insight:** Males generally have a higher average income than females in this dataset.
* **Trend:** Higher income correlates positively with bike purchases for both genders, though the gap is more pronounced among male customers.

### 2. Age Demographics
* **Insight:** "Middle Age" (31-54) is the dominant age group for bike purchases.
* **Trend:** Sales drop significantly for the "Adolescent" and "Old" age brackets, suggesting marketing efforts should focus on the middle-aged demographic.

### 3. Commute Distance
* **Insight:** Customers with shorter commutes (0-1 Miles) are the most likely to buy a bike.
* **Trend:** As commute distance increases, the likelihood of purchasing a bike generally decreases, likely due to the feasibility of biking long distances.

### 4. Car Ownership
* **Insight:** There is an inverse relationship between car ownership and bike purchases.
* **Trend:** Customers with 0-1 cars are significantly more likely to buy a bike compared to those with 2 or more cars.

## 💡 Recommendations
Based on the analysis, the following actions are recommended:
* **Target Marketing:** Focus ad campaigns on middle-aged professionals with short commute distances.
* **Regional Strategy:** Utilize the Region slicer to tailor inventory based on specific regional preferences (Europe, North America, Pacific).
* **Pricing Strategy:** Since higher-income individuals are more likely to buy, consider premium models for that demographic while offering budget-friendly options for the younger/lower-income segments.

---
*Created by Buse Pek*
