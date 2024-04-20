# Marketing-Campaign-DBSCAN
1. Get ready to talk about the benefits of your service. What problem does it solve?
We have grouped up customers based on total Purchases, number of web visit per Month, campaigns accepted, total Spent, and how recent they have made a purchase
2. How will I use the service?
Using this service allowes us to identify key traits of customer groups. In this case we Identified how many customers have the lowest sales and engagment and from there we can look at key attributes
3. Demonstrate the Process using Jupyter: Model Development & Model Deployment process
Cleaned the data. There was 20-30 customers with missing income so we dropped them. there was also a hug outlyer in income with a value of 666666 for one sutomer so we droped that customer.
Did some feature engineering of adding a totalSpent, totalPurchases and AcceptedCmpTotal columns to the dataset.
Applied DBSCAN for our cluster model. Used DBSCAN because of the size and how varried the data was. Also dont have to manually figure the number of clusters needed. With our results K-means probably
would of been fine.
4. What are your learnings?
Looking at cluster 0(1738 people out of 2215. Its huge compaired to the other clusters) they have the lowest income, highest average kids at home and top for teens at home, and overall lowest sales and engament.
web visits a little above average.
