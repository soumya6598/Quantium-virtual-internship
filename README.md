# Quantium-virtual-internship
This is the repository containing the work I did during my Quantium virtual internship. Find the internship here - https://www.theforage.com/virtual-internships/prototype/NkaC7knWtjSbi6aYv/Data-Analytics

In this Virtual Internship

In the First Task I was given two datasets, customer data and transaction data. After cleaning the data given to me, I extracted the Product Size and the Brand names from the Product column. 

Then there are 3 Trial Stores 77, 86 and 88 and I need to find the suitable control store for them. 

## My methedology for finding the appropritate control store

Fisrt I defined some metrics that will help me to analyse the performance of the stores, these were
* Total number of Customers
* Number of Transactions
* Number of Units Sold
* Total Sales
* Units per transaction
* price per unit
* transaction per customer

I had created two functions. The Correlation function calculated the correlation between the metric value of the two stores and the Distance function calculated the absolute distance between the metric value of the two stores. At last I visualised how the trail store performed compared to the respective control store.
