---
layout: post
title: "Code Failure Prediction and Pattern Extraction using LSTM Networks"
date: 2018-12-13 02:46:44
categories: arXiv_AI
tags: arXiv_AI Sentiment Optimization RNN Deep_Learning Prediction
author: Mahdi Hajiaghayi, Ehsan Vahedi
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we use a well-known Deep Learning technique called Long Short Term Memory (LSTM) recurrent neural networks to find sessions that are prone to code failure in applications that rely on telemetry data for system health monitoring. We also use LSTM networks to extract telemetry patterns that lead to a specific code failure. For code failure prediction, we treat the telemetry events, sequence of telemetry events and the outcome of each sequence as words, sentence and sentiment in the context of sentiment analysis, respectively. Our proposed method is able to process a large set of data and can automatically handle edge cases in code failure prediction. We take advantage of Bayesian optimization technique to find the optimal hyper parameters as well as the type of LSTM cells that leads to the best prediction performance. We then introduce the Contributors and Blockers concepts. In this paper, contributors are the set of events that cause a code failure, while blockers are the set of events that each of them individually prevents a code failure from happening, even in presence of one or multiple contributor(s). Once the proposed LSTM model is trained, we use a greedy approach to find the contributors and blockers. To develop and test our proposed method, we use synthetic (simulated) data in the first step. The synthetic data is generated using a number of rules for code failures, as well as a number of rules for preventing a code failure from happening. The trained LSTM model shows over 99% accuracy for detecting code failures in the synthetic data. The results from the proposed method outperform the classical learning models such as Decision Tree and Random Forest. Using the proposed greedy method, we are able to find the contributors and blockers in the synthetic data in more than 90% of the cases, with a performance better than sequential rule and pattern mining algorithms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.05237](http://arxiv.org/abs/1812.05237)

##### PDF
[http://arxiv.org/pdf/1812.05237](http://arxiv.org/pdf/1812.05237)

