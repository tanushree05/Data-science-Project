# Data-science-Project
Project Topic : Clustering Mixed data of a Heart Failure Clinical Record Dataset
The project successfully clusters a Heart Failure ‘Clinical Record Dataset’ into 5 groups using a combination of numerical and categorical features.
Visualizations and statistical summaries help in understanding the patterns and characteristics of each cluster.
To identify clusters of individuals who have experienced heart failure.
The dataset includes both numerical and categorical data, making it suitable for K-prototypes clustering.


Project Title: Clustering Mixed Data of a Heart Failure Clinical Record Dataset

Objective: The goal of the project was to perform clustering on a mixed dataset consisting of both numerical and categorical data from heart failure clinical records, to identify meaningful groups within the patient data.

Steps and Methodologies:

Importing and Exploring the Data

Loaded the dataset using Pandas and displayed the first few rows.
Dataset Size: (299, 13)
Data columns: age, anaemia, creatinine_phosphokinase, diabetes, ejection_fraction, high_blood_pressure, platelets, serum_creatinine, serum_sodium, gender, smoking, time, DEATH_EVENT.
Data Preprocessing

Selected relevant columns for clustering: age, gender, serum_sodium, platelets, smoking.
Defined numerical (age, serum_sodium, platelets) and categorical (gender, smoking) columns.
Scaled numerical features using StandardScaler.
Filtered out outliers in age, serum_sodium, and platelets.
Finding Optimal Number of Clusters

Employed K-Prototypes clustering for mixed data.
Used Elbow Method and Average Silhouette Method to determine the optimal number of clusters.
Based on the plots, identified 5 clusters as the most appropriate for the dataset.
Clustering the Data

Applied K-Prototypes clustering with 5 clusters.
Added cluster labels to the dataframe.
Cluster Exploration

Visualized clusters using Principal Component Analysis (PCA) and 3D scatter plot.
Explored the size and characteristics of each cluster.
Used PairGrid and count plots to analyze numerical and categorical features within clusters.
Cluster Statistics

Generated descriptive statistics for each cluster to understand the distribution and central tendencies of the features within each cluster.
Technical Skills Demonstrated:

Data Manipulation: Utilized Pandas for data loading, cleaning, and manipulation.
Statistical Analysis: Applied standard scaling and handled mixed data types.
Clustering Techniques: Implemented K-Prototypes for clustering mixed data.
Evaluation Methods: Used Elbow Method and Silhouette Score to evaluate clustering performance.
Visualization: Visualized clusters using Seaborn, Matplotlib, and Plotly for both 2D and 3D representations.
Dimensionality Reduction: Applied PCA for reducing data dimensions and facilitating visualization.
Tools and Libraries:

Python: Pandas, NumPy
Scikit-Learn: StandardScaler, silhouette_score, PCA
K-Modes: KPrototypes
Visualization: Seaborn, Plotly, Matplotlib
Results:

Successfully identified 5 distinct clusters in the heart failure clinical records dataset.
Provided visual and statistical insights into the characteristics of each cluster, facilitating better understanding of patient groups.
Link to Project: Open In Colab (Insert specific link if available)

This project demonstrates a comprehensive approach to clustering mixed data types, applying robust preprocessing, evaluation, and visualization techniques to extract meaningful insights from clinical datasets.


