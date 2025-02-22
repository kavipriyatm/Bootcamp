# Task 1: Basic K-means Implementation  
**What I Learned:**  
I implemented K-means clustering on a 2D dataset and visualized how data points were grouped into clusters.  
I understood how centroids are computed and how data points are assigned to the closest centroid.

**Challenges Faced:**  
Choosing the right number of clusters and ensuring the dataset was suitable for clustering.  
Interpreting the final clusters and understanding how the centroids align with the data.

**Final Thought:**  
This task helped me learn the basics of K-means clustering and how to visualize it.

**Dataset Used:**  
- **Dataset Name:** Credit Card Dataset  
- **Source:** Kaggle  
- **Details:** A dataset containing features such as credit card details, used for clustering.

---

# Task 2: Centroid Selection  
**What I Learned:**  
I experimented with different initializations of centroids and saw how they affected the clustering results.  
I realized that the starting points of centroids can influence the final clusters.

**Challenges Faced:**  
Comparing the effects of random centroid initialization on the outcome.  
Understanding how different initializations lead to different results.

**Final Thought:**  
Centroid initialization is important and can affect the quality of clustering results.

**Dataset Used:**  
- **Dataset Name:** Credit Card Dataset  
- **Source:** Kaggle  
- **Details:** A dataset containing features such as credit card details, used for clustering.

---

# Task 3: K-means on Real Data  
**What I Learned:**  
I applied K-means clustering to the Loan dataset (without labels) and explored how data points were grouped based on multiple features.  
I also learned that preprocessing (like normalization) is important before applying K-means.

**Challenges Faced:**  
Dealing with feature scaling to make sure the data was ready for clustering.  
Interpreting the clustering results without predefined labels.

**Final Thought:**  
Using K-means on real data showed me how clustering can reveal patterns in datasets.

**Dataset Used:**  
- **Dataset Name:** Loan Dataset  
- **Source:** My own created dataset  
- **Details:** A dataset containing loan-related information, including features like loan amount, applicant income, and credit score.

---

# Task 4: Elbow Method  
**What I Learned:**  
I used the elbow method to determine the optimal number of clusters for K-means.  
I plotted the within-cluster sum of squares for different values of K and identified the "elbow" to find the best K.

**Challenges Faced:**  
Determining the point where the "elbow" occurs and interpreting the plot correctly.  
Understanding that the elbow method gives an estimate, not a precise answer.

**Final Thought:**  
The elbow method is a useful technique to help decide the number of clusters for K-means.

**Dataset Used:**  
- **Dataset Name:** Loan Dataset  
- **Source:** My own created dataset  
- **Details:** A dataset containing loan-related information, including features like loan amount, applicant income, and credit score.

---

# Task 5: Cluster Analysis  
**What I Learned:**  
I analyzed the clusters obtained from K-means and identified patterns in the data based on the features.  
I learned how to describe each cluster's traits by looking at its centroids.

**Challenges Faced:**  
Determining meaningful interpretations for each cluster.  
Understanding how to assign labels to clusters based on the data.

**Final Thought:**  
Cluster analysis helps in understanding the data's underlying structure and can be used for data-driven decisions.

**Dataset Used:**  
- **Dataset Name:** Loan Dataset  
- **Source:** My own created dataset  
- **Details:** A dataset containing loan-related information, including features like loan amount, applicant income, and credit score.

---

# Task 6: Handling High-Dimensional Data  
**What I Learned:**  
I applied PCA to reduce the dimensions of a high-dimensional dataset, then performed K-means clustering on the reduced data.  
I learned that reducing dimensions before clustering makes it easier to visualize and process the data.

**Challenges Faced:**  
Choosing how many principal components to keep in PCA.  
Ensuring the reduced data still captured important patterns for clustering.

**Final Thought:**  
Using PCA to reduce dimensions is helpful when working with high-dimensional data, allowing for more efficient clustering.

**Dataset Used:**  
- **Dataset Name:** Loan Dataset  
- **Source:** My own created dataset  
- **Details:** A dataset containing loan-related information, including features like loan amount, applicant income, and credit score.
