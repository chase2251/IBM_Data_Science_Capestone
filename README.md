# IBM Data Science Capstone Project

Welcome to the repository for my IBM Data Science Professional Certificate capstone project. This project encapsulates a comprehensive journey through the data science lifecycle, demonstrating my skills and knowledge acquired during the course.


## Overview
In this capstone project, I focused on analyzing data from SpaceX to predict the success of Falcon 9 rocket landings. The project involves data collection, wrangling, exploratory data analysis (EDA), interactive visualizations, and predictive modeling.


## Project Objectives
* **Predict the likelihood of successful Falcon 9 landings:** Utilizing various data points, the goal was to accurately predict landing outcomes, which in turn can estimate launch costs and enhance competitive strategies in the space industry.
* **Analyze correlations:** Identify key factors that correlate with successful landings and understand their impact on the overall mission outcomes.
* **Interactive Visual Analytics:** Develop interactive dashboards and maps to visualize the data and results effectively.


## Methodology

### Data Collection
* **SpaceX API:** Retrieved comprehensive launch data including flight numbers, dates, payloads, launch sites, and outcomes.
* **Web Scraping:** Supplemented data with additional details from Wikipedia.

### Data Wrangling
* Cleaned and processed the data, converting landing outcomes into training labels.
* Calculated various metrics such as launch success rates and payload statistics.

### Exploratory Data Analysis (EDA)
* **Visualization:** Created scatter plots, bar charts, and line charts to explore relationships between variables.
* **SQL Queries:** Performed SQL-based EDA to extract insights from the dataset.

### Interactive Visualizations
* **Folium Map:** Displayed launch sites and their outcomes on an interactive map.
* **Plotly Dash:** Developed a dashboard with pie and scatter charts to explore the data dynamically.

### Predictive Modeling
* Built and evaluated classification models (SVM, Decision Trees, Logistic Regression) to predict landing outcomes.
* Achieved an accuracy of 83% on the test data, indicating a strong predictive performance.


## Dashboards and Visualizations

### Dashboard Overview
* **Launch Success Distribution:** A pie chart showing the distribution of successful launches across different sites.
* <img width="311" alt="Launch Success Distribution Pie Chart" src="https://github.com/chase2251/IBM_Data_Science_Capestone/assets/95754766/43afc3ab-c0e4-485d-8418-4c3378464866">

* **Payload vs. Outcome:** A scatter plot examining the relationship between payload mass and landing success.
* <img width="514" alt="Payload vs Outcome Scatter_plot" src="https://github.com/chase2251/IBM_Data_Science_Capestone/assets/95754766/0045767f-4a92-48ff-90b9-a97fec07ce75">

### Folium Map
Interactive map showcasing all launch sites and their outcomes, highlighting the geographical patterns and proximities to key infrastructure.

### Predictive Analysis Results
* Models were trained to classify successful and unsuccessful landings.
* The decision tree classifier emerged as the most effective model with an accuracy of 83.33%.


## Conclusion
The capstone project demonstrates a full-cycle data science project, from data acquisition and cleaning to interactive visualizations and predictive modeling. The findings provide valuable insights into factors influencing rocket landing successes, contributing to the broader field of aerospace analytics.


## Repository Structure
* **data/:** Contains the datasets used in the project.
* **notebooks/:** Jupyter notebooks for data collection, wrangling, EDA, and modeling.
* **dashboard/:** Code for the Plotly Dash interactive dashboard.
* **maps/:** Folium map visualizations.
* **reports/:** Final project report and documentation.


  
