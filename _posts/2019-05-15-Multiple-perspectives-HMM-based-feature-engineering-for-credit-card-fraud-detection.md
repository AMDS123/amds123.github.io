---
layout: post
title: "Multiple perspectives HMM-based feature engineering for credit card fraud detection"
date: 2019-05-15 15:29:49
categories: arXiv_AI
tags: arXiv_AI Classification Detection
author: Yvan Lucas, Pierre-Edouard Portier, L&#xe9;a Laporte, Olivier Caelen, Liyun He-Guelton, Sylvie Calabretto, Michael Granitzer
mathjax: true
---

* content
{:toc}

##### Abstract
Machine learning and data mining techniques have been used extensively in order to detect credit card frauds. However, most studies consider credit card transactions as isolated events and not as a sequence of transactions. 
 In this article, we model a sequence of credit card transactions from three different perspectives, namely (i) does the sequence contain a Fraud? (ii) Is the sequence obtained by fixing the card-holder or the payment terminal? (iii) Is it a sequence of spent amount or of elapsed time between the current and previous transactions? Combinations of the three binary perspectives give eight sets of sequences from the (training) set of transactions. Each one of these sets is modelled with a Hidden Markov Model (HMM). Each HMM associates a likelihood to a transaction given its sequence of previous transactions. These likelihoods are used as additional features in a Random Forest classifier for fraud detection. This multiple perspectives HMM-based approach enables an automatic feature engineering in order to model the sequential properties of the dataset with respect to the classification task. This strategy allows for a 15% increase in the precision-recall AUC compared to the state of the art feature engineering strategy for credit card fraud detection.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.06247](http://arxiv.org/abs/1905.06247)

##### PDF
[http://arxiv.org/pdf/1905.06247](http://arxiv.org/pdf/1905.06247)

