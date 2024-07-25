# Analysis of Coal Supply and Consumption in India

## Overview

This project aims to analyze coal production and consumption patterns in India using big data analytics techniques such as Random Forest Regression and Gradient Boosting Regressor. The goal is to extract valuable insights and develop strategies for sustainable energy management.

## Introduction

Coal, a sedimentary rock formed from ancient plant remains, plays a crucial role in the global energy landscape. It is the most significant and abundant fossil fuel in India, meeting 55% of the nation's energy needs. However, increasing coal usage has led to significant environmental and ecological concerns. This study aims to analyze coal production and consumption in India to inform energy security, guide policy on energy diversification, and develop sustainable energy strategies.

### Data Set

- **Coal Supply Dataset (570 rows):** Information on coal supply from government sources within India from 2011 to 2020.
- **Coal Consumption Dataset (1958 rows):** Information on coal consumption across different states, sectors, and coal types in India from 2011 to 2020.

### Data Preprocessing

- Handling missing data using imputation techniques.
- Isolating the target variable (coal consumption) from feature variables.
- One-hot encoding categorical variables.

### Model Training and Evaluation

- Splitting data into training (2011-2018) and testing (2019) sets.
- Training Random Forest Regression and Gradient Boosting Regressor models.
- Evaluating model performance using Mean Squared Error (MSE) and R-squared metrics.

### State-wise and Year-wise Predictions

- Generating state-wise and year-wise predictions using the trained Random Forest Regressor.
- Analyzing patterns, trends, and potential outliers in coal consumption across different states and years.
  ![coal-supply-over-year](https://github.com/vaidik24/BigData-Project/blob/main/images/coalsupplyoveryears.jpg)
  ![coal-consumption-over-year](https://github.com/vaidik24/BigData-Project/blob/main/images/coalconsuptionoveryears.jpg)

## Analysis

The Random Forest Regressor outperformed the Gradient Boosting Regressor in predicting coal consumption and supply, with R-squared scores of 0.93 and 0.95 for consumption and supply, respectively. The analysis also includes state-wise and year-wise predictions, highlighting patterns in coal usage across different regions.

## Results and Discussion

The study's findings emphasize the effectiveness of advanced machine learning techniques in analyzing complex energy datasets. The state-wise and sector-wise predictions can guide policymakers in resource allocation, energy diversification, and environmental mitigation strategies.

## Conclusion and Future Scope

This study demonstrated the use of big data analytics and machine learning approaches to gain insights into India's coal sector. Future studies could incorporate new data sources, examine the impact of policy interventions, and explore alternative fuels to provide a comprehensive view of India's energy landscape.

## Interactive Dashboards

Interactive dashboards were developed using Power BI to visualize coal supply and consumption across states, years, and sectors. These dashboards enable dynamic data exploration, empowering stakeholders to make informed decisions.
