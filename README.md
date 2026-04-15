
# Excel Data Analysis and Functions Toolkit

## Overview

This project demonstrates the use of essential and advanced Excel functions for data analysis. It covers a wide range of concepts including logical formulas, lookup functions, aggregation, text manipulation, date calculations, and dynamic referencing.

The project is structured across multiple datasets to simulate real-world scenarios such as student performance analysis, sales data evaluation, and employee records management.

---

## Project Objective

The objective of this project is to:

- Apply core and advanced Excel functions  
- Perform data analysis using real-world scenarios  
- Demonstrate logical, lookup, and statistical operations  
- Build dynamic and efficient spreadsheets  

---

## Datasets Used

The project consists of three main worksheets:

### Students Grade Sheet
- Student marks and grade classification  
- Performance analysis using logical formulas  

### Sales Data Sheet
- Product sales and revenue analysis  
- Discount calculations and filtering  

### Employee Data Sheet
- Employee salary and service details  
- Date calculations and dynamic ranges  

---

## Key Features

### Relative and Absolute Referencing
- Used relative references (A1) for dynamic calculations  
- Used absolute references ($A$1) for fixed values  

---

### Logical Functions

- IF and Nested IF for classification  
- AND / OR for condition-based evaluation  

Examples:
```

=IF(F2>=90,"A",IF(F2>=80,"B",IF(F2>=70,"C","D")))
=IF(AND(C2>80, D2>80), "Yes", "No")

```

---

### Aggregation Functions

- COUNTIFS  
- SUMIFS  
- AVERAGEIFS  

Used for filtering and analyzing data based on conditions  

---

### Lookup Functions

- VLOOKUP  
- XLOOKUP  
- XMATCH  

Used to retrieve data dynamically from tables  

---

### INDEX and MATCH

- Combined INDEX and MATCH for advanced lookup scenarios  
- Used for multi-condition data retrieval  

---

### Text Functions

- LEFT, FIND for extracting names  
- UPPER and LOWER for formatting  
- TRIM for cleaning text  

---

### Dynamic Referencing

- INDIRECT for dynamic range selection  
- OFFSET for flexible data ranges  

---

### Date and Time Functions

- DATEDIF for calculating years and days  
- TODAY for current date reference  

---

### Mathematical Functions

- ROUND  
- CEILING  
- FLOOR  

Used for financial and numerical adjustments  

---

### FILTER Function

- Extracted data based on conditions dynamically  

Example:
```

=FILTER(A2:I100, F2:F100>80, "No data found")

```

---

## Tech Stack

- Microsoft Excel  

---

## How to Use

1. Open the Excel file  
2. Navigate through each worksheet  
3. Review formulas applied in different columns  
4. Modify input values to observe dynamic results  

---

## Use Cases

- Student performance analysis  
- Sales reporting and discount calculation  
- Employee data tracking  
- Learning advanced Excel functions  

---

## Limitations

- Static dataset  
- No automation using macros or VBA  
- Limited scalability for large datasets  

---

## Future Improvements

- Add dashboards using Pivot Tables and Charts  
- Integrate Power Query for data transformation  
- Use VBA for automation  
- Connect with external data sources  

---

## Conclusion

This project demonstrates practical usage of Excel for data analysis by applying a wide range of formulas and functions. It provides a strong foundation for handling real-world datasets efficiently.
