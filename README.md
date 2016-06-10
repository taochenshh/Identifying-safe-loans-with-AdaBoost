# Identifying-safe-loans-with-AdaBoost

The project is based on the lectures from [Classification](https://www.coursera.org/learn/ml-classification/home/welcome) course provided by UW on Coursera.

---
```Graphlab-Create built-in Boosting```

The goal of this notebook is to use the pre-implemented **gradient boosted trees** in GraphLab Create:
* Use SFrames to do some feature engineering.
* Train a boosted ensemble of decision-trees (gradient boosted trees) on the LendingClub dataset.
* Predict whether a loan will default along with prediction probabilities (on a validation set).
* Evaluate the trained model and compare it with a baseline.
* Find the most positive and negative loans using the learned model.
* Explore how the number of trees influences classification performance.

---
```self-coded AdaBoost```

The goal of this notebook is to implement self-coded boosting module:
* Use SFrames to do some feature engineering.
* Modify the decision trees to incorporate weights.
* Implement Adaboost ensembling.
* Use your implementation of Adaboost to train a **boosted decision stump ensemble**.
* Evaluate the effect of boosting (adding more decision stumps) on performance of the model.
* Explore the robustness of Adaboost to overfitting.
