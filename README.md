Let's break down the workflow of the code into a step-by-step process:

1. **Data Loading:**
   - The code starts by loading the advertising dataset from a specified file location using pandas. This dataset contains information about advertising expenditures on TV, radio, newspaper, and corresponding sales figures.

2. **Data Preprocessing:**
   - The relevant columns are selected for analysis. The 'TV,' 'Radio,' and 'Newspaper' columns are considered as the features, and the 'Sales' column is designated as the target variable.
   
3. **Data Splitting:**
   - The data is divided into two subsets: training data and testing data. This is crucial for training the model on one subset and evaluating its performance on the other. An 80-20 split ratio is used, with 80% of the data allocated for training and 20% for testing.

4. **Model Selection and Training:**
   - A Linear Regression model is chosen for this task. Linear Regression is a simple and effective algorithm for predicting a target variable based on one or more input features.
   - The model is trained using the training data, with the 'TV,' 'Radio,' and 'Newspaper' advertising expenditures as input features and 'Sales' as the target.

5. **Model Prediction:**
   - The trained model is used to make predictions on the testing data. This step is where the model estimates sales based on the advertising expenses in the test dataset.

6. **Model Evaluation:**

   ![Screenshot 2023-11-05 121210](https://github.com/vr-jayashree5443/Sales-Prediction-using-Python/assets/128161257/16a062a4-6ed7-4cd1-86ea-6d115c769d99)

   - Two important metrics are calculated to assess the model's performance:
     - **Mean Squared Error (MSE):** It quantifies the average squared difference between the predicted sales and the actual sales in the test data. Lower MSE values indicate better model accuracy.
     - **R-squared (R2):** It measures how well the model fits the data. R2 values range from 0 to 1, where a higher R2 indicates a better fit.

8. **Printing Predicted Sales:**

   ![Screenshot 2023-11-05 121128](https://github.com/vr-jayashree5443/Sales-Prediction-using-Python/assets/128161257/ec8e6eb7-f7ee-439f-9c3e-816d992dac4d)


   - The code prints the predicted sales values for the test data. These are the estimated sales values based on the model's predictions.

9. **Data Visualization:**

    ![Figure_1](https://github.com/vr-jayashree5443/Sales-Prediction-using-Python/assets/128161257/05cddb45-61a7-4fa9-88d4-df95702bdce3)

   - To provide a visual representation of the model's performance, a scatter plot is created. It compares the actual sales (from the test data) with the predicted sales. This allows you to see how closely the model's predictions align with the actual data points.

In summary, the code follows a standard workflow for performing a simple linear regression analysis on an advertising dataset. It loads, preprocesses, splits, trains, predicts, evaluates, and visualizes the data and model performance, enabling you to understand how well advertising expenses predict sales.
