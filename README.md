# SQL
## How can you isolate (or group) the transactions of each cardholder?

Consider the time period 7:00 a.m. to 9:00 a.m.

## What are the 100 highest transactions during this time period?

Do you see any fraudulent or anomalous transactions?

If you answered yes to the previous question, explain why you think there might be fraudulent transactions during this time frame.

Some fraudsters hack a credit card by making several small payments (generally less than  2.00),𝑤ℎ𝑖𝑐ℎ𝑎𝑟𝑒𝑡𝑦𝑝𝑖𝑐𝑎𝑙𝑙𝑦𝑖𝑔𝑛𝑜𝑟𝑒𝑑𝑏𝑦𝑐𝑎𝑟𝑑ℎ𝑜𝑙𝑑𝑒𝑟𝑠.𝐶𝑜𝑢𝑛𝑡𝑡ℎ𝑒𝑡𝑟𝑎𝑛𝑠𝑎𝑐𝑡𝑖𝑜𝑛𝑠𝑡ℎ𝑎𝑡𝑎𝑟𝑒𝑙𝑒𝑠𝑠𝑡ℎ𝑎𝑛 2.00 per cardholder. Is there any evidence to suggest that a credit card has been hacked? Explain your rationale.

## What are the top five merchants prone to being hacked using small transactions?

Once you have a query that can be reused, create a view for each of the previous queries.

Create a report for fraudulent transactions of some top customers of the firm. To achieve this task, perform a visual data analysis of fraudulent transactions using Pandas, Plotly Express, hvPlot, and SQLAlchemy to create the visualizations.

Verify if there are any fraudulent transactions in the history of two of the most important customers of the firm. For privacy reasons, you only know that their cardholders' IDs are 18 and 2.

Using hvPlot, create a line plot representing the time series of transactions over the course of the year for each cardholder. In order to compare the patterns of both cardholders, create a line plot containing both lines.

## What difference do you observe between the consumption patterns? Does the difference suggest a fraudulent transaction? Explain your rationale.

The CEO of the firm's biggest customer suspects that someone has used her corporate credit card without authorization in the first quarter of 2018 to pay for several expensive restaurant bills. You are asked to find any anomalous transactions during that period.

Using Plotly Express, create a series of six box plots, one for each month, in order to identify how many outliers there are per month for cardholder ID 25.

## Do you notice any anomalies? Describe your observations and conclusions.

