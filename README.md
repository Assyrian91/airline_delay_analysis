 ✈️ Airline Delay and Cancellation Analysis (2009–2018)

## Project Overview
This project is a comprehensive analysis of U.S. airline performance from 2009 to 2018, using a large dataset of over 60 million rows. The project aims to understand the patterns of delays and cancellations and to build a simple machine learning model to predict average arrival delay.

## Project Goals
- **Big Data Handling:** Employ efficient techniques to process large-scale data without overwhelming system memory.
- **Exploratory Data Analysis (EDA):** Uncover seasonal and yearly trends in delays and cancellations.
- **Airline Performance Analysis:** Compare the performance of different airline carriers over the decade.
- **ML Modeling:** Create a linear regression model to predict the average arrival delay.

📦 Dataset
- Source: [Kaggle – Airline Delay and Cancellation Data](https://www.kaggle.com/datasets)
- Contains over 60 million records across 10 years
- Each file represents one year of domestic U.S. flights
- 
##Airline Performance Analysis & Predictive Modeling (2009-2018)

## Methodology
1.  **Data Preprocessing:** The large dataset was loaded in chunks to manage memory, then cleaned and aggregated by year and by airline carrier.
2.  **Exploratory Data Analysis (EDA):** `Matplotlib` and `Seaborn` were used to create visualizations showing:
    * Annual average delays, identifying 2014 as a significant outlier.
    * Total annual cancelled flights.
    * Performance comparisons of each airline in terms of delays and cancellations.
3.  **Modeling:** A `Linear Regression` model from `scikit-learn` was used to predict average arrival delay based on total cancellations.

## Key Findings
-   **2014** had the highest average delays and cancellations over the decade.
-   There is a **positive correlation** between an airline's average delay and its total cancelled flights.
-   The simple linear model's performance was weak (R2 Score close to zero), suggesting that the relationship between the two variables is **not strongly linear**.


## Technologies Used
-   **Python**
-   **Pandas**
-   **Numpy**
-   **Matplotlib**
-   **Seaborn**
-   **scikit-learn**
-   
Data Analyst | Hotel Management Background | Passionate about storytelling through data | ML
📫 [LinkedIn Profile]: http://linkedin.com/in/khoshaba-odeesho-17b5b92aa
