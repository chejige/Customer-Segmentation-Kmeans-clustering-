# Customer-Segmentation unsupervised ML

* Customer segmentation will be applied to an e-commerce customer database using K-means clustering from scikit-learn. 
* This project is trying to answer the following question: can this customer database be grouped to develop customized relationships in each country?
# Create features and build Kmeans model
* To answer this question 3 features will be created and used:
* Order frenqency for each customer
* Days since last purchase for each customer
* Total revenue per each customer
* Then create K-means model and visulize the result. 

# Analysis

* Kmeans has divided the dataset into 6 clusters based on days_since_purchase,	frequency,	revenue of the individual customers. The following clusters are created by the model.

![alt text](https://github.com/chejige/Customer-Segmentation-Kmeans-clustering-/blob/17156b37b1bbdef908ab266c32e34dc2d2369afe/cluster%20(frequency%20revenue).png)
![alt text](https://github.com/chejige/Customer-Segmentation-Kmeans-clustering-/blob/17156b37b1bbdef908ab266c32e34dc2d2369afe/cluster(days_since_purchase%20revenue).png)
# Segment Description
* Cluster Skyblue Bought recently, low average revenue and frequency.So they are recent shoppers, but haven’t spent much.
* Cluster red Purchased some time ago. Low average revenue and frequency. Purchased long time ago and never came back. They are hibernating customer.
* Cluster blue Purchased some time ago. Around average revenue and blow average frequency. These customer has good purchasing ability. Will lose them if not reactivated.
* Cluster green Bought recently, higher than average revenue.There are potential loyalists customer.
* Cluster orange Purchased some time ago, higher than average revenue. May not have bought very recently though.Need to bring them back!
* Cluster purple Buy on a regular basis with high revenue. They are the most promising customer.

# Build a dashboard using Tableau
* From the dashboard in Tableau, the total spending in each country and segement distribution in each country is clear.
![alt text](https://github.com/chejige/Customer-Segmentation-Kmeans-clustering-/blob/17156b37b1bbdef908ab266c32e34dc2d2369afe/Revenue%20per%20country%20and%20segment.png)
![alt text](https://github.com/chejige/Customer-Segmentation-Kmeans-clustering-/blob/17156b37b1bbdef908ab266c32e34dc2d2369afe/segment%20(1).png)


