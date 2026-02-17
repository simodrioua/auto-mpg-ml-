
## How to run
Open `auto_mpg.ipynb` in VS Code and run all cells.

## File path (important)
In the notebook, update this line to match where the CSV is on your computer:

df = pd.read_csv(r"C:\Users\YOUR_NAME\Downloads\auto-mpg.csv")
## Auto MPG (Regression)

Predict car fuel efficiency (mpg) using machine learning.

## Results
- MAE: 1.70 mpg
- RMSE: 2.31 mpg
- R²: 0.90

## What I did
- Converted columns to numeric 
- Filled missing horsepower with median (SimpleImputer)
- Trained RandomForestRegressor
- Tuned hyperparameters with 5-fold CV (RandomizedSearchCV)

## Files
- `auto_mpg.ipynb`: notebook with full code
- `requirements.txt`: needed Python packages
- `auto-mpg.csv`: dataset 
