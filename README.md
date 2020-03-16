# Customer Segmentation using PCA & Kmeans Algorithm
### Problem Statement: 
Analyze demographics data for customers of a mail-order sales company in Germany, comparing it against demographics information for the general population. We will use unsupervised learning techniques to perform customer segmentation, identifying the parts of the population that best describe the core customer base of the company. Then, we'll apply what we've learned on a dataset with demographics information for targets of a marketing campaign for the company, and use a model to predict which individuals are most likely to convert into becoming customers for the company. 

Project Design: We will follow the high-level process flow below for processing data, identifying population cluster and creating a supervised model.

High Level Process Flow:
-	Collect Data for the use case
-	Clean up and Pre-process the demographics (General & Customer) data
-	Feature Engineering
-	PCA, reduce input features to identify effective input features
-	Split the dataset into test, train and validation
-	Generate the shoulder curve to identify the cluster size
-	Apply K-means algorithm to the processed dataset to identify clusters
-	Identify potential customer base clusters by comparing general vs customer cluster
-	Clean up and Pre-process the given train and test customer data 
-	Identify Input Features
-	Create a model
-	Train the model
-	Test the model with test customer data
-	Validate output data and model performance
	Infer insights from the final predicted output 
 

