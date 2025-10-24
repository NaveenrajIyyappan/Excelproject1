# Advanced Excel Project: Electronic Product Data Analysis

This project demonstrates advanced Excel data analysis techniques applied to an electronic product dataset. The analysis was completed as part of the Entri Elevate training program and covers a range of Excel functions and formula applications.

## Overview

The dataset contains information about various electronic products, including their Product ID, Category, and Price. The following Excel concepts and functions were used to analyze and manipulate the data:

---

## 1. Sum, Count, Average

- **Total Price of All Products:**  
  Used the `SUM` function to calculate the sum of the Price column.

- **Number of Products:**  
  Used the `COUNT` function to count the number of products in the dataset.

- **Average Price of Products:**  
  Used the `AVERAGE` function to find the mean price.

**Example Formulas:**
```excel
=SUM(Price)
=COUNT(Price)
=AVERAGE(Price)
```

---

## 2. Minimum and Maximum Price

- **Minimum Price:**  
  Used the `MIN` function to determine the lowest price.

- **Maximum Price:**  
  Used the `MAX` function to find the highest price.

**Example Formulas:**
```excel
=MIN(Price)
=MAX(Price)
```

---

## 3. IF Function – Price Range Categorization

- Created a new column `Price Range` using the `IF` function.
- Products with price ≥ $500 are categorized as "High Price".
- Others are labeled as "Standard Price".

**Example Formula:**
```excel
=IF([@Price]>=500, "High Price", "Standard Price")
```

---

## 4. SUMIF and COUNTIF

- **Total Price for Electronics Category:**  
  Used `SUMIF` to sum prices for products categorized as "Electronics".

- **Count of Products Priced < $100:**  
  Used `COUNTIF` to count products with price less than $100.

**Example Formulas:**
```excel
=SUMIF(Category, "Electronics", Price)
=COUNTIF(Price, "<100")
```

---

## 5. Text Functions – LEFT, RIGHT, MID

- **Day Column:**  
  Used `LEFT` to extract the first 2 characters of the Product ID.

- **Country Code Column:**  
  Used `RIGHT` to extract the last 2 characters of the Product ID.

- **Month Column:**  
  Used `MID` to extract the 4th to 6th characters from the Product ID.

**Example Formulas:**
```excel
=LEFT([@Product ID], 2)
=RIGHT([@Product ID], 2)
=MID([@Product ID], 4, 3)
```

---

## Files

- `ProductData.xlsx` – The dataset and completed analysis (contains all formulas and results)
- `README.md` – Project documentation (this file)

---

## Conclusion

This project showcases the application of key Excel functions for data analysis, including mathematical, logical, and text processing functions. The concepts learned can be applied to a variety of data-driven scenarios in business and research.

**Training:** Entri Elevate  
**Author:** Naveenraj Iyyappan

