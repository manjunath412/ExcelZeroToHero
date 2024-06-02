
# Excel Functions for Data Analysis and Practice

## 1. Mathematical and Trigonometric Functions
- **SUM**: Calculate the total value of the `Value1` column.
  `=SUM(C2:C101)`
- **AVERAGE**: Find the average price.
  `=AVERAGE(F2:F101)`
- **SUMIF**: Sum the `Value2` column where the `Category` is "A".
  `=SUMIF(B2:B101, "A", D2:D101)`
- **ROUND**: Round the `Price` values to the nearest whole number.
  `=ROUND(F2, 0)`

## 2. Statistical Functions
- **COUNT**: Count the number of entries in the `ID` column.
  `=COUNT(A2:A101)`
- **COUNTA**: Count the number of non-empty cells in the `Text` column.
  `=COUNTA(E2:E101)`
- **COUNTIF**: Count how many times "Text1" appears in the `Text` column.
  `=COUNTIF(E2:E101, "Text1")`
- **MEDIAN**: Find the median quantity.
  `=MEDIAN(G2:G101)`

## 3. Logical Functions
- **IF**: Create a column to label if the `Value1` is greater than 250.
  `=IF(C2 > 250, "High", "Low")`
- **AND**: Check if `Value1` is greater than 200 and `Value2` is less than 500.
  `=AND(C2 > 200, D2 < 500)`
- **OR**: Check if `Value1` is greater than 200 or `Value2` is less than 500.
  `=OR(C2 > 200, D2 < 500)`

## 4. Lookup and Reference Functions
- **VLOOKUP**: Look up the price based on ID.
  `=VLOOKUP(5, A2:H101, 6, FALSE)`
- **MATCH**: Find the position of "Text3" in the `Text` column.
  `=MATCH("Text3", E2:E101, 0)`
- **INDEX**: Get the value from `Quantity` in the 10th row.
  `=INDEX(G2:G101, 10)`

## 5. Text Functions
- **LEFT**: Extract the first 4 characters of the `Text` column.
  `=LEFT(E2, 4)`
- **RIGHT**: Extract the last character of the `Text` column.
  `=RIGHT(E2, 1)`
- **MID**: Extract characters from the 2nd position to the 4th position in the `Text` column.
  `=MID(E2, 2, 3)`
- **TRIM**: Remove any extra spaces in the `Text` column.
  `=TRIM(E2)`
- **CONCATENATE**: Combine `Category` and `Text` into one cell.
  `=CONCATENATE(B2, " - ", E2)`

## 6. Date and Time Functions
- **TODAY**: Get the current date.
  `=TODAY()`
- **YEAR**: Extract the year from the `Date` column.
  `=YEAR(E2)`
- **MONTH**: Extract the month from the `Date` column.
  `=MONTH(E2)`
- **DAY**: Extract the day from the `Date` column.
  `=DAY(E2)`
- **NETWORKDAYS**: Calculate the number of working days between two dates.
  `=NETWORKDAYS(E2, E3)`

## 7. Financial Functions
- **PMT**: Calculate the monthly payment for a loan with a principal of 10000, an annual interest rate of 5%, and a term of 3 years.
  `=PMT(0.05/12, 3*12, 10000)`
- **NPV**: Calculate the Net Present Value of an investment with an annual discount rate of 10% and cash flows in the `Value1` column.
  `=NPV(0.10, C2:C101)`
- **IRR**: Calculate the Internal Rate of Return for the cash flows in the `Value1` column.
  `=IRR(C2:C101)`

## 8. Data Analysis and Visualization Tools
- **PivotTable**: Create a PivotTable to summarize `Value1` by `Category`.
- **Conditional Formatting**: Apply conditional formatting to highlight `Price` values greater than 50.
- **Data Analysis ToolPak**: Perform a regression analysis with `Value1` as the dependent variable and `Value2` as the independent variable.

## 9. Text to Columns
- **Text to Columns**: Split the `Text` column into two columns based on a delimiter.

## 10. Data Cleaning
- **CLEAN**: Remove non-printable characters from the `Text` column.
  `=CLEAN(E2)`
