# Data Science Job Salaries Analysis

## Project Overview
This project involves a comprehensive analysis of job salaries in the data science field from 2020 to 2022. The process is divided into two main parts: first, cleaning and preprocessing the raw dataset to ensure data quality, and second, performing an in-depth exploratory data analysis (EDA) to uncover key trends and insights related to compensation, experience levels, company characteristics, and geographical location.

## Objectives
* Analyze the overall salary distribution across the data science industry.
* Determine how compensation varies with experience level, employment type, and company size.
* Identify the top 10 highest-paying and most in-demand job titles.
* Compare average salaries and the number of job opportunities across different countries.
* Track the trend of data science salaries over the years.

## Tools & Technologies
-   **Python:** The core language used for the analysis.
-   **Pandas:** For data manipulation and cleaning.
-   **NumPy:** For numerical operations.
-   **Matplotlib & Seaborn:** For data visualization.
-   **Country-Converter:** To standardize country names.

## Key Insights
-   Salaries show a strong positive correlation with experience, with **Executive**-level positions commanding the highest average pay.
-   While most positions are **Full-time**, **Contract** roles offer the highest average salary.
-   **Large** and **Medium**-sized companies tend to offer higher salaries compared to small companies.
-   **Data Scientist**, **Data Engineer**, and **Data Analyst** are the three most common job titles in the dataset.
-   The **United States** has the most job opportunities by a large margin and is one of the top-paying countries.
-   There has been a consistent and significant increase in average data science salaries from 2020 to 2022.

## Project Structure
-   `leaning.ipynb`: Jupyter Notebook containing the data cleaning and preprocessing steps.
-   `Vis.ipynb`: Jupyter Notebook with the exploratory data analysis and visualizations.
-   `Data Science Job Salaries.csv`: The original, raw dataset.
-   `df_cleaned`: The cleaned dataset saved in pickle format.

## How to Use
1.  Clone the repository to your local machine.
2.  Install the necessary libraries:
    ```bash
    pip install pandas numpy matplotlib seaborn country-converter
    ```
3.  Run the Jupyter Notebooks sequentially, starting with `cleaning.ipynb` to generate the cleaned dataset, followed by `Vis.ipynb` to perform the analysis.


---
**License:** This project is for educational purposes.
