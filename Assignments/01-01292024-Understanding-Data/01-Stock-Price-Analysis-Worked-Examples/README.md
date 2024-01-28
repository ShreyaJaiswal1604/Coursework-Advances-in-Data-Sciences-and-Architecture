<hr>
<hr>

## Predicting Stock Prices with LSTM

<hr>
<hr>
<a href="https://githubtocolab.com/ShreyaJaiswal1604/Coursework-Advances-in-Data-Sciences-and-Architecture/blob/main/Assignments/01-01292024-Understanding-Data/01-Stock-Price-Analysis-Worked-Examples/python-code/Understanding_Data_Market_Stock_Price_Prediction_Shreya_Jaiswal_002747677.ipynb">
<img src="https://www.tensorflow.org/images/colab_logo_32px.png" />Run in Google Colab</a>


<hr>


This repository contains code for predicting stock prices using Long Short-Term Memory (LSTM) models. The example focuses on predicting the stock prices of Apple Inc. (AAPL) using historical stock market data obtained from Yahoo Finance.

#### Overview:

- **Data Source**: The historical stock price data is sourced from Yahoo Finance.
- **Data Preprocessing**: The data is preprocessed to handle missing values, standardize column names, and engineer additional features like daily return and typical price.
- **Modeling**: LSTM models are used for time series forecasting. The architecture, hyperparameters, and evaluation metrics are discussed and implemented.
- **Evaluation**: Model performance is evaluated using Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).
- **Visualization**: Visualizations of predicted vs. actual stock prices and feature importance are provided.

#### Contents:

- **data_preprocessing.ipynb**: Jupyter Notebook containing code for data preprocessing steps.
- **lstm_modeling.ipynb**: Jupyter Notebook implementing LSTM models for stock price prediction.
- **evaluation_metrics.ipynb**: Jupyter Notebook evaluating model performance using various metrics.
- **visualizations.ipynb**: Jupyter Notebook with visualizations of predicted vs. actual stock prices and feature importance.
- **README.md**: This file providing an overview of the project.

#### Workflow: Key Stages and Techniques
- **1. Data Profiling**: Understand the structure, content, and quality of the dataset. This involves examining data types, summary statistics, and identifying potential issues such as missing values, outliers, or inconsistent data.

- **2. Data Quality Techniques**: Implement techniques to address data quality issues identified during data profiling. This may include data validation, error correction, and ensuring data consistency.

- **3. Data Cleaning Techniques**: Perform data cleaning operations such as removing duplicates, correcting data inconsistencies, and handling outliers. This ensures that the dataset is prepared for analysis and modeling.

- **4. Handling Missing Data**: Address missing values in the dataset using appropriate techniques such as imputation (e.g., mean imputation, median imputation) or deletion of missing records.

- **5. Imputation Techniques**: If missing data is present, apply imputation techniques to fill in missing values with estimated values based on available data.

- **6. Feature Engineering**
Create new features from existing ones or transform features to better represent the underlying patterns in the data. This step can improve model performance by providing more relevant information to the algorithms.

- **7. Feature Selection**
Select relevant features that contribute most to the predictive task while reducing dimensionality and computational complexity. Techniques include statistical tests, feature importance from models, or domain knowledge.


- **8.Data Normalization**: Normalize the data if necessary to ensure that features are on a similar scale. Normalization typically transforms data to have a mean of 0 and a standard deviation of 1, which can improve the performance of certain algorithms.

- **9. Data Scaling**: Scale the data to a specific range or distribution if required. Scaling ensures that all features contribute equally to the analysis and modeling process.


- **10. Data Modeling**
Train and evaluate predictive models using the preprocessed dataset. Choose appropriate algorithms based on the nature of the problem, dataset size, and desired interpretability or accuracy.

- **11. Hyperparameter Tuning**
Optimize the hyperparameters of the selected models to improve performance. This involves systematically adjusting model settings to find the best configuration for the given data and problem.

- **12. Model Evaluation**
Assess the performance of trained models using appropriate evaluation metrics. This step helps determine how well the models generalize to unseen data and whether they meet the project's objectives.

- **13. Model Interpretability**
Understand the factors driving model predictions and interpret the model's behavior. This step enhances trust and transparency in the model's decision-making process.

- **14. Deployment and Monitoring**
Deploy the trained models into production environments and monitor their performance over time. This ensures that the models continue to deliver accurate and reliable predictions in real-world scenarios.


#### Usage:

1. Clone the repository to your local machine.
2. Install the required dependencies specified in `requirements.txt`.
3. Run the Jupyter Notebooks to explore the code and reproduce the results.

#### Dependencies:

- Python 3.x
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- scikit-learn
- TensorFlow/Keras

#### References:

- [Yahoo Finance](https://finance.yahoo.com/)
- [Keras Documentation](https://keras.io/)
- [scikit-learn Documentation](https://scikit-learn.org/)
- [TensorFlow Documentation](https://www.tensorflow.org/)
- https://www.analyticsvidhya.com/blog/2021/10/machine-learning-for-stock-market-prediction-with-step-by-step-implementation/
- https://neptune.ai/blog/predicting-stock-prices-using-machine-learning
- https://towardsdatascience.com/illustrated-guide-to-recurrent-neural-networks-79e5eb8049c9
- https://colah.github.io/posts/2015-08-Understanding-LSTMs/
- https://towardsdatascience.com/time-series-forecasting-predicting-stock-prices-using-an-lstm-model-d0056cd5e055
- https://towardsdatascience.com/time-series-forecasting-predicting-stock-prices-using-an-lstm-model-d0056cd5e055
- https://colah.github.io/posts/2015-08-Understanding-LSTMs/

Feel free to explore the notebooks and provide feedback for improvement!
