# 📈 Stock Market Analysis & Prediction 🚀

A comprehensive analysis of major tech stocks (AAPL, GOOG, MSFT, NFLX) using Python, featuring Exploratory Data Analysis, feature engineering, and a predictive machine learning model.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-%23ffffff.svg?style=for-the-badge&logo=seaborn&logoColor=black)

---

## 🌟 Project Overview

This project dives deep into the historical stock data for four tech giants: **Apple (AAPL)**, **Google (GOOG)**, **Microsoft (MSFT)**, and **Netflix (NFLX)**. The notebook provides a complete walkthrough of the data analysis process—from data wrangling and feature engineering to insightful visualizations and building a machine learning model to forecast stock prices.

The analysis covers data from **February 7, 2023, to May 5, 2023**.

---

## ✨ Key Features

-   **🧹 Data Preparation:** Loads the `stocks.csv` dataset, handles data types, and prepares it for analysis.
-   **🔧 Feature Engineering:** Creates insightful new features to enhance the analysis, such as:
    -   Daily Returns (%)
    -   Moving Averages (7, 14, & 30-day)
    -   Volatility (14-day rolling standard deviation)
-   **📊 Exploratory Data Analysis (EDA):** Dives into key metrics like total return, daily return, and volatility for each stock.
-   **🔗 Correlation Analysis:** Visualizes the correlation matrix between the closing prices of the four stocks.
-   **🤖 Machine Learning Model:** Implements and evaluates two regression models (Linear Regression & Random Forest) to predict stock prices.

---

## 🎨 Visualizations

A comprehensive 10-plot dashboard brings the analysis to life, summarizing all key trends and insights.


### The dashboard includes:
1.  **Stock Price Trends**: Closing prices over time.
2.  **Moving Averages (AAPL)**: Price vs. 7, 14, & 30-day MAs.
3.  **Daily Returns Distribution**: Histogram of daily returns.
4.  **Volatility Comparison**: Bar chart of average 14-day volatility.
5.  **Trading Volume**: Volume trends over time.
6.  **Correlation Heatmap**: Visualizing price correlations.
7.  **Price Distribution**: Box plots comparing price ranges.
8.  **Cumulative Returns**: Tracking investment growth over the period.
9.  **Risk vs. Return**: A scatter plot mapping risk against average daily return.
10. **Daily Price Range**: The daily high-low price spread.

---

## 🧠 Machine Learning Model

A model was developed to predict the **Close** price for **AAPL** stock.

| Model                     | R² Score |
| ------------------------- | :------: |
| **Linear Regression** | **0.9120** ✅ |
| **Random Forest Regressor** | 0.7789   |

The **Linear Regression model** provided the best performance on this dataset. The Random Forest model highlighted that `Low` and `High` prices are the most important features for prediction.

---

## 💡 Key Insights

-   🏆 **Best Performer:** **MSFT** showed the highest growth with a **16.10%** total return.
-   🎢 **Most Volatile:** **NFLX** exhibited the highest volatility, with an average 14-day price swing of **$11.28**.
-    busiest trader:**AAPL** was the most traded stock, with an average daily volume of over **60 million**.

---

## 🛠️ Technologies Used

* Python
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn

---

## 🚀 How to Run

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
    ```
2.  **Install the dependencies:**
    ```sh
    pip install pandas numpy matplotlib seaborn scikit-learn jupyter
    ```
3.  **Place the dataset:** Make sure the `stocks.csv` file is in the same directory.
4.  **Launch the notebook:**
    ```sh
    jupyter notebook Stock_Market.ipynb
    ```

---

Feel free to explore the notebook, run the analysis, and build upon it!
