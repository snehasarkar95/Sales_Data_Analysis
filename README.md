# ABC Private Limited Customer Purchase Analysis

This repository contains data and analysis for ABC Private Limited, a retail company, aimed at gaining insights into its customers' purchasing habits. The focus is specifically on understanding their spending across different product categories. The provided dataset includes a summary of the purchase history of high-volume products from the previous month. The dataset contains information on customer demographics, such as age, gender, marital status, city type, and length of stay in their current city. It also includes details on the products themselves, including product ID and product category.

## Dataset Description

The dataset consists of the following variables:

- **User_ID**: Unique user ID for each customer.
- **Product_ID**: Unique product ID for each purchased item.
- **Gender**: Categorical variable representing the gender of the user (M for male, F for female).
- **Age**: Age groups of customers, divided into bins of 10 years.
- **Occupation**: Masked category representing the occupation of the customer (only a number is provided).
- **City_Category**: Categorical variable representing the category of the city where the customer resides (A, B, or C).
- **Stay_In_Current_City_Years**: Number of years the customer has stayed in their current city.
- **Marital_Status**: Marital status of the customer, where 0 represents unmarried and 1 represents married.
- **Product_Category_1**: Masked product category.
- **Product_Category_2**: Product may belong to another category as well (masked).
- **Product_Category_3**: Product may belong to yet another category (masked).
- **Purchase**: Purchase amount, which serves as the target variable for analysis.

## Purpose

The purpose of this project is to analyze the provided dataset and gain insights into customers' purchasing behavior. By understanding how different customer demographics and product categories relate to purchase amounts, ABC Private Limited can make informed business decisions and tailor its strategies accordingly. The analysis will focus on answering questions such as:

- How does gender impact purchase amounts across different product categories?
- What is the distribution of purchase amounts among different age groups?
- Are there any significant differences in purchase behavior between married and unmarried customers?
- Does the length of stay in a city affect purchasing habits?
- Which product categories contribute the most to overall purchase amounts?

## Repository Contents

This repository contains the following files:

- `Train.csv`: The dataset containing the purchase history and customer demographics.
- `Test.csv`: The dataset containing customer demographics.
- `Notebook.ipynb`: A Jupyter Notebook file containing the analysis of the dataset.
- `README.md`: This readme file providing an overview of the project.

## Usage

To use the dataset and explore the analysis, follow these steps:

1. Clone this repository to your local machine or download the files directly.
2. Install the necessary dependencies if required (e.g., Python, Jupyter Notebook).
3. Open the `Notebook.ipynb` file in a Jupyter Notebook environment.
4. Execute the notebook cells to run the analysis and view the results.
5. Feel free to modify or extend the analysis as needed.

---


 
