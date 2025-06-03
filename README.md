Here is the cleaned-up **README.md** with all emojis removed:

---

# Kaggle House Price Prediction (Advanced Regression Techniques)

This project implements a full machine learning pipeline to predict house sale prices using the Ames Housing dataset (Kaggle competition). It covers comprehensive data preprocessing, feature engineering, visualization, and model training using Gradient Boosting Regressor.

---

## Project Highlights

* EDA and Visualization: Correlation heatmap, histograms, and pair plots to explore relationships.
* Data Cleaning:

  * Filled missing values for categorical, ordinal, and numerical features.
  * Dropped irrelevant or leakage-prone columns.
  * Applied feature engineering such as `TotalBaths` and `Neighborhood_TE`.
* Feature Engineering:

  * One-hot encoding for nominal categorical variables.
  * Ordinal encoding based on logical ranking for quality/condition features.
  * Log transformation for skewed numerical features and target (`SalePrice`).
* Modeling:

  * Train/test split and evaluation using RMSE, R², and RMSLE.
  * Gradient Boosting Regressor with hyperparameter tuning via `RandomizedSearchCV`.

---

## Technologies Used

* Python (NumPy, Pandas, Matplotlib, Seaborn)
* Scikit-learn
* SciPy
* Google Colab (for development)

---

## How to Run

1. Upload the cleaned datasets to Google Drive:

   * `df_train_cleaned.csv`
   * `df_test_cleaned.csv`
2. Mount Google Drive in Colab.
3. Run `kagglehousepricecomp.py` in Colab or Jupyter.
4. Output predictions saved as `submission.csv`.

---

## Skills Learned

* Advanced data preprocessing and feature encoding.
* Target encoding and transformation techniques.
* Model evaluation on both log and original scales.
* Efficient hyperparameter optimization using randomized search.

---

## Output Example

```csv
Id,SalePrice
1461,122345.65
1462,190876.34
...
```

---

## Contact

Feel free to reach out if you have questions or suggestions.

---

Let me know if you'd like this saved as a file or further customized.
