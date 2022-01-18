# machine-learning-algorithmic-trading

The purpose of this project is to apply machine learning algorithms to existing algorithmic trading strategies to enhance existing trading signals by adapting to new data. The parameters of the algorithm are tuned to optimize the strategy. Additional machine learning models (SVM and Logistic Regression) are also trained and tested in order to compare their performance to the baseline model. 

The results of the analysis show that the SVM machine learning model outperforms the baseline strategy, but the Logistic Regression model only outperforms the baseline strategy during certain time periods.



The parameters of the training algorithm were tuned to analyze a different time period and different SMA input features.


## Technologies

This project leverages Python 3.7 with the following libraries:
- Pandas
- Numpy
- pathlib
- Hvplot
- Matplotlib
- Sklearn

## Installation

This project requires the installation of sklearn and hvplot. To install these packages, run the following code in your terminal:

```
pip install -U scikit-learn
pip install hvplot
```

## Usage

In order to use this notebook, simply clone the repo and run the notebook to review the analysis.

## Contributors

Brought to you by Austin Do (austindotech@gmail.com)

## License

MIT