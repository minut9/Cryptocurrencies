# Cryptocurrencies

The purpose of this project is to analyze cryptocurrency data using methods of Unsupervised Machine Learning broken up into four Deliverables. Once the data was Downloaded from CryptoCompare, Pandas was used to fit the learning models. Reduction of the data prepared for clustering. A clustering Algorithm was used for grouping. And hvPlot visualizations were used to share the results. 

* Deliverable 1: Preprocessing the Data for PCA
*	Deliverable 2: Reducing Data Dimensions Using PCA
*	Deliverable 3: Clustering Cryptocurrencies Using K-means
*	Deliverable 4: Visualizing Cryptocurrencies Results

## Results
Once the data was preprocessed and parameters were established for clustering limitations, we sought to find the best value for K, which determined by the Elbow Curve was 4.

<img width="848" alt="Elbow_curve" src="https://user-images.githubusercontent.com/86068655/173469128-31657e06-4506-415c-9e67-29a4912f018f.png">


We also utilized 3D-Scatter with the PCA data and clusters

<img width="889" alt="3D-Scatter" src="https://user-images.githubusercontent.com/86068655/173469147-19894872-60cc-4206-bf93-2041715152e0.png">

<img width="912" alt="hvPlot" src="https://user-images.githubusercontent.com/86068655/173469369-6f6b1397-e6f7-4329-851a-c5154d8a037b.png">

Then the created hvTable above told us there were 532 tradeable currencies. And from the table we created an hvPlot (Scatter) to further show the grouping of the coin supply data. 

<img width="912" alt="hvPlot" src="https://user-images.githubusercontent.com/86068655/173469184-66961489-062c-4e50-828a-e5cc5cdf2f63.png">

## Summary
Unsupervised machine learning establishes a way to group, and cluster based of characteristics of the data; but, unlike machine learning the data is not clearly defined nor does it show how objects are relatable. This data set could be used to classify cryptocurrencies and will show insight to how relatable any new crypto currencies are once they enter the market. 

