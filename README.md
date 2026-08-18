# Walmart-Confidence-Interval-and-CLT

## Business Case Study – Customer Purchase Behavior Analysis

This project analyzes Walmart's Black Friday customer purchase behavior using statistical analysis, exploratory data analysis, the Central Limit Theorem (CLT), and Confidence Intervals.

The primary objective is to determine whether customer spending differs based on gender, marital status, and age.

## Business Problem

Walmart wants to understand customer purchase behavior during Black Friday and determine whether spending habits differ between male and female customers.

The analysis addresses the following questions:

* Do women spend more per transaction than men?
* What are the confidence intervals for average male and female spending?
* How does sample size affect the distribution of the sample mean?
* Do married and unmarried customers have different spending patterns?
* How does spending vary across different age groups?
* What actionable recommendations can Walmart use to improve sales and customer engagement?

## Dataset

The dataset contains Black Friday transaction data with the following attributes:

* User_ID
* Product_ID
* Gender
* Age
* Occupation
* City_Category
* Stay_In_Current_City_Years
* Marital_Status
* Product_Category
* Purchase

The dataset is loaded directly from the publicly provided Walmart dataset URL in the notebook.

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Google Colab
* Statistical Analysis
* Central Limit Theorem
* Confidence Intervals

## Analysis Performed

### 1. Data Understanding

* Dataset shape and structure
* Data types
* Statistical summary
* Unique values
* Value counts

### 2. Data Quality

* Missing-value analysis
* Duplicate-value analysis
* Outlier detection using IQR
* Distribution analysis

### 3. Exploratory Data Analysis

* Purchase distribution
* Gender distribution
* Age distribution
* Marital-status distribution
* City-category analysis
* Purchase amount by gender
* Purchase amount by age
* Purchase amount by marital status
* Correlation analysis

### 4. Statistical Analysis

* Male vs Female average purchase
* 90%, 95% and 99% Confidence Intervals
* Central Limit Theorem
* Sampling distribution of means
* Effect of sample size on standard error
* Married vs Unmarried comparison
* Age-group comparison

## Key Findings

* Male customers have a higher average purchase amount than female customers in the available sample.
* The 95% confidence intervals for male and female average spending do not overlap.
* Increasing sample size makes the sampling distribution of the mean more concentrated.
* Higher confidence levels produce wider confidence intervals.
* Married and unmarried customers have very similar average purchase amounts.
* The 26–35 age group represents the largest transaction segment.
* Older customers, particularly the 51+ segment, show relatively high average transaction values.

## Business Recommendations

1. Increase engagement and average spending among female customers through targeted promotions and personalized recommendations.
2. Retain high-value male customers through loyalty benefits and cross-selling.
3. Continue strong digital campaigns for the 26–35 age group because of its high transaction volume.
4. Develop premium and convenience-focused offers for older customers.
5. Avoid relying heavily on marital status for customer segmentation because spending differences are limited.
6. Use customer demographics together with product and purchase behavior for personalized marketing.

## Project Structure

```text
Walmart-Confidence-Interval-CLT/
│
├── Walmart_Confidence_Interval_CLT.ipynb
└── README.md
```

## Author

**Kinjal Dalwadi**

Data Science & Machine Learning | Python | Data Analytics | AI

## Project Type

Data Science / Statistics / Business Case Study
