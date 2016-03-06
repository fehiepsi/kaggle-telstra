# Telstra Network Disruptions
My code for [Telstra Network Disruptions](https://www.kaggle.com/c/telstra-recruiting-network) Kaggle competition.

This code has a companion blog post with my [competition writeup](http://gereleth.github.io/Telstra-Network-Disruptions-Writeup/).

Competition data can be downloaded [here](https://www.kaggle.com/c/telstra-recruiting-network/data) and should go into the `data` folder. `data` folder also contains my final ensemble's predictions for the test set and out-of-fold predictions for the train set.

See my notebooks for:

* [Automatic model tuning with Sacred and Hyperopt](https://github.com/gereleth/kaggle-telstra/blob/master/Automatic%20model%20tuning%20with%20Sacred%20and%20Hyperopt.ipynb)
* [Discovering the magic feature and some visualizations](https://github.com/gereleth/kaggle-telstra/blob/master/Discovering%20the%20magic%20feature.ipynb)

To be added later:

* Running all models and ensembling
* Calibrating probabilities
* Refining a random forest

Code for loading data and building features is in `src/telstra_data.py`.
