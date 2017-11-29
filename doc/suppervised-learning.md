# Supervised Learning


## Model selection:
[Machine learning Map from scikit](http://scikit-learn.org/stable/tutorial/machine_learning_map/)

[Microsoft Azure](https://azure.microsoft.com/en-us/documentation/articles/machine-learning-algorithm-choice/)

[Best ML Algorithm](http://sebastianraschka.com/faq/docs/best-ml-algo.html)

[Bagging](https://www.quora.com/What-is-bagging-in-machine-learning)

[Models should be explainable 1](https://rayli.net/blog/data/top-10-data-mining-algorithms-in-plain-english/)

[Models should be explainable 2](http://blog.echen.me/2011/03/14/laymans-introduction-to-random-forests/)

[Models should be explainable 3](https://prateekvjoshi.com/2014/05/05/what-is-adaboost/)

[Models should be explainable 4](http://xgboost.readthedocs.io/en/latest/model.html)

## Xgboost

Pro Tip (Advanced): Xgboost, one of Kaggle’s top algorithms.
In the recent years one algorithm emerged as favourite in the machine learning community, it is actually one of the most used in Kaggle: Xgboost.
Here you can find an informative [discussion](https://www.quora.com/Why-is-xgboost-given-so-much-less-attention-than-deep-learning-despite-its-ubiquity-in-winning-Kaggle-solutions) on why that is the case: 


The algorithm is not available sci-kit learn, here is how you can [start working](http://machinelearningmastery.com/develop-first-xgboost-model-python-scikit-learn/) with it:


An alternative feature selection approach consists in leveraging the power of Recursive Feature Selection to automate the selection process and find a good indication of the number of relevant features (it is not suitable for this problem because that is not what is required by the project rubric, though it is generally a very good approach). [Check this out!](http://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.RFE.html)


[Use a Random Search over a Grid Search](https://medium.com/rants-on-machine-learning/smarter-parameter-sweeps-or-why-grid-search-is-plain-stupid-c17d97a0e881
)

## Miscelleous

There are a ton of other methods we can use to extract the feature importances in our data. You might remember some of the simpler univariate methods like SelectKBest and SelectPercentile in sklearn.

We can also try more complex methods like Recursive Feature Elimination. This technique recursively cuts out the feature that contributes least to the model, and then re-evaluates the model after the elimination. This process repeats until we have the desired number of features.
[Check this out](http://blog.datadive.net/selecting-good-features-part-iv-stability-selection-rfe-and-everything-side-by-side/)

[And this](https://topepo.github.io/caret/recursive-feature-elimination.html)
