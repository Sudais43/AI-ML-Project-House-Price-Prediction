# House Price Prediction

End-to-end machine learning workflow for predicting house prices with EDA, preprocessing, feature engineering, model training, and evaluation.

## Dataset
- Kaggle: harishkumardatalab/house-price-prediction
- If the CSV is not available locally, the notebook generates a synthetic dataset with the same columns.
- Place the CSV in the project root or in a data/ folder with one of these names:
  - house_price_prediction.csv
  - house_price.csv

## Project Structure
- main.ipynb
- requirements.txt
- README.md

## How to Run
1. Install dependencies:
   - pip install -r requirements.txt
2. Open the notebook:
   - main.ipynb

## Notes
- The notebook uses pandas, numpy, matplotlib, seaborn, and scikit-learn.
- When the CSV is missing, synthetic data is created with columns:
  Price, Area, Bedrooms, Bathrooms, Floors, YearBuilt, Furnishing.
