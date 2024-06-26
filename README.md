# Analysis and Insights of AI and ML Job Listings in the USA (2022-2024)

## Project Overview

This project aims to analyze AI and ML job listings in the USA from 2022 to 2024. By leveraging data analysis and visualization techniques, the project provides insights into trends, demands, and opportunities in the AI/ML job market. The analysis includes trend identification, skills gap analysis, geospatial distribution, and demand forecasting.

## Dataset Description

The dataset contains AI and ML job listings across the USA from 2022 to 2024. It includes detailed information on job titles, locations, company names, descriptions, application counts, contract types, experience levels, work types, and sectors.

- **Dataset Link**: [AI and ML Job Listings USA](https://www.kaggle.com/datasets/kanchana1990/ai-and-ml-job-listings-usa)
- **Report Link**: [Analysis and Insights of AI and ML Job Listings in the USA (2022-2024)](https://docs.google.com/document/d/1oomwyxAqyhYBfC7lWeLgY0T7hNPHwh3sCR0Sf0S4gWs/edit?usp=sharing)
- 
### Columns

- **title**: Job title (e.g., AI/ML Engineer)
- **location**: Job location (e.g., New York, NY)
- **publishedAt**: Date the job was published
- **companyName**: Company offering the job
- **description**: Detailed job description
- **applicationsCount**: Number of applications received
- **contractType**: Type of contract (e.g., Full-time)
- **experienceLevel**: Required experience level (e.g., Mid-Senior level)
- **workType**: Type of work (e.g., Engineering and Information Technology)
- **sector**: Industry sector of the job

## Data Preprocessing

### Handling Missing Values

- Filled missing `publishedAt` with `'Unknown Date'` and converted to datetime format. Dropped rows with `NaT`.
- Filled missing `companyName` with `'Unknown Company'`.
- Filled missing `sector` with `'Unknown Sector'`.

### Data Transformation

- Converted `publishedAt` to datetime format.
- Extracted numeric values from `applicationsCount` and converted to integers.

## Exploratory Data Analysis (EDA)

### Number of AI/ML Job Listings Over Time

A line chart showing the trend in the number of AI/ML job listings over time. The data reveals a significant increase in job postings towards the end of the period, with a noticeable spike around April 2024.

### Contract Type by Experience Level

A bar chart visualizing the distribution of different contract types across various experience levels. Full-time positions dominate the job listings, especially for Mid-Senior level roles.

### Top 15 Sectors for AI/ML Job Listings

A horizontal bar chart identifying the top 15 sectors with the most job listings. The 'Software Development' sector had the highest number of job listings.

### Wordcloud for Job Descriptions

A word cloud highlighting the most frequently occurring words in the job descriptions. Common terms included 'machine learning', 'experience', 'team', 'data', 'model', and 'Python'.

### Distribution of Applications Count

A histogram with a KDE overlay showing the distribution of the number of applications received for AI/ML job listings. The distribution revealed peaks around 25 and 200 applications.

## Key Insights

1. **Trend Analysis**:
   - Significant increase in AI/ML job listings over time, with a sharp spike around April 2024.
   - Full-time positions are the most common, especially for Mid-Senior level roles.

2. **Sector Analysis**:
   - The 'Software Development' sector has the highest demand for AI/ML professionals.
   - High demand in sectors like IT Services and IT Consulting, and Technology, Information and Internet.

3. **Skills and Qualifications**:
   - Common requirements include machine learning skills, experience, teamwork, data handling, model development, and proficiency in Python.
   - Certain job listings attract significantly more applications than others, highlighting competitive roles.

## Conclusion and Recommendations

### Summary

The analysis provides valuable insights into the AI/ML job market in the USA, highlighting the growing demand for AI/ML professionals, especially in the software development and IT sectors. Full-time roles dominate the market, with a significant emphasis on Mid-Senior level positions.

### Future Work

1. **Geospatial Analysis**: Map job opportunities across different regions in the USA to identify hotspots.
2. **Demand Forecasting**: Use time series models to predict future job postings.
3. **Skills Gap Analysis**: Analyze the gap between the required and available skills in the job market.

### Recommendations

1. **For Job Seekers**: Focus on acquiring skills in machine learning, Python, and data handling. Target sectors with high demand, such as software development and IT consulting.
2. **For Employers**: Highlight key skills and experience required in job listings to attract suitable candidates. Consider offering competitive salaries to stand out in the market.

## Repository Structure

