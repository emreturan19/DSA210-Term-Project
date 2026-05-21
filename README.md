# DSA210 Term Project

# Analyzing the Relationship Between Trading Volume, Market Conditions, Exchange Rate Movements, and Stock Returns

---

# Project Overview

Financial markets are highly dynamic systems influenced by investor behavior, market trends, macroeconomic conditions, and external economic factors. Understanding the relationship between stock returns, trading activity, and economic indicators is an important topic in financial data science and investment analysis.

This project investigates the relationship between:
- Trading volume
- Market conditions
- Exchange rate movements
- Stock return behavior

using real-world financial datasets collected from Borsa Istanbul.

The project combines:
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Hypothesis Testing
- Financial Visualization
- Machine Learning Techniques

to analyze stock market behavior and evaluate whether financial indicators can help predict stock return movements.

The study also examines how macroeconomic factors such as exchange rate fluctuations affect stock performance across multiple sectors in Turkey.

---

# Project Objectives

The main objective of this project is to analyze whether trading activity, market performance, and exchange rate volatility have statistically significant effects on stock returns.

More specifically, the project aims to:

- Analyze the relationship between trading volume and stock returns
- Compare stock performance with the BIST100 market index
- Investigate the effect of USD/TRY exchange rate changes on stock returns
- Measure volatility behavior across sectors
- Identify patterns in stock return distributions
- Apply machine learning methods to predict stock return direction
- Compare the predictive power of financial indicators
- Evaluate sector sensitivity to market and macroeconomic conditions

The project combines financial theory with data science techniques to provide both analytical and predictive insights.

---

# Repository Structure

## Proposal
- `01_Proposal.pdf`

Contains:
- Project motivation
- Research objectives
- Research questions
- Hypotheses
- Dataset descriptions
- Planned methodology
- Expected contributions

---

## Exploratory Data Analysis Report
- `02_EDA_Report.pdf`

Contains:
- Data preprocessing steps
- Missing value analysis
- Return calculations
- Distribution analysis
- Correlation analysis
- Volatility analysis
- Cumulative return comparisons
- Financial visualizations
- Sector comparisons
- Interpretation of findings

---

## Machine Learning Report
- `03_Machine_Learning_Report.pdf`

Contains:
- Feature engineering
- Model preparation
- Logistic Regression implementation
- Model training
- Prediction analysis
- Accuracy evaluation
- Classification metrics
- Interpretation of ML results

---

## Final Project Report
- `04_Final_Report.pdf`

Contains:
- Complete project methodology
- Combined EDA and ML findings
- Statistical interpretations
- Final conclusions
- Overall evaluation of the project

---

## Jupyter Notebooks

### `05_EDA.ipynb`
Contains:
- Data collection
- Cleaning and preprocessing
- Exploratory data analysis
- Visualizations
- Statistical calculations

### `06_ML.ipynb`
Contains:
- Feature engineering
- Machine learning implementation
- Model evaluation
- Prediction analysis

### `07_Final_Code.ipynb`
Contains:
- Integrated final project workflow
- Combined EDA and ML pipeline
- Final implementation

---

# Datasets Used

The project uses real-world financial datasets collected programmatically using Python.

---

## Stock Price Data

Daily stock market data was collected for selected companies listed on Borsa Istanbul.

### Selected Companies
- THYAO.IS
- GARAN.IS
- AKBNK.IS
- ASELS.IS
- SISE.IS
- EREGL.IS

These companies were selected because they represent different sectors of the Turkish economy, allowing broader market analysis and sector comparisons.

### Variables Collected
- Open price
- Close price
- High price
- Low price
- Adjusted close price
- Trading volume

---

## Market Index Data

The BIST100 index was used to represent overall market conditions.

The market index serves as a benchmark to evaluate whether individual stock returns move consistently with overall market performance.

Using BIST100 instead of average stock returns provides a more realistic representation of market behavior.

---

## Exchange Rate Data

USD/TRY exchange rate data was included to capture macroeconomic effects on stock returns.

Exchange rate fluctuations are particularly important in emerging markets such as Turkey because they may influence:
- Investor sentiment
- Inflation expectations
- Corporate profitability
- Import/export costs
- Market volatility

Including exchange rate data strengthens the macroeconomic dimension of the project.

---

# Data Source

Financial datasets were collected using:

- Yahoo Finance API
- `yfinance` Python library

---

# Methodology

The project consists of several analytical stages.

---

# 1. Data Collection and Preprocessing

Data was collected programmatically using Python.

Preprocessing steps included:
- Handling missing values
- Date formatting
- Return calculations
- Percentage change calculations
- Feature generation
- Rolling statistics
- Lagged variables

The preprocessing stage ensured consistency and reliability before analysis.

---

# 2. Exploratory Data Analysis (EDA)

EDA was conducted to understand stock market behavior and identify relationships between variables.

---

## Distribution Analysis

