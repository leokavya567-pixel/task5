 # Task 5 - Exploratory Data Analysis (EDA) on Titanic Dataset

## Objective

The objective of this task is to perform Exploratory Data Analysis (EDA) on the Titanic dataset to discover patterns, trends, relationships, and anomalies using statistical methods and data visualization techniques.

## Tools and Libraries Used

* Python
* Google Colab
* Pandas
* Matplotlib
* Seaborn

## Dataset

Titanic Dataset containing passenger information such as:

* Passenger Class
* Name
* Gender
* Age
* Fare
* Cabin
* Embarked Port
* Survival Status

## Steps Performed

### 1. Data Loading

* Imported the dataset using Pandas.
* Displayed the first few rows of the dataset.

### 2. Data Inspection

* Used `info()` to understand data types and missing values.
* Used `describe()` to obtain statistical summaries.

### 3. Missing Value Analysis

* Identified missing values in Age, Cabin, and Embarked columns.

### 4. Univariate Analysis

* Histogram of Age Distribution.
* Boxplot of Fare Distribution.

### 5. Bivariate Analysis

* Survival Count Analysis.
* Survival by Gender.
* Survival by Passenger Class.
* Scatter Plot of Age vs Fare.

### 6. Multivariate Analysis

* Correlation Heatmap.
* Pairplot for Age, Fare, Passenger Class, and Survival.

## Key Findings

* Most passengers were between 20 and 40 years old.
* Female passengers had a significantly higher survival rate than male passengers.
* First Class passengers had better survival chances compared to Second and Third Class passengers.
* Fare contains several outliers, indicating a wide variation in ticket prices.
* Passenger Class and Fare are important factors influencing survival.
* Missing values were found in Age, Cabin, and Embarked columns.

## Conclusion

Exploratory Data Analysis helped identify important relationships and patterns in the Titanic dataset. The analysis showed that gender, passenger class, and fare played significant roles in determining passenger survival. Various visualizations were used to effectively understand the dataset and derive meaningful insights.

## Outcome

Successfully gained practical experience in:

* Data Cleaning and Inspection
* Statistical Analysis
* Data Visualization
* Pattern Recognition
* Trend Analysis
* Insight Generation using EDA
