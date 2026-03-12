# Crime Prediction and Analysis using Machine Learning

## Project Overview

This project focuses on analyzing crime patterns and predicting future crimes in a city using Machine Learning techniques. By studying historical crime data, the system identifies spatial and temporal crime hotspots and forecasts the likelihood of crimes occurring in specific locations and time periods.

The analysis helps highlight dangerous neighborhoods that may require increased attention from law enforcement agencies. It also provides useful insights for the general public to improve awareness and safety.

The project uses real-world crime datasets and applies machine learning models to detect patterns, trends, and possible future criminal activity.

---

## Objectives

The main objectives of this project are:

* To analyze historical crime data and identify patterns.
* To detect **crime hotspots based on location (neighborhood)**.
* To identify **time-based crime patterns** such as specific months or dates.
* To forecast the probability of crimes occurring in the future.
* To predict the **type of crime likely to occur in a specific location and time**.
* To provide insights that can help **law enforcement agencies improve crime prevention strategies**.

---

## Dataset

The dataset used for this project is sourced from Kaggle:

Dataset Link:
[https://www.kaggle.com/datasets/harryhanh/mci-2014-to-2019](https://www.kaggle.com/datasets/harryhanh/mci-2014-to-2019)

The dataset contains **Major Crime Indicators (MCI) from 2014 to 2019**.

### Important Columns in the Dataset

* Occurrence Date – Date when the crime happened
* Occurrence Month – Month of the crime occurrence
* Report Date – Date when the crime was reported
* Neighborhood – Location where the crime occurred
* Type of Offence – Category of the crime
* MCI (Major Crime Indicators) – Type of major crime classification

These attributes help in performing **spatial and temporal analysis of crime data**.

---

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Machine Learning Approach

The project follows these steps:

### 1. Data Collection

Crime dataset collected from Kaggle containing multiple years of crime records.

### 2. Data Preprocessing

* Handling missing values
* Data cleaning
* Feature selection
* Encoding categorical variables
* Date and time feature extraction

### 3. Exploratory Data Analysis (EDA)

* Crime distribution by neighborhood
* Crime trends by month and year
* Crime type analysis
* Visualization of crime hotspots

### 4. Model Building

Machine learning models are trained to predict:

* Crime occurrence probability
* Likely crime type in a specific location
* Time-based crime patterns

Possible models used include:

* Logistic Regression
* Decision Trees
* Random Forest

### 5. Prediction and Analysis

The model predicts:

* Most probable crime locations
* Frequent crime occurrence times
* Possible next crime type in a location

---

## Results

The project provides insights such as:

* Identification of **high-risk neighborhoods**
* Detection of **crime hotspots**
* Understanding of **time-based crime trends**
* Prediction of **future crime possibilities**

These findings can assist authorities in **better resource allocation and crime prevention planning**.
## How to Run the Project

1. Clone the repository

```
git clone https://github.com/yourusername/crime-prediction-ml.git
```

2. Install required libraries

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Open the project in **Jupyter Notebook**

4. Run the notebook to perform analysis and predictions.

---

## Applications

* Law enforcement agencies
* Urban planning
* Public safety awareness
* Crime pattern research
