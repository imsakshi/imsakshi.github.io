---
layout: post
title:  "Ensemble Learning Models"
---
Ensemble Learning is a technique that combines two or more algorithms of similar or dissimilar types called Base or weak learners. In contrast to ML, Ensemble learning allows to train multiple learners at a same time to solve the  problem. Ensemble methods are an excellent way to improve predictive performance and are widely used on Kaggle platform by Data Scientists to improve accuracy and performance of their models.

Random forests is an ensemble learning method that builds a large number of decision trees that are weak classifiers and then combine them to build a stable and strong classifier that is better than the individual trees created in the forest.This falls under the axiom that “whole is greater than the sum of its parts”. 

Some of the widely used ensemble learning techniques are
 
# [](#header-1)Bagging

Bagging stands for **B**ootstrap **Agg**regat**ing** which means different training subsets are randomly drawn, with replacement from  the entire training datasets.
Each training data subset is used to train a different classifier of a same type and then all the individual classifiers are combined for a final decision. 
# [](#header-1)Boosting

Boosting is a two step approach, in which we first uses subsets of the original data to produce a series of averagely performing models and then “boosts” their performance by combining them using a particular cost function. Unlike Bagging , subset creation is not random it depends upon the performance of previous models used.XGBoost,GBM,AdaBoost are all ensemble models.
# [](#header-1)Stacking

In stacking, multiple layers of machine learning models are placed one over another where each of the model passes their predictions to the model in the layer above it and the top-layer model takes decision based on the output of the models in layers below it. 

