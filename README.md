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
  * SMA fast = 100 periods
  * SMA slow = 500 periods
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
    * Sell: %
    * Buy: %  
  * Precision:
    * Sell: %
    * Buy: %  
  * Recall:
    * Sell: %
    * Buy: %  

* LR Model 1:
  * Accuracy:
    * Sell: %
    * Buy: %  
  * Precision:
    * Sell: %
    * Buy: %  
  * Recall:
    * Sell: %
    * Buy: %  

## Summary

* SVM Model 1:
 * 
* SVM Model 2:
 * 
* LR Model 1:
 * 