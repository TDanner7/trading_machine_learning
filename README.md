# trading_machine_learning

## Overview of the Analysis

* This repo aims to use SKLearn's support vector machine (SVM) and Logistical Regression (LR) Models to try to predict investment moves. These models use the following features to predict when to buy/sell:
  * Closing Price (Close)
  * Actual Returns
  * Short Window Simple Moving average (SMA fast)
  * Long Window Simple Moving average (SMA slow)
* SVM Model 1 will attempt to make predictions using the following inputs:
  * 3 months of training data.
  * SMA fast = 4 periods
  * SMA slow = 100 periods
* SVM Model 2 will attempt to make predictions using the following inputs:
  * 5 months of training data.
  * SMA fast = 50 periods
  * SMA slow = 200 periods
* LR Model 1 will attempt to make predictions using the following inputs:
  * 5 months of training data.
  * SMA fast = 100 periods
  * SMA slow = 500 periods

## Results

* SVM Model 1:
  * Accuracy:
    * Sell: 7%
    * Buy: 71%  
  * Precision:
    * Sell: 43%
    * Buy: 56%  
  * Recall:
    * Sell: 4%
    * Buy: 96%

* SVM Model 2:
  * Accuracy:
    * Sell: 37%
    * Buy: 63%  
  * Precision:
    * Sell: 46%
    * Buy: 57%  
  * Recall:
    * Sell: 31%
    * Buy: 71%  

* LR Model 1:
  * Accuracy:
    * Sell: 50%
    * Buy: 53%  
  * Precision:
    * Sell: 45%
    * Buy: 58%  
  * Recall:
    * Sell: 55%
    * Buy: 49%  

## Summary

* SVM Model 1:
 * This model slightly outperforms the market, although the data would need to be tested against more significant data before deploying.
* SVM Model 2:
 * This model does not outperform the market at a consistent rate, further research needed.
* LR Model 1:
 * This model does not outperform the market at a consistent rate, further research needed.