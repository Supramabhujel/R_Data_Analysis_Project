# Statistical Regression Analysis of Height and Weight Data

Welcome to the Statistical Regression Analysis of Height and Weight Data repository! This project focuses on analyzing a dataset related to height and wages in the UK using R.


**Table of Contents**
- [Project Overview](#project-overview)
- [Data](#data)
- [Analysis](#analysis)
- [Results/Findings](#resultsfindings)
- [Conclusion](#conclusion)
- [How to Use](#how-to-use)
- [Dependencies](#dependencies)
- [References](#references)

## Project Overview

The project structure is designed to provide a comprehensive analysis of the dataset. Here's what you'll find:

- **Analysis.Rmd**: This R Markdown file contains the code and analysis for the statistical regression analysis. It includes tasks such as data summarization, visualization of relationships, data filtering, and regression analysis.
  

## Data

The dataset used in this analysis is "Height_and_Wages_UK.dta", which provides information on height, wages, and gender for individuals in the UK.

## Analysis

The analysis consists of several key components:

1. **Data Summarization**: Descriptive statistics, including mean, standard deviation, and distribution plots for height and wages, are provided.
2. **Visualization of Relationships**: Scatterplots are created to visualize the relationship between height and wages.
3. **Data Filtering**: The dataset is filtered to exclude outliers and extreme values.
4. **Regression Analysis**: Linear regression models are estimated to analyze the relationship between height and wages.

## Results/Findings

1. Dataset: Information on height, wages, and gender for individuals in the UK.
2. Wages: Average £10.39 per hour, ranging from £0.12 to £2500.00 per hour.
Height: Average 69.40 inches, ranging from 22.44 to 79.53 inches.
Analysis:
3. Scatterplot shows a clustered distribution of height vs. wages, with noticeable outliers.
Filtered dataset maintains average height but sees a decrease in average wage.
---
![Screenshot 2024-03-24 at 8 53 58 PM](https://github.com/Supramabhujel/Statistical-Regression-Analysis-of-Height-and-Wage-Data/assets/164811033/26aff98d-88b4-46c7-abcf-6ad624331c5e)

---

5. Regression Analysis:
Each additional inch in height associates with an increase in wages by £0.245 per hour in the full sample and £0.268 per hour in the filtered sample.
6. Significance:
Height's effect on wages is statistically significant only in the filtered sample.
Confidence intervals confirm a positive effect of height on wages in the filtered sample.

## Conclusion:
Height positively correlates with wages, especially in the filtered sample. Further analysis may elucidate underlying factors.

## How to Use

To reproduce the analysis:

1. Clone this repository to your local machine.
2. Open the "Analysis.Rmd" file in RStudio or any R Markdown editor.
3. Run the code chunks sequentially to reproduce the analysis.
4. Feel free to modify the code or add your own analysis as needed.

## Dependencies

The analysis requires the following R packages:

- tidyverse
- stargazer
- ggrepel
- summarytools
- haven

If you haven't already installed these packages, you can do so using `install.packages()`.

## References 

- Real econometrics "THE RIGHT TOOLS TO ANSWER IMPORTANT QUESTIONS" SECOND EDITION by Michael A. Bailey 📖

