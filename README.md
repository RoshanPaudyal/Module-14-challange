## Support Vector Machine Trading Strategy
#### This project uses a Support Vector Machine (SVM) learning method to develop a trading strategy for emerging markets. The goal is to develop a model that can accurately predict market trends based on past price data, and generate profitable trading signals.

### Technologies
#### This project uses the following technologies:

Python 3.7.10
Pandas 1.2.4
Scikit-learn 0.24.2
Hvplot 0.7.3
Matplotlib 3.3.4
Installation
To run this project, you will need to install the following packages:

#### Copy code
pip install pandas
pip install scikit-learn
pip install hvplot
pip install matplotlib

### Usage
#### The project is divided into the following steps:

Data preprocessing and feature engineering
Generation of trading signals using SMA values
Splitting the data into training and testing datasets
Fitting the SVM model to the training data and generating predictions for the testing data
To run the project, open the "svm_trading_strategy.ipynb" file in a Jupyter Notebook, and run each cell in order.

### Results
The SVM model generated an accuracy of 55% in predicting market trends based on the training data. The model was able to correctly predict 96% of the times when the market was trending upwards, but only 4% of the times when it was trending downwards.

### Conclusion
While the SVM model was able to predict the upward trend of the market with a high degree of accuracy, it was not as successful in predicting the downward trend. Therefore, this trading strategy may be useful for long positions but may not be as effective for short positions. Further optimization of the model may be necessary to improve its overall performance.
