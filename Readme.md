# MLOPS CodePro EdTech Assignment

## Overview

This repository contains the MLOPS CodePro EdTech Assignment, which focuses on implementing Machine Learning Operations (MLOps) principles in an educational technology context.

## Table of Contents

- [Project Description](#project-description)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Project Description

[Provide a brief description of the project, its goals, and the problem it aims to solve in the EdTech domain using MLOps practices.]

## Installation

To set up this project locally, follow these steps:

1. Clone the repository:
   git clone https://github.com/kapasitejas/Codepro-EdTech-Lead-Scoring-Classification-MLOps-Assignment
2. Navigate to the project directory:
   cd MLOPS-CodePro-EdTech-Assignment
3. [Add any additional setup steps, such as installing dependencies, setting up virtual environments, etc.]

## Customer Acquisition Cost (CAC)

The Customer Acquisition Cost (CAC) is a key metric that measures the total cost of acquiring a new customer. It is calculated using the following formula:

CAC = (Total Marketing Expenditure + Sales Expenditure) / Total Customers Gained

This metric helps businesses understand how much they are spending to acquire each new customer, allowing them to evaluate the efficiency of their marketing and sales efforts.

## The key points are:

1. High initial costs are often necessary to build a customer base and brand awareness.
2. As businesses grow and establish themselves, they can start focusing more on profitability.
3. Once brand awareness is generated and the business grows organically, companies often transition to charging for their services.
4. The long-term goal is to reduce customer acquisition costs over time.

# Lead Scoring for CodePro

## Main Objectives

- Eliminate junk leads by categorizing leads based on their likelihood to purchase.
- Gain insights to improve lead conversion and address improper targeting.

## Business Metric

- **Chosen Metric:** L2AC (Leads to Application Completion)
- **Reason:** L2P (Leads to Payment) might aggressively drop leads.

## Lead Generation

- Occurs when a person visits CodePro's website and enters contact details.

## Junk Leads

- **Definition:** Leads with no genuine interest in the product/service.
- **Problem:** Create inefficiency in the sales process.

## Goal of the Data Science Team

- Build a system to categorize leads based on their likelihood to purchase CodePro's course.
- **Purpose:** Remove inefficiency caused by junk leads in the sales process.

This lead scoring system aims to improve the efficiency of CodePro's sales process by identifying and prioritizing the most promising leads, ultimately leading to better resource allocation and increased conversion rates.

## Origin of a Lead

To understand the origin of a lead, we have the following information:

1. created_data: This is the timestamp identifying when a lead was created.
2. city_mapped: This is the city where a lead was generated.
3. first_platform_c: This is the place that leads users to the source - mobile web, desktop web, Android app, etc.
4. first_utm_medium_c: Mediums are broad buckets of categories that describe the type of traffic being driven to your website. For example, ‘organic’ is a medium because it encompasses traffic coming from search engines such as Google. ‘Referral’, ‘social’ and ‘paid’ are other examples of mediums.
5. first_utm_source_c: The source is where your website’s traffic comes from (individual websites, Google, Facebook, etc.). For example, think of a journey - the source would be where you came from, and the medium would be the mode of transport.
6. total_leads_dropped: This refers to the count of leads accessed by the user. For example, a user might browse through multiple Python courses while looking for the best course based on their requirements.
7. Referred_lead: This indicates whether a lead was referred or not.
8. interaction type columns: These capture the type of interaction a user had with the CodePro website. For example, the user might look at 9. payment options, syllabus, placement records, etc.
9. App_complete_flag: this is the column we are trying to predict. We are trying to understand whether a user will fill the application or not based on the information in the previous columns.

The target variable is app_complete_flag, which indicates whether a user has completed an application or not. We used L2AC as our business metric in the previous segments. Hence, we are using app_complete_flag as our target variable.
