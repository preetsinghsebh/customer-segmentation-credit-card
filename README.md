Customer Segmentation with K-Means

This project analyzes credit card customer behavior and groups customers into meaningful segments using K-Means clustering. The goal is to identify spending patterns, understand customer profiles, and support better marketing and business strategies.

📌 Project Summary
	•	Cleaned and prepared the dataset (handled missing values, standardized features).
	•	Removed non-useful columns such as customer ID.
	•	Tested multiple cluster counts using the Elbow Method and Silhouette Score.
	•	Selected k = 2 as the optimal number of clusters.
	•	Trained a K-Means model and added segment labels to the dataset.
	•	Used PCA to visualize the customer groups in 2D.
	•	Exported final outputs including CSVs and plots.

🧩 Key Insights

Cluster 0 (High-Value Customers)
	•	Higher balances
	•	Higher spending amounts
	•	More credit usage (cash advances, purchases)

Cluster 1 (Low-Usage Customers)
	•	Lower balances
	•	Lower spending
	•	More controlled and stable usage

These insights can help businesses tailor marketing campaigns, credit offers, and customer strategies.

📁 Files Included
	•	Credit_Card_Clustering.ipynb – full analysis and model code
	•	customer_segments.csv – dataset with cluster labels
	•	pca_clusters.png – PCA visualization of segments
	•	elbow_plot.png – elbow method graph
	•	silhouette_plot.png – silhouette analysis
	•	segmentation_outputs.zip – all outputs bundled
