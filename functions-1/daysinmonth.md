---
description: >-
  Use the DAYSINMONTH function to determine the number of days in a specified
  month.
---

# DAYSINMONTH

For example, you can use the DAYSINMONTH function to find out that January 2016 had 31 days.

### Syntax

**DAYSINMONTH\(year, month\)** has the following arguments:

| Argument | Data type | Description |
| :--- | :--- | :--- |
| **year** \(Required\) | Number | The year of the month you want to find the number of days for. |
| **month** \(Required\) | Number | The month you want to find the number of days for, represented by a number between 1 and 12. |

### Constraints

The DAYSINMONTH function has the following constraints:

* The month must be represented by a number between 1 and 12. For example, April is represented by a 4.

### Examples

The following table shows some example formulas using the DAYSINMONTH function.

You can enter values directly into your formula, or reference line items or list properties.

| Formula | Description | Result |
| :--- | :--- | :--- |
| DAYSINMONTH\(Product.Year, Product.Month\) | This example shows how you can include line items or list properties in your formula. In this example, the value of Product.Year is 2014, and the value of Product.Month is 3. This formula returns the number of days in March 2014. | 31 |
| DAYSINMONTH\(2012, 1\) | The number of days in January 2012. | 31 |
| DAYSINMONTH\(2012, 2\) | The number of days in February 2012. | 29 |

### Excel equivalent

[EOMONTH](https://support.office.com/en-us/article/eomonth-function-7314ffa1-2bc9-4005-9d66-f49db127d628)

