---
layout: post
title: "RSL19BD at DBDC4: Ensemble of Decision Tree-based and LSTM-based Models"
date: 2019-05-06 02:39:31
categories: arXiv_CL
tags: arXiv_CL CNN RNN Detection
author: Chih-Hao Wang, Sosuke Kato, Tetsuya Sakai
mathjax: true
---

* content
{:toc}

##### Abstract
RSL19BD (Waseda University Sakai Laboratory) participated in the Fourth Dialogue Breakdown Detection Challenge (DBDC4) and submitted five runs to both English and Japanese subtasks. In these runs, we utilise the Decision Tree-based model and the Long Short-Term Memory-based (LSTM-based) models following the approaches of RSL17BD and KTH in the Third Dialogue Breakdown Detection Challenge (DBDC3) respectively. The Decision Tree-based model follows the approach of RSL17BD but utilises RandomForestRegressor instead of ExtraTreesRegressor. In addition, instead of predicting the mean and the variance of the probability distribution of the three breakdown labels, it predicts the probability of each label directly. The LSTM-based model follows the approach of KTH with some changes in the architecture and utilises Convolutional Neural Network (CNN) to perform text feature extraction. In addition, instead of targeting the single breakdown label and minimising the categorical cross entropy loss, it targets the probability distribution of the three breakdown labels and minimises the mean squared error. Run 1 utilises a Decision Tree-based model; Run 2 utilises an LSTM-based model; Run 3 performs an ensemble of 5 LSTM-based models; Run 4 performs an ensemble of Run 1 and Run 2; Run 5 performs an ensemble of Run 1 and Run 3. Run 5 statistically significantly outperformed all other runs in terms of MSE (NB, PB, B) for the English data and all other runs except Run 4 in terms of MSE (NB, PB, B) for the Japanese data (alpha level = 0.05).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.01799](http://arxiv.org/abs/1905.01799)

##### PDF
[http://arxiv.org/pdf/1905.01799](http://arxiv.org/pdf/1905.01799)

