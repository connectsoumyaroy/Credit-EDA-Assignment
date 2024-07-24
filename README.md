# Credit EDA Case Study

## Overview

Welcome to the Credit EDA Case Study repository! This project focuses on applying Exploratory Data Analysis (EDA) to real-world business scenarios in the banking and financial services sector. The goal is to understand and analyze the patterns in loan applications to help minimize the risk associated with lending.

## Problem Statement

Loan-providing companies often face challenges when assessing loan applications due to insufficient or non-existent credit histories. This scenario can lead to some clients exploiting the system and becoming defaulters. In this case study, we aim to use EDA techniques to analyze loan application data and develop a basic understanding of risk analytics in finance.

**Business Challenge:**

When evaluating a loan application, a company must make decisions based on the applicant’s profile. Two primary risks are involved:
1. **Business Loss Risk**: Not approving a loan to a capable applicant results in a loss of business.
2. **Financial Risk**: Approving a loan to an applicant who is likely to default could lead to financial loss.

The data provided includes information about loan applications, distinguishing between:
- Clients with payment difficulties (late payments on at least one of the first few installments)
- Clients who have paid on time.

### Decision Categories

There are four possible outcomes for a loan application:
1. **Approved**: The loan application is approved.
2. **Cancelled**: The client cancelled the application, possibly due to changing their mind or receiving unfavorable terms.
3. **Refused**: The loan application was rejected due to not meeting the company’s criteria.
4. **Unused Offer**: The loan was cancelled by the client at different stages of the process.

## Business Objectives

The objective of this case study is to identify patterns that indicate whether a client is likely to default on their payments. This analysis will guide the company in making informed decisions regarding loan approval, loan amount adjustments, and interest rates. Understanding the key factors that drive loan defaults will enhance the company's risk assessment and portfolio management.

### Goals
- **Identify Default Indicators**: Use EDA to determine which variables strongly indicate the likelihood of default.
- **Improve Risk Assessment**: Leverage insights to improve decision-making processes and minimize financial risks.

## Data Description

Download the dataset from the link below:

[Download Dataset](https://drive.google.com/open?id=16RQztUqCfJOlbooHqYlJrp6Q7iL65uZB)

The dataset comprises three files:
1. **application_data.csv**: Contains client information at the time of application, including details on payment difficulties.
2. **previous_application.csv**: Provides data on the client's previous loan applications and their outcomes (Approved, Cancelled, Refused, or Unused offer).
3. **columns_description.csv**: A data dictionary that describes the variables used in the dataset.

## Getting Started

1. **Clone this Repository**:
   ```bash
   git clone https://github.com/username/repository.git
# Credit-EDA-Assignment
