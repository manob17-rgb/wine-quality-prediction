# Wine Quality Prediction System

## Problem
A wine producer needs a preliminary way to screen wine samples as
GOOD QUALITY or NEEDS IMPROVEMENT using physicochemical measurements.

## Dataset
UCI Machine Learning Repository - Wine Quality (red wine):
https://archive.ics.uci.edu/dataset/186/wine+quality

## Prediction Rule
quality >= 6 = GOOD QUALITY; quality < 6 = NEEDS IMPROVEMENT.
The original quality score is the target only and is not used as an input.

## Technologies
Python, pandas, scikit-learn (Random Forest), joblib, Streamlit, GitHub

## Installation and Run
1. Clone the repository and open the folder
2. `pip install -r requirements.txt`
3. `python train_model.py` (creates wine_quality.csv and wine_model.pkl)
4. `streamlit run app.py`

## Model Results
Accuracy: __ | Good-quality recall: __ | Good-quality F1: __
(Fill in after running train_model.py)

## Limitations
Trained on one red-wine dataset; may not generalize to other wine types,
producers, or regions. This is a classroom prototype and not a substitute
for laboratory testing, sensory evaluation, or professional quality control.
