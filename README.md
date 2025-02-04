This project performs RFM (Recency, Frequency, Monetary) Analysis on the Zomato dataset to segment customers based on their purchasing behavior. The goal is to identify high-value customers, understand customer retention patterns, and optimize marketing strategies. 

What is RFM Analysis?
RFM Analysis is a customer segmentation technique that considers:

Recency (R) – How recently a customer made a purchase.\
Frequency (F) – How often a customer makes a purchase.\
Monetary (M) – How much a customer spends.

By scoring customers based on these factors, businesses can tailor their marketing efforts more effectively.

The Zomato dataset is a well known training dataset so EDA was skipped in this case. 

Steps
1. RFM Score Calculated\
Compute Recency: Days since last purchase\
Compute Frequency: Total number of purchases\
Compute Monetary: Total spending per customer

2. Customer Segmentation\
Customers were grouped into segments based on their cumulative RFM score with the relative "bins" based along these lines:\
Greater or equal to 13 are labeled "Champions"\
10 to 12 are "Loyal Customers"\
7 to 9 are "Potential Loyalists"\
4 to 6 are "At-Risk"\
Below 4 customers are considered "Lost"

3. Visualizations\
These included user count visualizations for each segment, heatmaps of the various bins wrt their revenue contribution, monetary score distribution, and others.

Further details on insights can be found in the report with this repository.
