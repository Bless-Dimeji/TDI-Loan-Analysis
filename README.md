# TDI-Loan-Analysis
Loan Data Analysis Dashboard

      This repository contains the Loan Data Analysis Dashboard project, developed as part of The Data Immersed (TDI) capstone project. The project focuses on analyzing loan data to     
      uncover insights about loan performance, customer demographics, risk factors, and approval rates. The dashboard is built using Microsoft Excel, with the primary goal of creating 
      visualizations that assist in making data-driven decisions.

Table of Contents

      Project Overview
      Data Description
      Analysis
      Key Metrics
      Visualizations
      How to Use
      Future Improvements

Project Overview

    The Loan Data Analysis Dashboard is designed to offer a comprehensive overview of loan data. It includes visualizations and metrics that help understand loan distribution, customer 
    profiles, loan performance, and associated risks. This project aims to assist lenders and financial analysts in making informed decisions based on customer risk and loan trends.

The dashboard covers:

      Loan approval rates across different regions
      Customer risk profiles based on income, employment, and credit history
      Loan performance metrics, including interest rates, payment terms, and loan status
      
Data Description

The loan dataset contains the following key columns:

        id: Loan identifier
        address_state: Borrower's state
        application_type: Type of loan application (individual or joint)
        emp_length: Employment length of the borrower
        emp_title: Job title of the borrower
        grade: Loan grade assigned by the lender
        home_ownership: Home ownership status
        issue_date: Date the loan was issued
        loan_status: Current status of the loan
        loan_amount: Amount of the loan
        int_rate: Interest rate on the loan
        term: Loan term in months (36 or 60)
        annual_income: Annual income of the borrower
        dti: Debt-to-income ratio
        total_payment: Total amount paid by the borrower
        
The dataset has been cleaned and processed to ensure accurate analysis.

Analysis

The key focus of the analysis includes:

        Loan Distribution by Purpose: Analyzing the reasons customers apply for loans and categorizing the loan amounts accordingly.
        Loan Performance: Tracking loans based on their status (e.g., fully paid, charged-off, late).
        Customer Risk Profiling: Evaluating risk based on customer attributes such as income, employment length, and credit history.
        Loan Amount Distribution: Grouping loan amounts into levels/grades to analyze trends based on loan size.
    
Key Metrics

Some key metrics explored in this project are:

      Loan Amount Distribution: Grouped by grade and purpose.
      Interest Rate Distribution: Analyzing the impact of loan grades on interest rates.
      Loan Approval Rates: Based on region and customer profile.
      Risk Analysis: Determining risk categories based on debt-to-income ratio (DTI) and loan performance.

Visualizations

The dashboard contains several visualizations for better interpretation of the loan data:

        Funnel Chart: Loan distribution by purpose.
        Bar Charts: Loan distribution by state and term.
        Pie Charts: Loan grade distribution.
        Risk Analysis Chart: Breakdown of customer risk profiles.

How to Use

        Open the Loan Data Analysis Dashboard in Excel to explore the visualizations and metrics.
        Modify the dataset as needed or refresh the dashboard to reflect updated data.

Future Improvements

In future iterations, the project could be expanded by:

      Incorporating machine learning models to predict loan defaults.
      Adding interactive visualizations using tools like Power BI or Tableau.
      Enhancing the dashboard with more financial metrics such as ROI and loan profitability analysis.
