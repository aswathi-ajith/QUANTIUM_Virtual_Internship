![image](https://github.com/user-attachments/assets/d14934a7-ef35-47d3-a0ed-cc389cb7997a)

# Quantium Data Analytics Virtual Experience Program

## The virtual internship consists of three tasks:

## Task - 1 : **Retail Analytics for Chips Category**

### **Objective**
This project aims to analyze customer and transaction data to understand purchasing behavior in the chips category and provide strategic recommendations for the supermarket's category review. The insights will guide the chips category's strategic plan for the next six months.

---

### **Project Overview**

#### **1. Data Cleaning and Preparation**
- **Transaction Data:**  
  - Identified and addressed inconsistencies, missing data, and outliers.
  - Verified proper categorization of items and ensured correct formatting of numeric fields.

- **Customer Data:**  
  - Checked for missing values and resolved anomalies.

- **Merged Dataset:**  
  - Combined cleaned transaction and customer data for analysis.
  - Derived additional features such as:
    - **Pack size**
    - **Brand name**

---

#### **2. Data Analysis and Metrics**
- **Key Metrics Defined:**
  - Total sales.
  - Drivers of sales.
  - Customer spending patterns.
  - Regional and segment-based sales trends.

- **Analysis Goals:**
  - Understand who spends on chips and what drives their purchases.
  - Explore data trends using visualizations (charts and graphs).
  - Identify segments and regions with the highest sales.

---

#### **3. Customer Segmentation and Insights**
- Segmentation based on customer spending and purchasing behavior.
- Analysis of key factors such as:
  - Preferred pack sizes.
  - Popular brands.
  - Spending drivers for each segment.

- Insights will inform recommendations on:
  - Target customer segments.
  - Strategies to enhance sales and engagement.

---

#### **4. Strategic Recommendations**
- Develop actionable recommendations with a commercial focus, leveraging the analysis findings.
- Provide insights to guide the chips category's performance improvement in the next review cycle.

---

#### **Deliverables**
1. **Cleaned Data Files:** Saved as `.csv` for reference.
2. **Visualizations:** Key charts and graphs summarizing findings.
3. **Code:** Documented and saved as a `.pdf` file.
4. **Insights and Recommendations:** Ready for integration into the category review report.

---

#### **Tools and Approach**
- **Preferred Tools:**  
  - **Python** due to the data size and complexity.
  
- **Steps Taken:**
  - High-level data checks: Summarizing, detecting outliers, correcting formats.
  - Merging datasets and deriving features for deeper insights.
  - Visualizing data to uncover purchasing trends and behaviors.

---

## Task - 2 : Experimentation and Uplift Testing


### **Objective**
This project evaluates the performance of trial store layouts in stores 77, 86, and 88 compared to control stores. The goal is to provide a data-driven recommendation on whether the trial layout should be rolled out to all stores.

---

### **Project Overview**

#### **1. Control Store Selection**

- **Objective:** Identify suitable control stores for each trial store to serve as a benchmark.
- **Approach:** 
  - Defined metrics for control store selection based on similarity to trial stores.
  - Explored drivers such as:
    - Total sales revenue.
    - Number of customers.
    - Average transactions per customer.
  - Used statistical measures like Pearson correlation or magnitude distance to quantify similarity.
  - Developed a reusable function for efficient control store selection.

- **Control Store Matches:**
  - **Trial store 77:** Control store 233.
  - **Trial store 86:** Control store 155.
  - **Trial store 88:** Control store 40.

---

#### **2. Assessment of the Trial**
- **Comparison Metrics:**
  - Total sales revenue.
  - Total number of customers.
  - Average transactions per customer.

- **Steps:**
  - Analyzed each trial store individually, comparing their performance to the respective control store during the trial period (Feb-Apr).
  - Assessed whether changes in trial store performance were statistically significant.
  - Investigated the drivers of change (e.g., more customers or higher purchases per customer).

- **Key Insights:**
  - **Trial store 77:** Sales for Feb, March, and April exceeded the 95% threshold compared to the control store.
  - **Trial store 86:** Sales for all three trial months exceeded the 95% threshold.
  - **Trial store 88:** No significant increase in sales or number of customers during the trial period.

---

#### **3. Findings and Recommendations**
- **Trial Stores 77 and 86:**
  - Showed significant increases in total sales and number of customers during the trial period.
  - Positive impact suggests potential for rolling out the new layout to similar stores.

- **Trial Store 88:**
  - Did not demonstrate a significant increase in sales or customers.
  - Further analysis is required to determine the factors limiting its performance.

---

#### **Conclusion**
- **Summary of Results:**
  - Trial store 77: Control store 233.
  - Trial store 86: Control store 155.
  - Trial store 88: Control store 40.
  - Trial stores 77 and 86 exhibited significant positive results in total sales and customer numbers.
  - Overall, the trial showed positive significant results, indicating the new layout's potential effectiveness for most stores.

---

#### **Deliverables**
1. **Cleaned Data Files:** Saved as `.csv` for reference.
2. **Codebase:** Documented and saved as a `.pdf` file.
3. **Visualizations:** Graphs and charts summarizing trial vs. control performance.
4. **Insights and Recommendations:** Summarized for client review.

---




