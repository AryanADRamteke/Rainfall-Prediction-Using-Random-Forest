Rainfall Prediction Using Random Forest

Project Overview
This project predicts whether it will rain tomorrow using weather observations from the Rain in Australia dataset.

Dataset
- Rain in Australia Dataset
- 142,193 records after preprocessing

Features Used
- MinTemp
- MaxTemp
- Rainfall
- Humidity9am
- Humidity3pm
- RainToday

Machine Learning Model
- Random Forest Classifier

Results
- Accuracy: 82.72%

Confusion Matrix

| Actual / Predicted | No Rain | Rain |
|-------------------|---------|------|
| No Rain | 20796 | 1302 |
| Rain | 3611 | 2730 |

Feature Importance
1. Humidity3pm
2. MinTemp
3. MaxTemp
4. Humidity9am
5. Rainfall
6. RainToday

Tools Used
- Python
- Pandas
- Scikit-Learn
- Matplotlib
- Jupyter Notebook
