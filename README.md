# Fraudulent Job Posting Detection
## Overview
This project aims to detect fraudulent job postings using machine learning algorithms. The dataset contains various features related to job postings, such as job title, location, department, salary range, and more. The goal is to build and evaluate machine learning models that can accurately identify fraudulent job postings based on these features.

## Dataset

The dataset used in this project is fake_job_postings.csv, which contains the following columns:

job_id: Unique identifier for each job posting.

title: Job title.

location: Job location.

department: Department associated with the job.

salary_range: Salary range for the job.

company_profile: Company profile description.

description: Job description.

requirements: Job requirements.

benefits: Job benefits.

telecommuting: Binary feature indicating if telecommuting is allowed.

has_company_logo: Binary feature indicating if the company logo is present.

has_questions: Binary feature indicating if the job posting has questions.

employment_type: Type of employment (e.g., Full-time, Part-time).

required_experience: Required experience level (e.g., Entry level, Mid-Senior level).

required_education: Required education level (e.g., Bachelor's Degree, Master's Degree).

industry: Industry associated with the job.

function: Job function.

fraudulent: Binary target variable indicating if the job posting is fraudulent (1) or not (0).


## Exploratory Data Analysis (EDA)

Cleaned the dataset by handling missing values and filling them with appropriate values or modes.
Visualized the distribution of certain columns using box plots.
Created word clouds to visualize the most frequent words in job titles and company profiles.
Analyzed the distribution of fraudulent vs. non-fraudulent job postings.
Investigated the most common job titles and departments.
Identified the job posting with the highest salary range.
Extracted and visualized the top words used in company profiles.

## Machine Learning Models
Logistic Regression: Achieved an accuracy of approximately 95.12% but had low recall and F1-score for detecting fraudulent postings.

k-Nearest Neighbors (KNN): Achieved an accuracy of approximately 96.75% with better recall and F1-score than Logistic Regression.

Random Forest Classifier: Outperformed the other models with an accuracy of approximately 98.23%.
