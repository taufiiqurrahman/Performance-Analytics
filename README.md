## README

### Kimia Farma Performance Analytics 2020-2023

#### Project Overview

This project is a comprehensive analysis of Kimia Farma's business performance from 2020 to 2023. As a Big Data Analytics Intern at Kimia Farma, the primary goal is to evaluate the company's performance through data analysis and visualization. The project involves several tasks, including data import, table creation, and dashboard design using Google Looker Studio.

#### Prerequisites

Before starting the project, ensure the following prerequisites are met:

1. **Google Account**: Ensure you have a Google account.
2. **Google Cloud Platform (GCP) Login**: Login to GCP with your Google account and ensure you have access to BigQuery.
3. **Project and Dataset Creation**:
    - Create a project named `Rakamin_KF_Analytics` in BigQuery.
    - Create a dataset named `kimia_farma` within the project.
4. **GitHub Repository**: Create a repository on GitHub to store your BigQuery syntax and analysis results.

#### Steps and Tasks

1. **Importing Datasets to BigQuery**:
    - Import the following datasets into BigQuery:
        - `kf_final_transaction.csv`
        - `kf_inventory.csv`
        - `kf_kantor_cabang.csv`
        - `kf_product.csv`
    - Ensure the table names match the dataset names (without ".csv").

2. **Creating Analysis Tables**:
    - Create an analysis table by aggregating data from the imported tables. The mandatory columns are:
        - `transaction_id`
        - `date`
        - `branch_id`
        - `branch_name`
        - `kota`
        - `provinsi`
        - `rating_cabang`
        - `customer_name`
        - `product_id`
        - `product_name`
        - `actual_price`
        - `discount_percentage`
        - `persentase_gross_laba`
        - `nett_sales`
        - `nett_profit`
        - `rating_transaksi`

3. **Designing the Dashboard**:
    - Create a performance analytics dashboard for Kimia Farma for the years 2020-2023 in Google Looker Studio.
    - Connect the analysis table in BigQuery to Google Looker Studio.
    - Design the dashboard to include:
        - Title
        - Summary
        - Filter Control
        - Snapshot Data
        - Yearly Revenue Comparison
        - Top 10 Transactions by Branch Province
        - Top 10 Nett Sales by Branch Province
        - Top 5 Branches with Highest Rating but Lowest Transaction Rating
        - Geo Map for Total Profit by Province
        - Additional analyses as per creativity

4. **Final Submission**:
    - Prepare a PowerPoint presentation using the provided template: [Final Task Template](http://bit.ly/template-final-task-kimia-farma-bda)
    - Include:
        - Personal Biodata
        - Project Results
        - Links to GitHub repository and video presentation
    - Submit the final task file named `FinalTask_KimiaFarma_BDA_[Your Name]`

#### Additional Information

- **Data Dictionary**:
    - `kf_final_transaction.csv`: transaction details including `transaction_id`, `product_id`, `branch_id`, `customer_name`, `date`, `price`, `discount_percentage`, `rating`.
    - `kf_product.csv`: product details including `product_id`, `product_name`, `product_category`, `price`.
    - `kf_inventory.csv`: inventory details including `inventory_ID`, `branch_id`, `product_id`, `product_name`, `opname_stock`.
    - `kf_kantor_cabang.csv`: branch details including `branch_id`, `branch_category`, `branch_name`, `kota`, `provinsi`, `rating`.

- **Hints and Tips**:
    - Ensure proper roles and permissions in GCP.
    - Follow naming conventions for projects and datasets.
    - Use clean and understandable dashboard designs.
    - Document each step thoroughly in the GitHub repository.

#### Files and Resources

- [Looker Studio Dashboard Image](./LookerStudiosDashboard.png)
- [BigQuery Syntax Script](./vix_kimia_farma_script.sql)
- [Project Documentation PDF](./Kimia_Farma__Big_Data_Analyst__Challenge_Prerequisite_and_Hints__Final_Task-9902254e-5c2e-40b2-b42c-7a20cb46c562.pdf)

### Conclusion

This README provides a detailed overview of the project tasks and requirements for analyzing Kimia Farma's business performance. Follow the steps carefully, ensure all prerequisites are met, and use the provided resources to successfully complete the project.
