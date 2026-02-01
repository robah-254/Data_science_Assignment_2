# Data_science_Assignment_2

## Jumia E-commerce Product Analytics.

### Data Cleaning

- This involved first getting rid of duplicate products in the first column (Product).

- The next step involved filling in blank values in the Rating column with the average, as it presented the least difference from the original mean compared to the mode and median.

- The Review column had negative values, and this can't be; this prompted the creation of a new review column and found the absolute values of the reviews. This converted all the reviews to positive.

### Data Enrichment

- A new column (discount percentage**) was added. The discount value was calculated using (old price - current price) / old price * 100.

- New columns were also created, where:

- Rating Category was grouped as:
   - Poor for ratings below 3
   - Average for ratings between 3 and 4.4
   - Excellent for ratings of 4.5 and above

- AND Discount Category was grouped as:
   - Low Discount for discounts below 20%
   - Medium Discount for discounts between 20% and 40%
   - High discount for discounts above 40%

Finally, next was data analysis done in the above Excel document (analysis, dashboard, pivot tables, and visualizations).
