# Customer Segmentation 
### Customer segmentation using RFM analysis and K-means clustering

<br>
Customer segmentation involves dividing customers into groups based on certain characteristics they share, such as their demographics, geographical location, their interests or their behaviour. Doing so allows marketers to personalise their marketing campaigns, to identify potentially profitable customers and to develop customer loyalty.

\
In this project I use <i>K-means clustering</i>, which is an unsupervised form of machine learning, to segment customers of an online retail company using [data](https://archive.ics.uci.edu/ml/datasets/Online+Retail) regarding thier <b>purchasing behaviour</b>. 

I follow a marketing technique known as <b>RFM analysis</b>, which derives insights based on the following features: 

- Recency (How recent was the customer's last purchase?)
- Frequency (How often do they purchase?)
- Monetary Value (How much do they spend?) 

The project is written in Python and the steps covered in the [Jupyter Notebook](https://github.com/quarterpastten/Customer_Segmentation_Clustering/blob/main/customer_segmentation_kmeans.ipynb) are as follows: 

1. Import and clean data
2. Feature extraction: RFM analysis
3. Pre-processing (remove outliers and feature scaling)
4. Clustering with K-means
5. Observations and conclusions

Please see [here](https://nbviewer.org/github/quarterpastten/Customer_Segmentation_Clustering/blob/main/customer_segmentation_kmeans.ipynb) for a version of the Notebook with the interactive plot displayed. 

# Resulting Clusters

<img src="results.jpg" alt="drawing" width="700"/>

- <b>Group 1 (green)</b>: less frequent, less recent and lower overall spend. This will represent the least valuable customer.
- <b>Group 2 (red)</b>: less frequent, lower overall spend but more recent. This group will be among those to target for promotions.
- <b>Group 3 (blue)</b>: more recent, more frequent and the higher spenders. This represents the most valuable since they are typically the most frequent, most recent and higher spending customers.
