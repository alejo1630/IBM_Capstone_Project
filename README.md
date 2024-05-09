# IBM Capstone Project: Predictive Analysis for Space Y Rocket Launches

## 🔰 Description
This project aims to leverage predictive analytics to forecast the outcomes of rocket launches for Space Y, a new player in the commercial space industry. By harnessing machine learning algorithms and comprehensive data analysis, the goal is to enhance decision-making processes and optimize launch operations.

## 🔱Methodology
1. **Data Collection:**
    - **API Data Collection:** Utilized SpaceX API to gather information on past rocket launches.
    - **Web Scraping:** Extracted data from relevant websites such as Wikipedia to supplement the dataset.
2. **SQL Queries:**
    - Conducted SQL queries to perform data exploration and gather insights into launch sites, payloads, and mission outcomes.
3. **Exploratory Data Analysis (EDA):** 
    - Utilized SQL queries for initial data exploration.
    - Conducted further EDA using pandas and matplotlib to visualize and analyze the dataset.
4. **Data Preprocessing:**
    - Created a column for the launch outcome class.
    - Standardized the data to ensure consistency.
    - Split the dataset into training and test subsets.
5. **Geospatial Analysis with Folium:**
    - Used Folium to visualize the locations of launch sites and mission outcomes on an interactive map.
6. **Dashboard Creation with Dash:**
    - Developed an interactive dashboard using Dash to provide stakeholders with real-time insights into launch data.
7. **Model Selection:**
    - Explored various machine learning algorithms including Logistic Regression, Support Vector Machines (SVM), Classification Trees, and K-Nearest Neighbors (KNN).
    - Tuned hyperparameters for each model using techniques like grid search.
8. **Model Evaluation:**
    - Evaluated model performance using test data through cross-validation, confusion matrix analysis, and classification scoring metrics.

## ✅ Model Performance
- Logistic Regression accuracy: 0.846
- SVM accuracy: 0.848
- Classification Tree accuracy: 0.873
- KNN accuracy: 0.848

## 🔶 Conclusions
All models demonstrated strong performance, with accuracy scores ranging from approximately 84.6% to 87.3%. While each model proved effective in predicting launch outcomes, the Classification Tree model emerged as the top performer with the highest accuracy. These results highlight the efficacy of predictive analytics in optimizing rocket launch operations for Space Y, enabling informed decision-making and enhancing overall efficiency. The successful completion of this project underscores the critical role of preprocessing techniques, including data collection, data wrangling, exploratory data analysis (EDA), and data visualization, in the predictive analysis of rocket launches for Space Y. Through meticulous data collection efforts utilizing APIs and web scraping, we obtained a comprehensive dataset essential for training and evaluating predictive models. The preprocessing phase involved various steps such as handling missing values, standardizing the data, and splitting it into training and test sets, ensuring the data's quality and integrity. Additionally, EDA techniques, including SQL queries and visualization tools like Folium, provided invaluable insights into launch site distribution, mission outcomes, and payload characteristics. These insights guided model selection and hyperparameter tuning, leading to the development of robust predictive models. Overall, the success of this project highlights the importance of a thorough preprocessing pipeline in extracting actionable insights from complex datasets and facilitating informed decision-making in the commercial space industry.
