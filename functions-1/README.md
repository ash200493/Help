---
description: >-
  Anaplan provides a range of functions that allow you to perform calculations
  or other actions on the data in your models.
---

# Functions and formulas

### Overview2

You use functions by writing formula in line items. The **Formula editor** is always visible when you're working in a model.

[Learn how to create and edit formula.](www.google.com)

For example, the following formula finds the square root of 16, using the [SQRT](sqrt.md) function.

**SQRT\(16\)**

You can enter values directly into formula, like in the example above, or reference line items or list properties.

For example, the following formula fins the square root of the value in the model _Rooms_, and line item _Width_.

**SQRT\(Rooms.Width\)**

Formulas can also contain expressions, references, operators, and constants.

Here are some more examples of formula you can enter in line items.

| Formula | Description | Result |
| :--- | :--- | :--- |
| 2 + 3 | Calculates 2 plus 3 using the + \(plus sign\) operator. | 5 |
| DIVIDE\(50, 5\) | Calculates 50 divided by 5, using the DIVIDE function. | 10 |
| SQRT\(16\) | Finds the square root of 16, using the SQRT function. | 4 |
| UPPER\(anaplan\) | Converts the text 'anaplan' to 'ANAPLAN' using the UPPER function. | ANAPLAN |
| MOD\(Party.Beverages, Party.Guests\) | Returns the remainder when one number is divided by another, using the MOD function. This example shows how you can include line items or list properties in your formula. In this example, the value of Party.Beverages is 200, and the value of Party.Guests is 30. | 20 |
| RIGHT\(Product.Name, 5\) | Extracts the last 5 letters from a text string, using the RIGHT function. This example shows how you can include line items or list properties in your formula. In this example, the value of Products.Name is Mobile phone. | phone |

### Types of function

The following types of functions are available in Anaplan.

Click a category to see all of the functions in that category, or view [All functions](www.google.com).

* [Aggregation](www.google.com)
* [Call centre planning](www.google.com)
* [Compound](www.google.com)
* [Data conversion](www.google.com)
* [Financial](www.google.com)
* [Logical](www.google.com)
* [Numeric](www.google.com)
* [Time and date](www.google.com)
* [Other](www.google.com)

### See functions in action

Download the [Formulas and functions app](www.google.com) from the Anaplan App Hub to see many of the functions in action.

### Find which function to use

If you know what you want to do, but you're not sure which function will help, try the [Reverse lookup](www.google.com) page. 

### Compare functions with Microsoft Excel

See the [Excel comparison page](www.google.com) to find equivalent Anaplan functions in Microsoft Excel.

This is useful if you want to migrate a calculation that you use in Excel, to Anaplan.



