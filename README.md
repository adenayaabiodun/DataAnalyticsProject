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
Assuming product names are in column B

## Text Manipulation
**Question 2: Uppercase Product Names**
*What is the total number of product names converted to uppercase using the UPPER functions, follow these steps:*
1. Use the UPPER function to convert product names to uppercase.
2. Count the cases where the result is "YES"
  **Formula:**
   ``` excel
   =COUNTIF(C2:C101, "YES")

 **Question 3: Lowercase Product Names**
*How many product names are transformed into lowercase using the LOWER function?*

**Answer: To count the product names transformed into lowercase using the LOWER function, follow these steps:**
  1. Use the LOWER function to convert product names to lowercase.
  2. Count the cases where the result is "YES"
    **Formula:**
     ```excel
     =countif(D2:D101, "YES")
