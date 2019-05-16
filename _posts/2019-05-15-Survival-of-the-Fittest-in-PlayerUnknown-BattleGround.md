---
layout: post
title: "Survival of the Fittest in PlayerUnknown BattleGround"
date: 2019-05-15 09:39:46
categories: arXiv_AI
tags: arXiv_AI Prediction
author: Brij Rokad, Tushar Karumudi, Omkar Acharya, Akshay Jagtap
mathjax: true
---

* content
{:toc}

##### Abstract
The goal of this paper was to predict the placement in the multiplayer game PUBG (playerunknown battleground). In the game, up to one hundred players parachutes onto an island and scavenge for weapons and equipment to kill others, while avoiding getting killed themselves. The available safe area of the game map decreases in size over time, directing surviving players into tighter areas to force encounters. The last player or team standing wins the round. In this paper specifically, we have tried to predict the placement of the player in the ultimate survival test. The data set has been taken from Kaggle. Entire dataset has 29 attributes which are categories to 1 label(winPlacePerc), training set has 4.5 million instances and testing set has 1.9 million. winPlacePerc is continuous category, which makes it harder to predict the survival of the fittest. To overcome this problem, we have applied multiple machine learning models to find the optimum prediction. Model consists of LightGBM Regression (Light Gradient Boosting Machine Regression), MultiLayer Perceptron, M5P (improvement on C4.5) and Random Forest. To measure the error rate, Mean Absolute Error has been used. With the final prediction we have achieved MAE of 0.02047, 0.065, 0.0592 and 0634 respectively.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.06052](http://arxiv.org/abs/1905.06052)

##### PDF
[http://arxiv.org/pdf/1905.06052](http://arxiv.org/pdf/1905.06052)

