📌 Overview

This project focuses on Exploratory Data Analysis (EDA) of loan application data to uncover the key factors linked to loan default / payment difficulties. Loan providers often struggle to evaluate applicants with limited or no credit history, which can lead to poor approval decisions. Using EDA, this case study identifies meaningful patterns in applicant profiles and previous loan behavior to support better risk assessment and smarter lending decisions.

🎯 Problem Statement

When a bank receives a loan application, it must decide whether to approve the loan based on the applicant’s profile. This decision carries two major business risks:

✅ Loss of Business (False Rejection): Rejecting applicants who are actually likely to repay results in lost revenue and customers.

❌ Financial Loss (False Approval): Approving applicants who are likely to default can lead to major financial losses.

The goal of this project is to use EDA to find the key driver variables behind default, enabling the lender to take actions such as:

- rejecting highly risky applicants,

- reducing loan amounts for risky profiles,

- offering loans at higher interest rates based on risk,

- improving overall portfolio quality without rejecting genuine borrowers.

🗂️ Dataset Overview

This analysis uses two datasets:

1) application_data.csv

- Contains information about the client at the time of application, including demographic and financial details.

- Purpose: Identify patterns indicating whether an applicant is likely to face payment difficulties.

2) previous_application.csv

- Contains the client’s previous loan application history and its outcomes.

- Includes outcomes like: Approved, Cancelled, Refused, Unused offer

- Purpose: Understand how past application history and outcomes relate to current default risk.

🔧 Data Preparation & EDA (Summary)

- Dropped columns with >40% missing values.

- Renamed columns for better readability.

- Imputed missing values using mean (numeric) and mode (categorical).

- Performed required feature/column transformations (cleaning + formatting).

- Conducted univariate and bivariate analysis to uncover patterns.

- Analyzed correlations to understand relationships and key drivers.
