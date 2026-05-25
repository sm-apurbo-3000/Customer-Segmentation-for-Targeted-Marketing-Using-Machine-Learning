# Customer-Segmentation-for-Targeted-Marketing-Using-Machine-Learning

Customer segmentation enables businesses to iden
tify distinct consumer groups and deliver personalised marketing
messages, improving campaign efficiency and reducing acquisi
tion costs. This paper presents a machine learning pipeline for
customer personality analysis that integrates data preprocessing,
feature engineering, Principal Component Analysis (PCA), and
unsupervised clustering to segment 2,208 customers into four
actionable groups. Four algorithms were evaluated across 26
model configurations: K-Means, Agglomerative Clustering, Gaus
sian Mixture Models (GMM), and DBSCAN. A systematic archi
tecture search over PCA dimensionality (components 2 through
7) revealed that PCA with two components achieves the best
clustering quality, yielding a Silhouette Score of 0.4403—a 44.5%
improvement over the initial three-component configuration. The
optimal K-Means model (K=4) identified four distinct segments:
Low-Income Young Customers, Senior Online Family Shoppers,
Inactive Large Families, and Premium High-Value Customers.
The Premium segment demonstrated a campaign acceptance
rate of 21.4%, five times the dataset average. A Random Forest
classifier trained on the cluster labels achieved 88.6% accuracy
in predicting campaign response. Cross-dataset validation on
the UCI Online Retail II dataset (5,763 customers) confirmed
the pipeline’s generalisability, achieving a Silhouette Score of
0.5335—a 74.6% improvement over the original dataset.
