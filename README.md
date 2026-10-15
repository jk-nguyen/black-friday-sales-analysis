# Black Friday Sales Analysis – Maven Ski Shop

This is my small guided project from the Maven Analytics "Python Foundations for Data Analysis" course.

## Business questions
- How many unique customers made purchases, and how many orders per customer?
- What were total sales, tax, and items sold?
- Which store location generated the most revenue?

## Approach
- Loaded Excel order data into a Python dictionary
- Built reusable functions (e.g. a column aggregator) to calculate totals
- Used loops, conditions, sets and list comprehensions to summarise sales by location

## Key findings
- **27 orders from 19 unique customers** – about 1.4 orders per customer, so most customers bought only once.
- **$346.25 average order value** (including tax), with **54 items sold** – exactly 2 items per order on average.
- **Black Friday drove the weekend:** 26/11 generated $5,915.18 - about 63% of total sales across the three days.
- **Mammoth is the top location at $3,879.81**, roughly **3× Sun Valley** ($1,268.84), the lowest performer.

## Tools
Python, Jupyter Notebook, Excel