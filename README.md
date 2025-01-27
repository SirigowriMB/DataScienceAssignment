# DataScienceAssignment


# Data Science Assignment - eCommerce



## Task 1: Exploratory Data Analysis (EDA) and Business Insights

- **File**: `FirstName_LastName_EDA.ipynb`
- **Description**: This Jupyter Notebook performs an exploratory data analysis (EDA) on the provided eCommerce dataset, which includes customer, product, and transaction information. It generates business insights based on the analysis, including:
  - Customer distribution by region
  - Revenue by product category
  - Revenue trends over time
  - Top customers and products by sales
  - Insights into regions and their revenue contribution

- **File**: `FirstName_LastName_EDA.pdf`
- **Description**: A PDF document summarizing the business insights generated from the EDA, presented in a concise format.

## Task 2: Lookalike Model

- **File**: `FirstName_LastName_Lookalike.ipynb`
- **Description**: This Jupyter Notebook implements a Lookalike Model to recommend similar customers based on their profiles and transaction history. It calculates similarity scores between customers and provides the top 3 lookalikes for each customer in the first 20 records.
  
- **File**: `FirstName_LastName_Lookalike.csv`
- **Description**: A CSV file containing the lookalike recommendations for the first 20 customers, including the similarity score for each recommended customer.

## Task 3: Customer Segmentation / Clustering

- **File**: `FirstName_LastName_Clustering.ipynb`
- **Description**: This Jupyter Notebook applies clustering techniques to segment customers based on their profile information and transaction history. The clustering model uses various customer features and transaction data to identify patterns, and the number of clusters is evaluated using the DB Index.

- **File**: `FirstName_LastName_Clustering.pdf`
- **Description**: A PDF document summarizing the customer segmentation process, the number of clusters, the clustering metrics (including the DB Index), and relevant visualizations.

## Requirements

To run the code and reproduce the analysis, you'll need the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- scipy

Install them using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy
