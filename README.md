# Weather-Based Road Accident Analysis

This project analyzes the relationship between weather conditions and road accidents in India using government-published datasets. It explores accident patterns through data analysis and implements a predictive model to estimate accident severity.

---

## Features
- Exploratory Data Analysis (EDA) of accident trends.
- Analysis of weather conditions such as fog, rain, and clear skies on accident frequency.
- Data preprocessing and feature engineering for structured analysis.
- Predictive modeling for accident severity.
- Visualizations for accident distribution and model performance.

---

## Dataset
- Source: Government of India accident datasets (Annexure tables).  
- Attributes include:
  - `Weather_Condition`
  - `Accident_Type`
  - `Number_of_Fatalities`
  - `Number_of_Injuries`

---

## Tech Stack
- **Python**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Jupyter Notebook** for analysis and model building  

---

## Predictive Model
The project includes a classification model to predict accident severity (minor, serious, fatal) based on weather conditions.

- **Algorithms Used**:  
  - Logistic Regression (baseline)  
  - Random Forest Classifier (final model)  

- **Why Random Forest?**  
  - Handles mixed features effectively  
  - Reduces overfitting using ensemble learning  
  - Provides feature importance for interpretability  

- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score, Confusion Matrix  

---

## Outcomes
- Identifies high-risk weather conditions for accidents.  
- Provides predictive insights that can support road safety planning.  
- Lays the foundation for a real-time accident risk predictor using live weather data.  

---

## Installation & Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/weather-based-accidents.git
   cd weather-based-accidents
