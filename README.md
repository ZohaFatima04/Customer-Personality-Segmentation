Customer Personality Segmentation

This project applies unsupervised machine learning to segment customers based on their demographics, lifestyle, and purchasing behavior. By understanding the unique traits of each segment, businesses can design personalized marketing strategies, improve customer retention, and allocate resources more effectively.

Project Overview

The dataset used contains customer demographic details (age, income, family structure), lifestyle indicators, and purchase data across multiple product categories.

The workflow includes:

Data exploration and cleaning – checking for missing values, outliers, and inconsistent entries.

Feature engineering – encoding categorical features, scaling numerical variables, and creating meaningful derived features.

Clustering – applying K-Means and determining the optimal number of clusters using evaluation methods such as the elbow method and silhouette score.

Cluster profiling – analyzing the unique characteristics of each cluster in terms of income, spending habits, product preferences, and preferred purchase channels.

Visualization – creating plots to make cluster insights more interpretable for business users.

Repository Structure

Learner_Notebook_Full_Code_Version_Customer_Personality_Segmentation.ipynb — full notebook containing EDA, preprocessing, clustering, and insights.

data/ (optional) — place your dataset here.

README.md — documentation for the project.

Features

Exploratory Data Analysis: statistical summaries, visualizations of demographics and purchases.

Preprocessing: handling missing values, feature scaling, categorical encoding.

Clustering: K-Means clustering with evaluation metrics for choosing the optimal K.

Profiling: descriptive analysis of clusters to interpret actionable business insights.

Visualization: plots for demographics, purchase categories, and cluster distributions.

Installation

Clone this repository and install the required dependencies:

git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>


If a requirements.txt file is provided:

pip install -r requirements.txt


Otherwise, install manually:

pip install pandas numpy matplotlib seaborn scikit-learn jupyter

Usage

Open Jupyter Notebook:

jupyter notebook


Run the notebook Learner_Notebook_Full_Code_Version_Customer_Personality_Segmentation.ipynb.

Step through each cell to replicate the analysis, clustering, and results.

Results

The clustering analysis produced distinct customer segments that differ in:

Demographics: age groups, family structures, and income levels.

Product preferences: spending across categories such as wine, fruits, meat, fish, sweets, and gold.

Shopping behavior: preferred purchasing channels (store, catalog, online).

Business Implications:

High-income, high-spending customers may be targeted with premium product promotions.

Younger, digital-savvy customers can be approached with online campaigns.

Price-sensitive clusters can be retained through loyalty discounts and catalog promotions.

Next Steps

Experiment with other clustering methods (DBSCAN, hierarchical clustering) to validate results.

Automate the preprocessing and clustering steps into a reusable pipeline.

Build a Streamlit/Flask app or Power BI dashboard to present insights interactively.
