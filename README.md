# **Walmart-Black-Friday-Purchases-Data-Analysis**

## **Project Overview**

This project aims to analyze Walmart's Black Friday sales data by focusing on purchase patterns across different customer categories such as gender, age group, marital status, city category, and product categories. We utilized statistical methods like **Confidence Intervals (CI)** and **Bootstrap** to derive actionable insights into customer behavior.

## **Key Insights**

1. **Gender Spending**:
   - Males spend more than females:
     - Average Male Spend: \$925,408.28
     - Average Female Spend: \$712,217.18

2. **Age Group**:
   - Customers aged **25-40** represent over 80% of the highest spenders.

3. **Marital Status**:
   - Single men spend significantly more than married men during Black Friday sales.

4. **City Category**:
   - **City B** contributes the most to overall sales volume, but **City C** generates higher average purchase amounts.

5. **Product Categories**:
   - **Categories 6 and 15** are the highest value categories, while **categories 1, 5, 8, and 11** have the highest purchase frequencies.

## **Methodology**

- **Confidence Intervals (CI)**: Calculated for various demographic features like gender, marital status, and age groups.
- **Bootstrap Sampling**: Used to estimate confidence intervals for different categories.
- **Exploratory Data Analysis (EDA)**: Conducted to uncover purchase trends across multiple features.
### Why Bootstrap Instead of Z-Test or T-Test?
In this analysis, we chose to use Bootstrap rather than traditional parametric methods like the Z-test or T-test for several important reasons:

- No Assumption of Normality: Unlike Z or T-tests, Bootstrap doesn't assume the data is normally distributed, making it ideal for skewed sales data with outliers.
- Unknown Population Parameters: Bootstrap doesn't need population parameters (e.g., variance), allowing us to estimate statistics directly from the data.
- Flexibility with Sample Size: Bootstrap works for any sample size, while Z and T-tests have stricter size requirements.
- Robustness to Skewed Data: Given the variability in Black Friday purchases, Bootstrap is more robust in capturing the true distribution of the data.

By using Bootstrap, we ensure our analysis is robust, reliable, and does not rely on potentially incorrect assumptions about the underlying data distribution. 

## **Technologies Used**

- **Python**: For data analysis, statistical modeling, and visualizations.
- **Pandas**: For data manipulation and analysis.
- **Seaborn & Matplotlib**: For data visualization.
- **NumPy**: For numerical operations, including bootstrapping and confidence interval calculation.

## **Actionable Recommendations**

1. **Target Male Shoppers**: Males spend more, so tailor high-value product promotions towards this demographic.
2. **Single Men Focus**: Single men outspend married men, suggesting tailored offers for this group.
3. **Age-Based Marketing**: Promote premium products to older age groups (51+) who spend more.
4. **City-Specific Offers**: City C should be targeted with luxury items, while City B can benefit from volume-based promotions.
5. **Product Focus**: Highlight categories 6 and 15 in promotions and use bundling strategies for high-frequency purchase categories (1, 5, 8, 11).

## **Results**

The project provides valuable insights for marketing strategies, especially targeting key customer segments based on gender, age, marital status, and city category. The findings are useful for optimizing promotions and product offerings for future Black Friday sales.
