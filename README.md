# XGBoost-Regressor-Calories-Burnt-Prediction

=> Project Overview
- In this project, we predict the number of calories burnt based on various features such as age, gender, height, weight, exercise duration, heart rate, and body temperature. The model is trained on the XGBoost regression algorithm, which is well-known for its performance on structured/tabular data.

=> Data Preprocessing
- Handling Missing Values: No missing values were found in the dataset.
- Categorical Variables: The Gender column is converted into numerical form (0 for male, 1 for female).
- Feature Selection: The User_ID column was dropped as it is not useful for prediction.
- Data Splitting: The data was split into training and testing sets in an 80:20 ratio.

=> Exploratory Data Analysis (EDA)
- Visualizations were created using Seaborn and Matplotlib to understand the data distribution:
- Gender distribution using countplot.
- Age, height, weight distributions using distplot.
- Correlation heatmap to visualize relationships between variables.

=> Model Building
- The XGBoost regressor was used to train the model. XGBoost is a powerful and efficient machine learning algorithm for regression tasks. The model was trained on the training set and evaluated on the test set.

=> Evaluation
- The model's performance was evaluated using Mean Absolute Error (MAE). The MAE for this model is approximately 1.49, indicating that the predictions are very close to the actual values.

=> Conclusion
- The XGBoost regressor provided accurate predictions with a low mean absolute error. Further improvements can be made by tuning the hyperparameters or using additional features.

=> Contact Us

1. Email: uttamsojitra.ds@gmail.com

2. LinkedIn: https://www.linkedin.com/in/uttam-sojitra-6aa781236/

Feel free to reach out for any collaboration, job opportunities, or project discussions!
