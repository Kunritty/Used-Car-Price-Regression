# Used-Car-Price-Regression
For [Kaggle.com's Regression of Used Car Prices competition](https://www.kaggle.com/competitions/playground-series-s4e9/overview)

This project features exploratory data analysis and modeling using AutoGluon. I ended up writing many notebooks on Kaggle while experimenting with different parameters for Autogluon and different feature engineering but decided not to include all of them in this repo since it was repetitive. I also ran notebooks for tuning XGB and CatBoost models using Optuna. I tried including these hyperparameters within some run of AutoGluon as well.

In the end, I ended up at 85th out of 3,066 teams, much better than I had initially expected! The notebook that was used for this scoring was an earlier version of AutoGluonImproved.ipynb but it was unfortunately before I linked it to GitHub. The main differences between that version and the latest commit is that I had only used 1 stack level, kept a KNN model within the ensemble, and only specified XGBoost parameters. This version had produced a cross validation score of 72415. 
