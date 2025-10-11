# RideWise — Customer Segmentation & Churn Prediction

## Repo structure
- ridewise_api.py           # FastAPI app
- ridewise_dashboard.py     # Streamlit dashboard
- models/                   # saved joblib models
  - logistic_model.joblib
  - rf_model.joblib
- data/
  - all_customers_with_segments_and_scores.csv
  - customer_features.csv
  - test_predictions.csv
- notebooks/                 # EDA and analysis notebooks
- outputs/                   # plots and CSV outputs
- evaluate_models.py
- requirements.txt
- README.md

## How to run
1. Install packages:
   pip install -r requirements.txt

2. Start API:
   uvicorn ridewise_api:app --reload

3. Start dashboard:
   streamlit run ridewise_dashboard.py

## Endpoints
- GET /health
- POST /predict
- POST /predict_bulk
- GET /customer/{id}
- GET /segments

## Model training
See notebooks/train_and_evaluate.ipynb for details.

## Contact
Data team — for questions and access to production datasets.
