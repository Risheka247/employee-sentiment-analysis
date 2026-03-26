# Employee Sentiment Analysis 

## Overview

This project analyzes employee communication data to understand sentiment trends, identify potential risks, and derive actionable insights.

The system processes email data to:

* Classify sentiment (Positive, Negative, Neutral)
* Analyze communication patterns
* Detect potential flight-risk employees
* Model sentiment trends using linear regression

## Technologies Used

* Python
* Pandas
* Matplotlib
* TextBlob (NLP)
* Scikit-learn

## Dataset

The dataset contains employee email records with the following fields:

* Subject
* Body
* Date
* Employee (email ID)

## Features Implemented

### 1. Sentiment Labeling

* Used TextBlob to classify email content into:

  * Positive
  * Negative
  * Neutral

### 2. Exploratory Data Analysis (EDA)

* Sentiment distribution visualization
* Messages over time (trend analysis)
* Average sentiment per employee

### 3. Monthly Sentiment Scoring

* Aggregated sentiment scores per employee per month
* Helps track behavioral changes over time

### 4. Employee Ranking

* Ranked employees based on overall sentiment score
* Identifies most positive and least positive employees

### 5. Flight Risk Identification

* Detected employees with **4 or more negative messages within 30 days**
* Highlights potential dissatisfaction patterns

### 6. Linear Regression Model

* Modeled relationship between:

  * Number of messages (feature)
  * Sentiment score (target)
* Used to analyze sentiment trend

## 📈 Key Insights

* Majority of communication is positive, indicating a generally healthy work environment
* Some employees show temporary spikes in negative sentiment
* High communication frequency slightly correlates with positive sentiment

## How to Run

1. Install dependencies:

2. Place the dataset (`test.csv`) in the project folder

3. Run the notebook or script:


## Name

Risheka Vijayabalaiya Sujee

## Conclusion

This project demonstrates how sentiment analysis can be applied to workplace communication to derive meaningful insights, monitor employee well-being, and support decision-making.
