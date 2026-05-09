# 🛒 Purchase Frequency and Basket Size Analysis on Grocery Data

## 📌 Project Overview

This project performs an end-to-end exploratory data analysis (EDA) on a grocery shopping dataset to understand customer purchasing behavior, basket composition, shopping frequency, and product demand patterns.

The dataset contains 38,765 grocery transaction records across 3 features, including customer identifiers, transaction dates, and purchased grocery products.

The main objective is to identify:

- Customer shopping frequency behavior
- Basket size distribution patterns
- Most purchased grocery products
- Weekday shopping activity trends
- Product co-occurrence relationships
- Customer purchasing concentration
- Store management and operational insights

---

# 🧹 Data Cleaning

The following preprocessing steps were applied:

- Loaded the grocery transaction dataset using pandas
- Inspected dataset structure and verified data quality
- Checked missing values across all columns
- Verified data types for all variables
- Converted the Date column into datetime format
- Created basket-level transaction identifiers using Member_number and Date
- Validated basket construction for transaction-level analysis

---

# 📊 Exploratory Data Analysis

The analysis includes:

- Basket size analysis
- Purchase frequency analysis
- Customer segmentation based on visit frequency
- Product popularity analysis
- Weekday transaction behavior analysis
- Product co-occurrence analysis
- Top customer activity analysis
- Basket distribution analysis

---

# 🧺 Basket Analysis

A basket was defined as a unique combination of:

- Member_number
- Date

Key Findings:

- The dataset contains 9,835 unique baskets
- Average basket size is 3.95 products
- Maximum basket size is 14 products
- Single-item baskets represent approximately 17% of all transactions

The analysis shows that most grocery transactions contain a moderate number of products, reflecting routine household shopping behavior.

---

# 👥 Customer Purchase Frequency Analysis

Customer shopping frequency was calculated using the number of unique shopping days per customer.

Customers were segmented into:

- 1 Visit
- 2–5 Visits
- 6–10 Visits
- 10+ Visits

Key Findings:

- Approximately 68% of customers shop less than once per month
- Shopping activity is broadly distributed across the customer base
- The top 10 customers contribute only 3.8% of total shopping activity

This suggests that the grocery store depends on a large number of occasional shoppers rather than a small group of highly loyal customers.

---

# 🥛 Product Popularity Analysis

The analysis identified the most frequently purchased grocery products.

Top-selling products include:

- whole milk
- other vegetables
- rolls/buns

Key Findings:

- Staple household products dominate customer baskets
- Essential grocery products drive recurring store visits
- Product demand is concentrated around frequently consumed daily items

This highlights the importance of maintaining strong inventory availability for core grocery products.

---

# 📅 Weekday Shopping Analysis

Transaction timestamps were analyzed to identify shopping behavior across weekdays.

Key Findings:

- Thursday is the busiest shopping day
- Shopping behavior changes across weekdays
- Average basket size varies depending on the day of the week

These patterns can support operational planning, workforce scheduling, and inventory replenishment strategies.

---

# 🔗 Product Co-Occurrence Analysis

Product co-occurrence analysis was performed to identify products frequently purchased together in the same basket.

Key Findings:

- Several grocery items consistently appear together in customer transactions
- Complementary purchasing behavior is visible across staple products
- Product pairing patterns reveal cross-selling opportunities

This analysis can improve:

- Shelf placement optimization
- Product bundling strategies
- Promotional campaign planning
- Store navigation efficiency

---

# 👑 Top Customer Analysis

The project identifies the top 10 customers based on total basket count.

Monthly shopping frequency trends were analyzed to understand:

- Repeat purchasing behavior
- Shopping consistency
- High-frequency customer activity

The analysis shows that even top customers contribute a relatively small share of total shopping activity, reinforcing the importance of broad customer engagement.

---

# 📊 Visualizations

The project includes:

- Basket size histogram
- Top 20 products bar chart
- Customer frequency segment chart
- Average basket size by weekday chart
- Weekday transaction count visualization
- Top customer monthly shopping frequency plot

All visualizations were created using matplotlib and seaborn with professional formatting and clean analytical styling.

---

# 🛠️ Technologies Used

- Python
- pandas
- matplotlib
- seaborn

---

# 🚀 Conclusion

This analysis provides valuable insights into grocery shopping behavior, customer purchasing frequency, basket composition, and operational retail patterns.

Key opportunities include:

- Improving product placement strategies
- Optimizing inventory planning for high-demand products
- Enhancing cross-selling opportunities through co-occurrence analysis
- Increasing customer retention among low-frequency shoppers
- Aligning operational planning with weekday shopping trends
- Using basket analysis to support promotional campaign strategies
