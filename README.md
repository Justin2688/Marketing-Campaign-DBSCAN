# Marketing-Campaign-DBSCAN
How did I use DBSCAN on this data?\
I have grouped up customers based on total Purchases, number of web visit per Month, campaigns accepted, total Spent, and how recent they have made a purchase.

What does this do?\
Using this allowes identify key traits of customer groups. In this case we Identified how many customers have the lowest sales and engagment and from there we can look at key attributes

Summary of my process.\
Cleaned the data. There was 20-30 customers with missing income so we dropped them. There was also a huge outlyer in income with a value of 666666 for one sutomer so we droped that customer.
Did some feature engineering of adding a totalSpent, totalPurchases and AcceptedCmpTotal columns to the dataset.
Applied DBSCAN for our cluster model. Used DBSCAN because of the size and how varried the data was. Also dont have to manually figure the number of clusters needed. With our results K-means probably
would of been fine.

My findings?\
Looking at cluster 0(1738 people out of 2215. Its huge compaired to the other clusters) they have the lowest income, highest average kids at home and top for teens at home, and overall lowest sales and engament.
Web visits a little above average. Overall this cluster identified the low income family shoppers. Because the have spent the least but being the biggest group of people this store possibly has high priced items.
If the store stocked more affordable items or had more/better sale campaigns they might be abe to engage with this group more.
