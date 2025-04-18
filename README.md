# DATA 301 Final Project: Analyzing the Evolution of AI Models

## Group 4 Members
- William Kennedy  
- Reiya Aono  
- Lucas Spitzer  
- Vinod George

## Table of Contents
- [Project Overview](#project-overview)
- [Research Questions](#research-questions)
- [Dataset Description](#dataset-description)
- [Tools and Technologies](#tools-and-technologies)
- [Data Cleaning and Processing](#data-cleaning-and-processing)
- [Planned Visualizations](#planned-visualizations)
- [Member Contributions](#member-contributions)
- [Links to Data](#links-to-data)

## Project Overview

This project explores the evolution of artificial intelligence through the analysis of the "Notable AI Models" dataset from Epoch AI. Our goal is to gain insights into the trajectory of AI, identify key players in the space, and understand performance trends across various tasks and benchmarks.

By examining over 900 notable AI models and benchmarking results, we aim to answer pressing questions about who is leading in AI innovation and what factors drive progress in this field.

## Research Questions

- Which corporation leads the AI world in terms of reliability and progress?
- Which company or model currently performs best overall?
- What AI models excel at specific tasks such as mathematics, coding, and modeling?

## Dataset Description

We are using two datasets from [Epoch AI](https://epoch.ai):

- **Notable AI Models Dataset**  
  Tracks over 900 state-of-the-art, highly cited, or historically significant AI models. Includes data on model name, release year, organization, and estimated compute.

  URL: https://epoch.ai/data/notable-ai-models?view=table

- **Benchmarking Dataset**  
  Contains performance scores from internal Epoch AI evaluations on tasks like math, coding, reasoning, and more.

  URL: https://epoch.ai/data/ai-benchmarking-dashboard?view=table

Both datasets are available as downloadable CSV files, making them easy to import and manipulate using Pandas.

## Tools and Technologies

- **Programming Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Visualization Libraries:** Matplotlib, Seaborn, Ggplot
- **Environment:** Jupyter Notebook

## Data Cleaning and Processing

- Initial data exploration showed that the datasets are relatively clean.
- We will:
  - Use `fillna()` to handle missing values with mean or mode depending on the variable type.
  - Possibly engineer new columns, such as an "overall score" combining performance metrics across different tests.
  - Filter and select only relevant columns for analysis.

## Planned Visualizations

We will use a variety of plots to answer our research questions:
- Line plots to show trends in model capabilities over time.
- Bar plots and scatter plots to compare model and organization performance.
- Heatmaps to visualize correlations between variables.

## Member Contributions

Each team member will explore the dataset from different angles based on a specific sub-question. Responsibilities are informally divided as follows:

- **Data Cleaning and Merging:** One team member will lead efforts to clean and preprocess the dataset.
- **Sub-question Analysis:** Each member will contribute one or more sub-questions that feed into the broader research goals.
- **Visualization:** Multiple members will create plots using different visualization libraries.

### Individual Focus Areas

- **William Kennedy:** [To be filled after contribution]
- **Reiya Aono:** [To be filled after contribution]
- **Lucas Spitzer:** [To be filled after contribution]
- **Vinod George:** [To be filled after contribution]

## Links to Data

- Notable AI Models: https://epoch.ai/data/notable-ai-models?view=table  
- AI Benchmarking Dashboard: https://epoch.ai/data/ai-benchmarking-dashboard?view=table
