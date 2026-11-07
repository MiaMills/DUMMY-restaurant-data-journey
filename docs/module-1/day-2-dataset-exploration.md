# Module 1 Day 2: Dataset Exploration

## Dataset

**Dataset name:** pizzaplace  
**Source:** Rdatasets / gt  
**Source page:** https://vincentarelbundock.github.io/Rdatasets/doc/gt/pizzaplace.html

## What one row represents

One row represents one pizza sold. One order can contain more than one pizza, so the same order ID can appear on more than one row.

## Fields I can see

List the fields in the version of the dataset being used and brief description of what each field represents.
Field	Description
| Field | Description |
|---|---|
| **id** | Unique identifier for a transaction or order record |
| **date** | Date the order was placed |
| **time** | Time the order was placed |
| **name** | Name of the pizza ordered |
| **size** | Size of the pizza |
| **type** | Category or type of pizza |
| **price** | Selling price of the pizza (£) |

## Three questions this dataset can help answer

1. Which pizzas generate the highest total sales revenue, based on their prices and number of sales?
2. Which days of the week and times of day have the highest and lowest pizza sales?
3. Which pizza sizes and types are most popular among customers, based on the number of pizzas sold?

## One question this dataset cannot answer well

hich pizza types generate the highest total profit?

## Why it cannot answer it
Limitation: The dataset contains pizza types, selling prices and sales records, but does not include 
ingredient costs or other production expenses. Therefore, it can calculate sales revenue but cannot 
accurately determine profit by pizza type.

State which field or information is missing.

Missing Fields Needed to Calculate Profit by Pizza Type:
- Ingredient costs (£): Cost of ingredients used to make each pizza.
- Labour costs (£): Staff wages and salaries associated with preparing and selling pizzas.
- Utility costs (£): Electricity, gas and water expenses.
- Premises costs (£): Rent, business rates and maintenance.
- Insurance costs (£): Business insurance expenses.
- Taxes (£): Applicable taxes, where relevant to the profitability calculation.
- Packaging costs (£): Cost of pizza boxes and other packaging materials.
- Overhead allocation (£): Proportion of shared business expenses attributed to each pizza type.

Key idea: Profit is calculated by subtracting costs from revenue.

Profit (£) = Total Sales Revenue (£) − Total Costs (£)

To calculate profit accurately by pizza type, the dataset must also show how shared costs are allocated across different pizza types.
Record anything important about where the data came from, what is synthetic or public, or any limitations you should remember.

## Notes about provenance or limitations
### Notes About Provenance and Limitations

The pizza sales dataset is **synthetic**, meaning it has been artificially generated for educational purposes rather than collected 
from actual restaurant transactions. Its purpose is to provide a realistic example of business data for practising data analysis.
Although the dataset contains useful information, including pizza names, types, sizes, prices and transaction dates and times, it has
several limitations. For example, it does not include ingredient costs, staff salaries, utility bills, insurance or other operational 
expenses. Therefore, while the dataset can be used to analyse sales patterns, customer purchasing trends and revenue, it cannot 
accurately determine profitability.

Furthermore, because the data is synthetic, the patterns and trends identified may not accurately reflect real-world customer behaviour
or restaurant performance.

**Understanding data provenance and recognising these limitations is essential for ensuring that conclusions are reliable, transparent 
and appropriate for the intended business questions.**
