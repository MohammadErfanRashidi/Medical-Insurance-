# Medical Insurance Cost Prediction

This project predicts medical insurance costs using a Random Forest Regressor model.

## Dataset

The dataset used is `insurance.csv`, containing information about patients and their insurance charges.

## Dependencies

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

## Usage

1. Install the required libraries using `pip install -r requirements.txt` (create a `requirements.txt` file with the dependencies listed above).
2. Load the dataset into a pandas DataFrame.
3. Preprocess the data by encoding categorical features.
4. Split the data into training and testing sets.
5. Train a Random Forest Regressor model on the training data.
6. Evaluate the model's performance on the testing data using metrics such as R-squared, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).
7. Visualize the results with plots.

## Results

The model achieves an R-squared of approximately 0.8, indicating a good fit to the data. The MAE and RMSE values provide further insights into the prediction accuracy.

## Conclusion

This project demonstrates how to build a machine learning model for predicting medical insurance costs. The Random Forest Regressor model shows promising results and can be further improved by tuning hyperparameters or exploring other algorithms.
