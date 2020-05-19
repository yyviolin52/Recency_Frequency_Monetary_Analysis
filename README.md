# Recency_Frequency_Monetary_Analysis
180k+ records ---> Segment Emails by three main groups, in this code demo, I used percentiles(e.g. quantiles) method.

What is RFM?

RFM is an acronym of recency, frequency and monetary. Recency is about when was the last order of a customer. It means the number of days since a customer made the last purchase. If it’s a case for a website or an app, this could be interpreted as the last visit day or the last login time.

Frequency is about the number of purchase in a given period. It could be 3 months, 6 months or 1 year. So we can understand this value as for how often or how many a customer used the product of a company. The bigger the value is, the more engaged the customers are. Could we say them as our VIP? Not necessary. Cause we also have to think about how much they actually paid for each purchase, which means monetary value.

Monetary is the total amount of money a customer spent in that given period. Therefore big spenders will be differentiated with other customers such as MVP or VIP.

Process of calculating percentiles:

Sort customers based on that metric
Break customers into a pre-defined number of groups of equal size
Assign a label to each group

