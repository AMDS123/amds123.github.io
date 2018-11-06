---
layout: post
title: "META-DES.H: a dynamic ensemble selection technique using meta-learning and a dynamic weighting approach"
date: 2018-11-01 23:28:01
categories: arXiv_AI
tags: arXiv_AI Classification Recognition
author: Rafael M. O. Cruz, Robert Sabourin, George D. C. Cavalcanti
mathjax: true
---

* content
{:toc}

##### Abstract
In Dynamic Ensemble Selection (DES) techniques, only the most competent classifiers are selected to classify a given query sample. Hence, the key issue in DES is how to estimate the competence of each classifier in a pool to select the most competent ones. In order to deal with this issue, we proposed a novel dynamic ensemble selection framework using meta-learning, called META-DES. The framework is divided into three steps. In the first step, the pool of classifiers is generated from the training data. In the second phase the meta-features are computed using the training data and used to train a meta-classifier that is able to predict whether or not a base classifier from the pool is competent enough to classify an input instance. In this paper, we propose improvements to the training and generalization phase of the META-DES framework. In the training phase, we evaluate four different algorithms for the training of the meta-classifier. For the generalization phase, three combination approaches are evaluated: Dynamic selection, where only the classifiers that attain a certain competence level are selected; Dynamic weighting, where the meta-classifier estimates the competence of each classifier in the pool, and the outputs of all classifiers in the pool are weighted based on their level of competence; and a hybrid approach, in which first an ensemble with the most competent classifiers is selected, after which the weights of the selected classifiers are estimated in order to be used in a weighted majority voting scheme. Experiments are carried out on 30 classification datasets. Experimental results demonstrate that the changes proposed in this paper significantly improve the recognition accuracy of the system in several datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.01742](http://arxiv.org/abs/1811.01742)

##### PDF
[http://arxiv.org/pdf/1811.01742](http://arxiv.org/pdf/1811.01742)

