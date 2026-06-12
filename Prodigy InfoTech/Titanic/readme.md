# Titanic Dataset - Data Cleaning and Exploratory Data Analysis (EDA)

## Project Overview

This project focuses on performing Data Cleaning and Exploratory Data Analysis (EDA) on the Titanic dataset. The objective is to understand passenger characteristics, identify patterns in the data, and determine the factors that influenced survival during the Titanic disaster.

The project includes analysis of all three Titanic dataset files:

- train.csv
- test.csv
- gender_submission.csv

---

## Objectives

- Perform data cleaning and preprocessing.
- Handle missing values and duplicate records.
- Explore relationships between variables.
- Visualize important patterns and trends.
- Compare train, test, and submission datasets.
- Generate meaningful insights from the data.

---

## Dataset Description

### 1. Train Dataset (train.csv)

The training dataset contains passenger information along with the target variable:

- PassengerId
- Survived
- Pclass
- Name
- Sex
- Age
- SibSp
- Parch
- Ticket
- Fare
- Cabin
- Embarked

### 2. Test Dataset (test.csv)

The test dataset contains passenger information but does not include the Survived column.

### 3. Submission Dataset (gender_submission.csv)

The submission dataset contains sample prediction results provided by Kaggle.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Data Cleaning Process

The following preprocessing steps were performed:

### Train Dataset

- Removed Cabin column due to excessive missing values.
- Filled missing Age values using Median.
- Filled missing Embarked values using Mode.
- Removed duplicate records.

### Test Dataset

- Removed Cabin column due to excessive missing values.
- Filled missing Age values using Median.
- Filled missing Fare values using Median.
- Removed duplicate records.

### Feature Engineering

Created a new feature:

- FamilySize = SibSp + Parch + 1

---

## Exploratory Data Analysis (EDA)

The following analyses were performed:

### Train Dataset Analysis

- Survival Distribution
- Gender vs Survival
- Passenger Class Distribution
- Passenger Class vs Survival
- Age Distribution
- Fare Distribution
- Fare Outlier Detection
- Correlation Heatmap
- Embarked Port vs Survival
- Family Size vs Survival
- Survival Rate by Gender
- Average Survival Rate by Passenger Class

### Test Dataset Analysis

- Gender Distribution
- Passenger Class Distribution
- Age Distribution

### Submission Dataset Analysis

- Survival Prediction Distribution

### Dataset Comparison

- Dataset Shapes Comparison
- Missing Values Comparison
- Feature Comparison

---

## Key Insights

- Female passengers had a significantly higher survival rate than male passengers.
- First-class passengers had the highest survival probability.
- Third-class passengers had the lowest survival rate.
- Most passengers belonged to the age group of 20–40 years.
- Higher fare passengers were more likely to survive.
- Family size showed a relationship with survival probability.
- The Fare feature contained several outliers.
- Passenger class, gender, and fare were among the most influential factors affecting survival.

---

## Project Structure

```
Titanic-EDA/
│
├── train.csv
├── test.csv
├── gender_submission.csv
├── Task2.ipynb
├── README.md
```

---

## Sample Visualizations

The project contains visualizations such as:

- Histogram
- Count Plot
- Box Plot
- Bar Plot
- Correlation Heatmap

These visualizations help identify trends, distributions, and relationships among variables.

---

## Results

The analysis revealed that:

- Women had a much higher chance of survival.
- Passengers in higher classes were more likely to survive.
- Most passengers paid lower fares.
- Survival was strongly influenced by gender and passenger class.

---

## Conclusion

This project successfully demonstrates the process of Data Cleaning and Exploratory Data Analysis using the Titanic dataset. Missing values were handled, duplicate records were removed, new features were created, and multiple visualizations were generated to uncover meaningful insights.

The project highlights the importance of preprocessing and EDA in understanding datasets before applying machine learning techniques.

---

## Author

**Dev Patel**

Data Analyst | Python | SQL | Data Visualization
