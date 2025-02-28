# Iris Flower Dataset Analysis
## Project Overview
This project is an exploratory data analysis of the classic Iris flower dataset, which contains measurements for 150 iris flowers from three different species: Setosa, Versicolor, and Virginica. The analysis examines the relationships between different flower measurements to understand how these features might help distinguish between the species.
## Dataset Description
The Iris dataset consists of the following:

150 samples (50 from each of three species)

4 numerical features:

Sepal length (cm)
Sepal width (cm)
Petal length (cm)
Petal width (cm)


Target variable: Species (Setosa, Versicolor, Virginica)

## Analysis Performed
The analysis includes:

### 1. Data Loading and Inspection

a. Loading the dataset using pandas

b. Examining the first few rows

c. Checking dataset dimensions (150 samples, 5 columns)

d. Reviewing data types and checking for missing values


### 2. Descriptive Statistics

a. Statistical summary of numerical features (mean, std, min/max, etc.)

b. Distribution of species (50 samples for each species)


### 3. Data Visualization

a. 2D scatter plots comparing sepal dimensions

b. Colored scatter plots to visualize species distinctions

c. Pair plots showing relationships between all features

d. Univariate analysis with histograms for each feature by species


### 4. Statistical Analysis

a. Computing mean values for specific features

b. Demonstrating the effect of outliers on mean calculations



## Key Findings

a. The dataset is clean with no missing values

b. Species are perfectly balanced with 50 samples each

c. Petal length and width show clear separation between species, making them strong predictive features

d. Setosa is the most distinguishable species based on petal measurements

e. Versicolor and Virginica show some overlap but can still be reasonably separated

## Technologies Used

Python 3
Libraries:

pandas - for data manipulation

numpy - for numerical operations

matplotlib - for basic plotting

seaborn - for advanced visualization



## Getting Started

1. Clone this repository
2. Install the required packages:
```
Copypip install pandas numpy matplotlib seaborn
```


4. Download the iris.csv dataset or use the one included in the repository
5. Run the Jupyter notebook to see the analysis

## Future Work

Implement machine learning models to predict species

Explore more advanced visualization techniques

Perform feature importance analysis

Compare classification algorithms for this dataset
