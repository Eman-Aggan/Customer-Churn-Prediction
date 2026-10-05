# 📶 AI Customer Churn Prediction System

## Project Overview
This project predicts customer churn using classic Machine Learning algorithms (KNN, Decision Trees, Random Forest) alongside a Deep Learning Multi-Layer Perceptron (ANN). 

## Key Results
| Model | Accuracy | Precision | Recall | F1-Score |
|---|---|---|---|---|
| KNN | 0.758 | 0.542 | 0.510 | 0.525 |
| Decision Tree | 0.785 | 0.620 | 0.505 | 0.556 |
| Random Forest | 0.802 | 0.655 | 0.531 | 0.586 |
| **ANN (Deep Learning)** | **0.806** | **0.648** | **0.565** | **0.603** |

## Best Performing Model
The Artificial Neural Network achieved the highest overall balance between Precision and Recall (F1-score: 0.603). 

## How to Run
1. Clone the repo: `git clone <repo-url>`
2. Install requirements: `pip install -r requirements.txt`
3. Launch Streamlit UI: `streamlit run app.py`
