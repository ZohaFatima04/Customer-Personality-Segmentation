# Customer Personality Segmentation
## Business Context

Understanding customer personality and behavior is pivotal for businesses to enhance satisfaction and increase revenue. Segmentation based on demographics, personality traits, and purchasing behavior allows companies to:

- Design personalized marketing campaigns

- Improve customer retention

- Optimize product offerings and resource allocation

A leading retail company with a growing customer base seeks deeper insights into customer profiles. By analyzing personality traits, lifestyles, and purchasing habits, the company can move away from generic strategies and sustain a competitive edge through targeted and personalized approaches.

## Objective

The goal of this project is to identify distinct customer segments using unsupervised machine learning. Specifically, the project aims to:

- Develop personalized marketing strategies to increase conversion rates

- Design effective retention strategies for high-value customers

- Optimize pricing, promotions, and inventory planning

- Provide actionable insights into customer behaviors and preferences

## Dataset & Data Dictionary

The dataset contains customer demographics, personality traits, purchasing behaviors, and marketing campaign responses.

### Customer Information

- ID: Unique customer identifier

- Year_Birth: Year of birth

- Education: Education level

- Marital_Status: Marital status

- Income: Household income

- Kidhome: Number of children

- Teenhome: Number of teenagers

- Dt_Customer: Date joined the company

- Recency: Days since last purchase

- Complain: Complaint in the last 2 years (1 = Yes, 0 = No)

### Spending (Last 2 Years)

MntWines, MntFruits, MntMeatProducts, MntFishProducts, MntSweetProducts, MntGoldProds: Amount spent on each product category

### Campaigns & Response

- NumDealsPurchases: Purchases with discounts

- AcceptedCmp1 to AcceptedCmp5: Response to prior campaigns

- Response: Response to last campaign

### Shopping Behavior

- NumWebPurchases: Purchases via website

- NumCatalogPurchases: Purchases via catalog

- NumStorePurchases: Purchases in stores

- NumWebVisitsMonth: Website visits last month

### Tools & Technologies

- Python (core language)

- Jupyter Notebook (development environment)

- Pandas, NumPy (data cleaning and manipulation)

- Matplotlib, Seaborn (data visualization)

- Scikit-learn (K-Means clustering, scaling, evaluation metrics)

- Git & GitHub (version control, portfolio hosting)

## Workflow

1. Exploratory Data Analysis (EDA):

- Demographic distributions (age, income, family structure)

- Purchase behavior across product categories

- Channel usage (store, catalog, online)

2. Data Preprocessing:

- Handling missing values and outliers

- Feature scaling (StandardScaler)

- Encoding categorical features

3. Clustering with K-Means:

- Determined optimal k using the elbow method & silhouette score

- Segmented customers into distinct groups

4. Cluster Profiling & Visualization:

- Compared segments across demographics, spending habits, and purchase channels

- Created visual profiles to explain actionable insights

## Results

- Segmentation revealed 3–5 distinct customer groups with clear differences in income, product preferences, and channel usage.

- High-income clusters spend heavily on wine and gold products → targeted for premium campaigns.

- Mid-income, family-heavy clusters purchase more daily essentials (meat, fruits) → suited for discount offers and loyalty programs.

- Online-focused customers showed higher engagement in digital channels → candidates for email and web campaigns.

## Next Steps

- Apply alternative clustering techniques (DBSCAN, hierarchical clustering) for comparison

- Perform why-analysis to investigate factors behind differences (e.g., why certain segments spend more on specific categories)

- Build a dashboard (e.g., Power BI or Streamlit) for interactive segmentation insights

- Integrate predictive modeling to forecast customer lifetime value (CLV)

## How to Use

#### 1. Clone the repository:

git clone https://github.com/<your-username>/Customer-Personality-Segmentation.git
cd Customer-Personality-Segmentation


#### 2. Install dependencies:

pip install pandas numpy matplotlib seaborn scikit-learn jupyter


#### 3. Run the notebook:

- jupyter notebook Learner_Notebook_Full_Code_Version_Customer_Personality_Segmentation.ipynb

#### 4. Step through each section to reproduce the analysis and clustering results.
