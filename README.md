# machine-learning-algorithmic-trading

The purpose of this project is to apply machine learning algorithms to existing algorithmic trading strategies to enhance existing trading signals by adapting to new data. The parameters of the algorithm are tuned to optimize the strategy. Additional machine learning models (SVM and Logistic Regression) are also trained and tested in order to compare their performance to the baseline model. 

The baseline strategy returns showed an outperformance of the actual returns of the asset:
![image](https://user-images.githubusercontent.com/89161654/152255918-4bb1aff2-fde5-4b91-ac70-4ec9c0dab167.png)


The results of the analysis show that the SVM machine learning model outperforms the baseline strategy, but the Logistic Regression model only outperforms the baseline strategy during certain time periods (between mid 2018-2021).
![image](https://user-images.githubusercontent.com/89161654/152255943-84707658-87cf-42c3-9721-3ff49de21507.png)


The parameters of the training algorithm were tuned to analyze a different time period and different SMA input features. 

By increasing the training window to 6 months instead of 3 months, the baseline strategy ended up underperforming the actual returns between late 2018-early 2020, but then outperformed the actual returns from early 2020 to 2021.
![image](https://user-images.githubusercontent.com/89161654/152255993-2fad273f-4dee-4b13-b42d-a328988a3605.png)


By increasing the SMA short window from 4 to 21, the strategy never outperformed the actual returns. 
![image](https://user-images.githubusercontent.com/89161654/152256055-ba8125b5-1b8e-43f2-a093-e6f36134abe5.png)


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
