---
title: "Bayesian Optimization with Hyperopt"
excerpt: "<br/><a href='https://github.com/ginnocen/MachineLearningHEP/pull/629'>https://github.com/ginnocen/MachineLearningHEP/pull/629</a><br/><img src='../images/bayesian_opt_plots.png' width='500' height = '500'/>"
collection: portfolio
---

I worked on implementing Bayesian hyperparameter optimization into the [MachineLearningHEP](https://github.com/ginnocen/MachineLearningHEP) (MLHEP) package for XGBoost & Keras algorithms. It has the following features:
* Modular and reusable for tuning the hyperparameters of any ML/DL model in a few lines of code
* Can optimize with respect to any evaluation metric, including custom user defined ones.
* Returns a new model with the best set of parameters which then can immediately be evaluated on the test set.
* Produces useful plots for visualizing the hyperparameter search space e.g. validation scores at each trial and relative deviation of validation score from train score at each trial.

For more details, check out this PR on Github [here](https://github.com/ginnocen/MachineLearningHEP/pull/629).