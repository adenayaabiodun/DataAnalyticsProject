## Data Analytics Project
#### This project was developed by me during the 2023 cohort in collaboration with My Tech with Ac.


## Excel Data Cleaning and Preprocessing
**Question 1: How many product names contain extra spaces that need to be removed using the TRIM function?**

**Answer: To find the number of product names containing extra spaces that need to be removed using the TRIM function, follow these steps:**
1. Apply Excel's TRIM function to the product name column.
2. Count the cases where the trimmed and original names differ.
   **Formula:**
   ```excel
   =COUNTIF(B2:B101, "<>"&TRIM(B2:B101))
