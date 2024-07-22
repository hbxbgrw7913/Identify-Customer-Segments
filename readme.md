# Identify customer segments: Unsupervised Learning Project

## Introduction

This project uses unsupervised learning techniques to identify segments of the population that form the core customer base for a mail order company in Germany. These segments can be used to target marketing campaigns to audiences with the highest expected response rate. The data is provided by Bertelsmann Arvato Analytics and represents a real data science challenge.

## Features

- Data cleaning and demographic pre-processing
- Feature engineering and selection
- Dimensionality reduction using Principal Component Analysis (PCA)
- Customer segmentation with K-means clustering
- Comparison of general population segments with customer segments

## Technologies used

- Python
- Pandas for data manipulation
- NumPy for numerical operations
- Matplotlib and Seaborn for data visualisation
- Scikit-learn for machine learning algorithms (PCA, K-means)

## Installation

To run this notebook, you need to install the following libraries
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Use

1. Clone the repository:
   ```
   git clone https://github.com/romanwolf-git/Identify-Customer-Segments.git
   ```
2. Navigate to the project directory and open the Jupyter notebook.
3. Run the notebook cells sequentially to perform data cleaning, analysis and visualisation.

## Key components

1. **Load data**: Loads demographic data for the general population and customers, as well as feature attribute summaries.

2. **Data Cleaning**: Handles missing values, removes irrelevant characteristics and codes categorical variables.

3. **Feature Engineering**: Creates new features and transforms existing features to improve model performance.

4. **Dimensionality reduction**: Applies PCA to reduce the number of features while retaining most of the variance in the data.

5. **Clustering**: Uses a K-means algorithm to segment the population into distinct groups.

7. **Segment analysis**: Compares the distribution of customers across segments with the general population to identify key customer groups.

## Data Files

- `Udacity_AZDIAS_Subset.csv`: Demographic data for the general population of Germany.
- `Udacity_CUSTOMERS_Subset.csv`: Demographic data for customers of the mail order company
- `Data_Dictionary.md`: Detailed information about the characteristics in the datasets
- `AZDIAS_Feature_Summary.csv`: Summary of feature attributes for demographic data

## Contributors

[Roman Wolf](linkedin.com/in/Roman-Wolf/)
