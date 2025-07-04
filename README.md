

--------------------------------------------------
📌 Project Workflow

1. Import Libraries and Load Data
   - Used pandas, matplotlib, seaborn for data handling and visualization.

2. Data Visualization
   - Created a pairplot to explore pairwise relationships between features, colored by gender.

3. KMeans Clustering
   - Used KMeans with k=5 to cluster customers based on:
     - Annual Income (k$)
     - Spending Score (1-100)
   - Added cluster labels to the original DataFrame.

4. Elbow Method
   - Plotted Within-Cluster Sum of Squares (WCSS) for k = 1 to 10.
   - Used the "elbow point" to determine the optimal number of clusters.

5. Cluster Visualization
   - Displayed a scatter plot of the customer clusters using seaborn scatterplot.

6. Silhouette Score
   - Evaluated clustering quality using the silhouette score.

--------------------------------------------------
📈 Output Summary

- Elbow Plot: Suggested optimal clusters ≈ 5.
- Scatter Plot: Clearly visualized 5 distinct customer segments.
- Silhouette Score: Typically ~0.55, indicating reasonably good separation.

--------------------------------------------------
📌 Key Concepts

- KMeans Clustering: Algorithm that partitions data into k distinct clusters by minimizing intra-cluster variance.
- Elbow Method: Heuristic for choosing the optimal number of clusters.
- Silhouette Score: Metric to assess clustering performance.

--------------------------------------------------
