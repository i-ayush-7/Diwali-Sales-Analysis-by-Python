# Diwali-Sales-Analysis-by-Python

The Jupyter Notebook file performs an exploratory data analysis (EDA) of Diwali Sales Data.

## Data Preparation and Cleaning:
1. The data was loaded into a pandas DataFrame named df.
2. The DataFrame initially contained 11,251 rows and 15 columns.
3. Two columns, 'Status' and 'unnamed1', were found to be entirely null (0 non-null counts) and were subsequently dropped.
4. The remaining data had 12 null values in the 'Amount' column.
5. These 12 rows with null values were dropped using dropna(), resulting in 11,239 rows for analysis.
6. The data type of the 'Amount' column was successfully changed from float to integer (int64).
7. One column, 'Marital_Status', was temporarily renamed to 'Shaadi' (though the descriptive statistics show the original name, implying the change was not made in-place for all subsequent uses).
8. Descriptive statistics were generated for numerical columns like 'Age', 'Orders', and 'Amount'.

## Exploratory Data Analysis (EDA) Insights:
The analysis primarily focused on identifying key customer segments and popular product categories by looking at the count of buyers and the total sales amount.

### Analysis by Gender
1. Most buyers are females (approx. 7,800) compared to males (approx. 3,400). Females have a much greater purchasing power (Total Amount: 74,335,853) than males (Total Amount: 31,913,276).

### Analysis by Age Group
1. The 26-35 age group has the highest number of buyers and the largest total sales amount.

2. Within this most active group (26-35), females are the dominant buyers. The total sales amount also confirms that the 26-35 age group generates the highest revenue.

### Analysis by State
1. The top 3 states contributing to the total number of orders are Uttar Pradesh, Maharashtra, and Karnataka. * These same top 3 states also account for the highest total sales/amount: Uttar Pradesh, Maharashtra, and Karnataka.

### Analysis by Marital Status
1. Married individuals (Marital_Status = 1) are the largest group of buyers by count and also have the highest total purchasing power.

2. The analysis broken down by gender shows that married women are the key purchasers.

### Analysis by Occupation
1. The top 3 occupations in terms of number of buyers are IT Sector, Healthcare, and Aviation. * These top 3 occupations also contribute the most to total sales/amount.

### Analysis by Product Category and ID
1. The top 3 sold product categories by total sales amount are Food, Clothing & Apparel, and Electronics & Gadgets. * The top 10 most ordered products were also identified by their Product_ID.

## Conclusion:
The overall conclusion drawn from the analysis is that the target customers for marketing and sales efforts should be:

Demographics: Married women in the 26-35 age group.

Geography: Buyers from Uttar Pradesh, Maharashtra, and Karnataka.

Occupation: Individuals working in the IT, Healthcare, and Aviation sectors.

Product Focus: Products from the Food, Clothing, and Electronics categories.

## Project By: Ayush Shukla