The distribution of stock returns was analyzed using:
- Histograms
- Boxplots
- Descriptive statistics

This helped identify:
- Volatility patterns
- Outliers
- Return asymmetry
- Distribution behavior

---

## Correlation Analysis

Correlation matrices and heatmaps were used to examine relationships between:
- Stock returns
- Trading volume
- Market returns
- Exchange rate movements

This stage helped identify strong positive or negative relationships among variables.

---

## Volatility Analysis

Rolling volatility calculations were used to analyze:
- Market instability
- Sector sensitivity
- Risk behavior

Volatility comparisons allowed identification of more stable and more sensitive sectors.

---

## Cumulative Return Analysis

Cumulative returns were calculated to compare:
- Individual stock performance
- Market benchmark performance
- Sector trends over time

These analyses provided insight into long-term investment behavior.

---

# 3. Statistical Analysis

Statistical methods were applied to examine whether relationships between variables were statistically significant.

The statistical analysis focused on:
- Trading volume and stock returns
- Market returns and stock performance
- Exchange rate effects
- Sector comparisons

---

# Hypothesis Testing

## Null Hypothesis (H0)

Trading volume, market conditions, and exchange rate movements do not have statistically significant effects on stock returns.

## Alternative Hypothesis (H1)

Trading volume, market conditions, and exchange rate movements have statistically significant effects on stock returns.

The hypothesis testing stage evaluated whether observed relationships occurred randomly or represented meaningful financial relationships.

---

# 4. Machine Learning Analysis

Machine learning techniques were implemented to predict stock return direction.

---

## Machine Learning Model

The project used:
- Logistic Regression

The goal was to classify whether the next day’s stock return would be:
- Positive
- Negative

---

## Features Used

The machine learning model used:
- Trading volume
- Lagged returns
- Market returns
- Exchange rate returns
- Volatility indicators
- Rolling averages

---

## Machine Learning Workflow

1. Feature engineering
2. Data preprocessing
3. Train-test split
4. Model training
5. Prediction generation
6. Model evaluation
7. Interpretation of results

---

# Visualization Techniques

The project includes multiple financial visualizations such as:
- Histograms
- Correlation heatmaps
- Line charts
- Boxplots
- Cumulative return graphs
- Volatility plots

These visualizations improve interpretability and support analytical findings.

---

# Technologies Used

## Programming Language
- Python

---

## Python Libraries
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- yfinance

---

## Platforms
- Google Colab
- GitHub

---

# Key Findings

The project identified several important findings:

- Trading volume showed meaningful relationships with stock return behavior.
- Exchange rate fluctuations influenced multiple sectors differently.
- Market volatility increased during periods of economic instability.
- Certain sectors demonstrated higher sensitivity to macroeconomic conditions.
- Logistic Regression achieved moderate predictive performance for stock return direction.
- Market-wide variables improved prediction capability compared to using only firm-level indicators.

---

# Challenges Faced

Several challenges were encountered during the project:

- Financial market volatility
- Missing data handling
- Feature engineering complexity
- Model overfitting prevention
- Macroeconomic instability during certain periods
- Interpreting noisy financial data

These challenges were addressed through preprocessing, feature engineering, and careful model evaluation.

---

# Project Contributions

This project contributes by combining:
- Financial analysis
- Statistical methods
- Macroeconomic analysis
- Machine learning techniques

within a single analytical framework.

The study demonstrates how data science techniques can be applied to real-world financial datasets to generate meaningful analytical and predictive insights.

---

# Future Improvements

Potential future improvements include:
- Using additional macroeconomic variables
- Applying advanced ML models
- Implementing time-series forecasting methods
- Using deep learning approaches
- Expanding the dataset with international market data
- Performing sentiment analysis using financial news

---

# Conclusion

This project provides a comprehensive analysis of the relationship between trading volume, market conditions, exchange rate fluctuations, and stock returns in Borsa Istanbul.

By combining exploratory data analysis, statistical methods, and machine learning techniques, the project demonstrates how financial data science methods can be used to better understand stock market behavior and generate predictive insights.

The results highlight the importance of both market-wide and macroeconomic factors in explaining stock return dynamics across different sectors.
# AI and Development Tools Used

The project development process included the use of several AI-assisted and development tools to improve productivity, code organization, debugging, and documentation quality.

## Tools Used
- ChatGPT
- Google Colab
- GitHub
- Python Libraries

## Usage of AI Assistance

AI-assisted tools were used for:
- Code debugging support
- Documentation improvement
- Report structuring
- Explanation and interpretation support
- Project organization assistance

All analytical decisions, dataset selection, preprocessing steps, model implementations, and interpretations were reviewed and validated throughout the project development process.

The project workflow, financial analysis, statistical evaluations, and machine learning implementation were conducted and verified by the project members.

---

# Author

## Emre Turan
Sabancı University  
Industrial Engineering

---

# Course Information

DSA210 — Data Science Term Project

Sabancı University
