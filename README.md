# IBM Data Science Capstone Project: Predicting SpaceX Falcon 9 Launch Success

Welcome to the repository for my capstone project under the IBM Data Science Professional Certificate. This Readme provides an overview of the project's goals, structure, and installation instructions.

## Project Overview

This capstone project aims to apply the skills acquired during the IBM Data Science Professional Certificate program to a real-world problem: predicting the success of SpaceX Falcon 9 rocket launches. Utilizing historical launch data from various sources, I developed a machine learning model to estimate the probability of success for future launches.

### Sources of Data
The dataset was compiled using:
- The SpaceX API
- NASA's website
- A Kaggle dataset on SpaceX launches

Python was used for data extraction and cleaning with Pandas. Below are the key components:

#### Data Extraction
- [**DataCollection.ipynb**](https://github.com/nalapalu/IBM_Data_Science_Capstone/blob/main/DataCollection.ipynb): Demonstrates data extraction via an API.
- [**WebScraping.ipynb**](https://github.com/nalapalu/IBM_Data_Science_Capstone/blob/main/WebScraping.ipynb): Showcases web scraping techniques.

#### Data Wrangling
- [**Data_Wrangling.ipynb**](https://github.com/nalapalu/IBM_Data_Science_Capstone/blob/main/Data_Wrangling.ipynb): Focuses on cleaning, handling missing values, and transforming data for analysis.

#### Exploratory Data Analysis (EDA)
Performed to understand the dataset and explore relationships between features and the target variable. Visualizations were created using matplotlib and seaborn.
- [**EDA.ipynb**](https://github.com/nalapalu/IBM_Data_Science_Capstone/blob/main/EDA.ipynb): Performed Exploratory data analysis with pandas, Numpy, Seaborn, matplotlib
- [**EDA_sql.ipynb**](https://github.com/nalapalu/IBM_Data_Science_Capstone/blob/main/EDA_SQL.ipynb): EDA using SQL queries.

#### Interactive Analytics
- [**Visualization.ipynb**](https://github.com/nalapalu/IBM_Data_Science_Capstone/blob/main/Visualization.ipynb): Geospatial visualizations using Folium and  Interactive visual analytics with Plotly.

### Machine Learning Model

A machine learning model was developed to predict launch success. Various algorithms were tested, including logistic regression, decision trees, and random forests. The best-performing model was a Logistic model with an accuracy of 94.4%. Performance metrics such as accuracy, precision, recall, and F1 score were used for evaluation.
- [**Machine_Learning_Prediction.ipynb**](https://github.com/nalapalu/IBM_Data_Science_Capstone/blob/main/Machine_Learning_Prediction.ipynb): Focuses on machine learning predictions.

### Key Findings

[Slide Deck with results](https://github.com/nalapalu/IBM_Data_Science_Capstone/blob/main/Final_assignment.pdf)
#### Decision Tree Model Insights
- The model achieved an 87.7% accuracy rate.
- KSC launch site had the highest success rates, likely due to stable environmental conditions.
- Launch success rates improved over time as providers refined their procedures.
- Payloads over 6000kg were less successful, possibly due to increased difficulty and susceptibility to weather.

## Installation

To run this project, ensure you have Python installed along with the following libraries:
- pandas
- matplotlib
- seaborn

Clone the repository using:
```
git clone https://github.com/nalapalu/IBM_Data_Science_Capstone
```

Install dependencies via pip or within a virtual environment. Execute Jupyter notebooks in the order specified to replicate the project workflow.

## Conclusion

The decision tree model identified key factors influencing launch success, providing valuable insights for improving launch procedures. This project demonstrates the potential of machine learning in predicting SpaceX rocket launch outcomes, aiding in enhancing safety and reducing operational costs.

Thank you for exploring this project!
