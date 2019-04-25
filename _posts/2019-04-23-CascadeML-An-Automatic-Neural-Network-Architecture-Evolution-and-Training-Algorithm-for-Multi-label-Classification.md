---
layout: post
title: "CascadeML: An Automatic Neural Network Architecture Evolution and Training Algorithm for Multi-label Classification"
date: 2019-04-23 22:05:51
categories: arXiv_AI
tags: arXiv_AI Classification
author: Arjun Pakrashi, Brian Mac Namee
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-label classification is an approach which allows a datapoint to be labelled with more than one class at the same time. A common but trivial approach is to train individual binary classifiers per label, but the performance can be improved by considering associations within the labels. Like with any machine learning algorithm, hyperparameter tuning is important to train a good multi-label classifier model. The task of selecting the best hyperparameter settings for an algorithm is an optimisation problem. Very limited work has been done on automatic hyperparameter tuning and AutoML in the multi-label domain. This paper attempts to fill this gap by proposing a neural network algorithm, CascadeML, to train multi-label neural network based on cascade neural networks. This method requires minimal or no hyperparameter tuning and also considers pairwise label associations. The cascade algorithm grows the network architecture incrementally in a two phase process as it learns the weights using adaptive first order gradient algorithm, therefore omitting the requirement of preselecting the number of hidden layers, nodes and the learning rate. The method was tested on 10 multi-label datasets and compared with other multi-label classification algorithms. Results show that CascadeML performs very well without hyperparameter tuning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.10551](http://arxiv.org/abs/1904.10551)

##### PDF
[http://arxiv.org/pdf/1904.10551](http://arxiv.org/pdf/1904.10551)

