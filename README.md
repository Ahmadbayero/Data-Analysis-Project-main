
## Data analysis of company XYZ supermarket with three branches across the nation


# Project Steps

1. Combined data from all three branches into one.

2. Explored the data and it's different features (no missing data).

3. Converted all dates and time to a Datetime object and extracted the DAY, MONTH, YEAR, AND HOUR columns.

4. Grouped data by city and applied aggregate functions for more insight on the performance of the different branches

5. Use of the Seaborn library to visualise data for easy comparison of different features e.g Determine the highest & lowest sold product line


# Insights

1. From observing the quantity column, on average customers tend to buy at least 5 items and above ( customer retention is good)

2. it looks like the gross income on item/s purchase is just the 5% tax on the item's price multiplied by the quantity

3. On average the customer service is quite satisfactory

4. Port Harcourt has the most gross income even though Lagos has the most quantity sold.

5. Epay is the most used payment method followed by cash.

6. On the Product line, the Fashion accessories had the most sales, followed by food & beverages and then Electornic accessories, by far health and beauty products have the lowest sales.

7. Customers tend to pay for Electronics mostly in cash.

8. By far the ratings on all branches are almost similar at an average of 7 out of 10, except for branch B which is the lowest amongst the three.

9. In the health and beauty line, there seems to be more male customers which is quite odd.

10. In the Fashion and electronic accessories, the unit price and quantity bought have an inverse correlation. meaning with raise in unit price there is a drop in quantity purchase.

# Future Work

To drive sales up, We need to increase our customer retention, we don't want customers to just buy what they came for but to buy what they didn't even know that they wanted. I suggestion a further collection of data about our customers so that we can suggest new products based on thier previous purchases, which is a proven way of increasing our sales.


# Standout Section

Here i used a barh plot to visualize the correlation of the gross income and the other features