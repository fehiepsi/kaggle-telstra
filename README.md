# Telstra Network Disruptions
My code for [Telstra Network Disruptions](https://www.kaggle.com/c/telstra-recruiting-network) Kaggle competition.

This code has a companion blog post with my [competition writeup](http://gereleth.github.io/Telstra-Network-Disruptions-Writeup/).

Competition data can be downloaded [here](https://www.kaggle.com/c/telstra-recruiting-network/data) and should go into the `data` folder. `data` folder also contains my final ensemble's predictions for the test set and out-of-fold predictions for the train set.

Code for loading data and building features is in `src/telstra_data.py`.

See my notebooks for:

* Automatic model tuning with Sacred and Hyperopt

To be added later:

* Discovering the magic feature and some visualizations
* Running all models and ensembling
* Calibrating probabilities
* Refining a random forest
