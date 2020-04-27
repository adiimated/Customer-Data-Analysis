## Goals of the project :
1. The store is launching a new product. We are finding out who the product appeals to , so that we can advertise accordingly.
2. Secondly , we find the product of the hour. It is the product with highest amount of sales.
3. The products which are associated with each other  are stacked together in an aisle. So that customers can find the related products easily.

## Dataset :
1. The first dataset gives the history of previous sales of a product which is similar to the new one to be launched. Analysing this dataset can help the company to understand which salary group should the product be advertised to. Also this can help the owner decide the neighbourhood in which the product would be available.
2. The second dataset gives the history of customers and their spending scores. This can be helpful in deciding the marketing strategy .
3. The last dataset is the inbuilt dataset (groceries) in R. Analysing this dataset can help the owner in stacking of products. 

## Results :
### Dataset 1
Before performing decision tree analysis, we featured scaled the dataset. This helps in better visualization of results. The above visual shows how each value in the dataset can be mapped to show patterns in the data. The red dot represents the customers that didn't buy the product whereas the green dot represents the customers that bought the product. The red region is our estimation where the red dots would lie i.e which customers wont buy the product and the green region is our estimation where the green dots would lie i.e which customers would buy the product.

This result can also be visualized into a tree form which would help the layman understand them quickly. The Tree format concentrates on which age and salary group the owner of the shop should focus on. 1 indicates the higher probability of purchase and 0 indicates the lower probability. Advertisements in this case should cater to and older age group with high income salary.  

### Dataset 2
The elbow method is a heuristic method of interpretation and validation of consistency within cluster analysis designed to help find the appropriate number of clusters in a dataset. With the help of which we found out the optimum number of clusters ,which is 5.

Cluster No. | What It Represents
------------ | -------------
1 | High Income Group + High Spending Score
2 | Average Income Group + Low Spending Score

### Dataset 3
Apriori Algorithm focuses on customer buying habits. It links objects which a customer is highly likely to buy, based on what he has already bought. This helps the customer to find the items he intended to buy easily. The image below shows the first 20 rules derived from the groceries dataset.  

