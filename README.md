# unsupervised-machine-learning-challenge
----------------------------

## Module 20 Challenge
----------------------------

*Below are the steps taken to solve the challenge:*

### Part 1: Prepare the Data:
* Read file into Pandas DataFrame.
* Remove the "MYOPIC" column from the dataset.
* Standardise your dataset so that columns that contain larger values do not influence the outcome more than columns with smaller values.

### Part 2: Apply Dimensionality Reduction:
* Perform dimensionality reduction with PCA with 90% as the accepted threshhold.
* Then run t-SNE on the principal components, which is the output of the PCA transformation.
* Create a scatter plot of the t-SNE output

### Part 3: Perform a Cluster Analysis with K-means:
* Use a for loop to determine the inertia for each k between 1 through 10.
* Determine where the elbow of the plot is, and at which value of k it appears.

### Part 3: Perform a Cluster Analysis with K-means:
Based on the PCA method used above **(while mainting at least 90% of the explained variance)** and based on the K-means method **(after finding a k value of 3 based on the elbow from the plot)**, I would recommend that patients can be clustered into 3 different "Myopic" clusters.


----------------------------
