# LoanRiskIndicators
This repository contains an analysis of potential loan risk indicators based on financial data from the PKDD 99 competition. The objective is to identify key factors that can predict the likelihood of good or bad loans. The analysis focuses on two parameters:

    Hypothesis 1: The presence of a disponent (2nd client under the same account_id) is expected to have a positive influence on loan outcomes.
    Hypothesis 2: The monthly variation in the debtor's credit (income) is expected to influence loan outcomes.

The analysis involved the following steps:

    Data was loaded into MariaDB and cleaned.
    Relevant tables and attributes were identified.
    SQL code was used to filter the data and generate results.
    The resulting table was exported to Excel/Pandas for visualization.

The findings suggest that both the presence of a disponent and monthly credit variation are crucial indicators for loan risk assessment. Accounts with a disponent had a 0% bad loan rate, while accounts without a disponent had a 14% bad loan rate. Higher monthly credit variation indicates increased risk of bad loans.

This repository provides code snippets and insights for lenders to make more informed decisions and reduce the risk of bad loans. Feel free to use the code and findings for your own loan risk assessment projects.

Please note that this repository is for educational and research purposes only.
