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
   ```
Assuming product names are in column B

## Text Manipulation
**Question 2: Uppercase Product Names**
*What is the total number of product names converted to uppercase using the UPPER functions, follow these steps:*
1. Use the UPPER function to convert product names to uppercase.
2. Count the cases where the result is "YES"
  **Formula:**
   ``` excel
   =COUNTIF(C2:C101, "YES")
   ```

 **Question 3: Lowercase Product Names**
*How many product names are transformed into lowercase using the LOWER function?*

**Answer: To count the product names transformed into lowercase using the LOWER function, follow these steps:**
  1. Use the LOWER function to convert product names to lowercase.
  2. Count the cases where the result is "YES"
    **Formula:**
     ```excel
     =countif(D2:D101, "YES")
     ```
Assuming the result of the LOWER function (whether a product name is in lowercase in column D)

## Data Concatenation
**Question 4: Creating Full Names**
 *Create a "Full Name" column and find the "Full Name" for the first customer, follow these steps*
 
  **Answer: To create the "Full Name" column and find the "Full Name" for the first customer, follow these steps:**
  1. Use the CONCATENATE function to concatenate the first and last names.
  2. For the first customer, use the respective cells for the first and last names.
     **Formula:**
     ```excel
     =CONCATENATE(A2, " ", B2)
     ```
Assuming the first name is in column A and the last name is in column B.

## Data Search
**Question 5: Searching for Transactions**
*Use the SEARCH function to find all transactions that include the term "Smartphone."
How many transactions are included in these terms?*

**Answer: To find the transactions that include the term "Smartphone," follow these steps:**
1. Use the SEARCH function to check if "Smartphone" is present in each product name.
2. Count the cases where the term is found.
  **Formula:**
   ```excel
   =COUNTIF(C2:C1010, "*Smartphone*")
   ```
   Assuming that the product names are in column C.

## Date Analysis
**Question 6: Current Date**
*What is the current data according to TODAY function?*

**Answer: The current date according to the TODAY function will vary depending on when you run the function. it provides the current date based on your system's date and time.**
  **Formula:**
   ```excel
   =TODAY(B2)
```
Assuming the date is in the column B.

 **Question 7: Extracting Day of the Week**
 *Extract the day of the week(e.g., Monday, Tuesday) for the first transaction date using the TEXYT and DATE functions.

 **Answer: To extract the day of the week for the first transaction date, use the below:**
 **Formula:**
 ```excel
=TEXT(DATE(2023,10,01), "dddd")
```

**Question 8: Determining Month and Year**
*Determine the month and year for the first transaction date using TEXT, MONTH, and YEAR functions.

**Answer: To determine the month and year for the first transaction date, use the following:**
**Formula:**
```excel
=TEXT(DATE(2023,10,01), "MMMM") which returns October
=YEAR(DATE(2023,10,01)) which will return 2023

     
