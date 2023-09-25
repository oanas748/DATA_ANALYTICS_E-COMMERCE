# E-commerce Data Analysis Project Readme

This repository contains a Python data analysis project aimed at cleaning data and extracting valuable insights for an e-commerce website. The project leverages Python to process and analyze the dataset, providing actionable recommendations to enhance the e-commerce site's performance. Below is a comprehensive guide to the project, including its objectives, methodology, and key findings.

## Project Overview

The primary goal of this data analysis project is to harness the power of data to improve the performance and user experience of an e-commerce website. The project follows a structured approach that encompasses data cleaning, exploratory data analysis (EDA), and the extraction of actionable insights. The project can be broken down into the following sections:

### 1. Importing Libraries

This section begins by importing the necessary Python libraries, including pandas for data manipulation and matplotlib for data visualization. These libraries are fundamental for the subsequent data analysis tasks.

### 2. Merging 12 Months of Data

To facilitate comprehensive analysis, data from 12 months is merged into a single file named `all_data.csv`. This consolidation simplifies data handling and enables a holistic view of the e-commerce transactions.

### 3. Data Cleaning

Data cleaning is a pivotal phase in the data analysis process. In this section, the project addresses various data quality issues, including:
- Handling missing values: Rows with missing data are removed to ensure data completeness.
- Removing duplicates: Duplicate records are eliminated to prevent data redundancy.
- Consistency checks: The 'Order Date' column is cleaned by removing rows with placeholder text ('Or') and ensuring data consistency.
- Data type conversion: Columns such as 'Quantity Ordered' and 'Price Each' are converted to their appropriate data types (float) for numerical analysis.
- Calculating sales: A 'sales' column is added to quantify the revenue generated from each transaction.

### 4. Analysis

The analysis phase is the core of the project, where actionable insights are extracted. Key analyses include:

#### a. The Highest Month in Sales

The project visualizes and identifies the month with the highest sales, aiding in understanding seasonal trends and peak sales periods.

#### b. The Highest City in Sales

By segmenting sales data by city, the project identifies the cities contributing the most to the e-commerce site's revenue.

#### c. Best Timing for Advertising

The project analyzes sales data to determine the optimal times and days for advertising to maximize user engagement and conversions.

#### d. Most Products Sold Together

Through analysis of order data, the project identifies products frequently purchased together, potentially informing product bundling or marketing strategies.

#### e. Most Selling Product

The project determines the best-selling product based on sales quantity and visualizes its performance.

### 5. Visualization

Data visualization plays a vital role in presenting the analysis results effectively. The project employs various visualization techniques, such as bar charts and line plots, to illustrate key findings. These visualizations simplify complex data and make it accessible to a wider audience. The final conclusion results was integrated into tableau and the dashboard below shows the summary
![Dashboard 1](https://github.com/oanas748/DATA_ANALYTICS_E-COMMERCE/assets/126720570/4ed89cdd-a1ff-4881-8363-65c554838179)


### 6. Conclusion

The concluding section provides a summary of the project's main findings and insights. It serves as a foundation for actionable recommendations to improve the e-commerce site's performance, marketing strategies, and overall user experience.

### 7. Saving the Cleaned Data

The final cleaned and processed dataset is saved as 'new_data.csv,' ensuring that the data is readily available for further analysis, reporting, or integration into the e-commerce platform.

## Getting Started

To begin using this project:

1. Clone this repository to your local machine.

2. Install the required Python libraries listed in the code.

3. Download the e-commerce dataset and place it in the 'Sales_Data' directory (or update the code to point to your dataset location).

4. Follow the code and documentation within the project to replicate the data cleaning and analysis process.

5. Explore the project's visualizations and insights to inform data-driven decisions for your e-commerce site.

By following these steps, you can leverage the power of data analysis to enhance your e-commerce website's performance and user experience.
