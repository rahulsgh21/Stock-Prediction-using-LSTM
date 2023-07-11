# Stock Price Prediction using LSTM

Through this code I have provided an implementation of stock price prediction using an LSTM (Long Short-Term Memory) neural network.

- Firstly, I have created  a file "Trained_model_code.ipynb"" in which I have trained the neural network using the dataset "STOCK_INDEX.csv". Then, I saved this model into a file named "trained_model.h5" which can be loaded whenever needed for prediction.

- Secondly, I have created a file "210807_Rahul Singh.ipynb". In this file I have modified the "predict_func" while keeping the "evaluate" function unchanged. I have loaded the "trained_model.h5" file in this particular file and used it for making prediction and evaluate mse and directional accuracy.


## Instructions

1. Install the required libraries using the following command:
- !pip intall tensorflow
- !pip install numpy
- !pip install pandas 
- !pip install keras

2. Prepare the data:
- Please make sure that the historical stock price data is available in the 'STOCK_INDEX.csv' file in the same directory.
- Ensure that the sample input data is available in the 'sample_input.csv' file and the corresponding actual closing prices are listed in the 'sample_close.txt' file.
- To test for other dataset. Replace sample_input with some-other dataset. Please ensure that this new dataset contains 50 stock prices else it will throw error.

3. Run the code:
-  Open the f
- TensorFlow: A machine learning library used for creating and training neural networks.
- NumPy: A library for numerical computing in Python.
- Pandas: A library for data manipulation and analysis.
- Kerasile named "210807_Rahul Singh.ipynb". Run all the cells.

4. Output:
- The code will display the mean squared error and directional accuracy of the stock price predictions for the sample dataset.

## Required Libraries
 (part of TensorFlow): A high-level neural networks API used for building and training models.

## Files

- 210807_Rahul Singh.ipynb: Python file which evaluates my trained model based on prediction of stock prices for the next two days of the provided sample dataset.
- Trained_model_code.ipynb: The main script that trains the LSTM model.
- STOCK_INDEX.csv: CSV file containing historical stock price data.
- sample_input.csv: Sample input data for evaluating the model's predictions.
- sample_close.txt: Text file containing the actual closing prices corresponding to the sample input data.
- trained_model.h5: File which can be loaded whenever required for making predictions.
- scaler.save: File which saves the scaling while is used in training our model