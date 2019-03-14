---
layout: post
title: "Transforma at SemEval-2019 Task 6: Offensive Language Analysis using Deep Learning Architecture"
date: 2019-03-12 09:36:25
categories: arXiv_CL
tags: arXiv_CL Sentiment RNN Deep_Learning
author: Ryan Ong
mathjax: true
---

* content
{:toc}

##### Abstract
SemEval-2019 Task 6 requires us to identify and categorise offensive language in social media. In this paper we will describe the process we took to tackle this challenge. Our process is heavily inspired by Sosa (2017) [1] where he proposed CNN-LSTM and LSTM-CNN models to conduct twitter sentiment analysis. We decided to follow his approach as well as further his work by testing out different variations of RNN models with CNN. Specifically, we have divided the challenge into two parts: data processing and sampling and choosing the optimal deep learning architecture. In preprocessing, we experimented with two techniques, SMOTE and Class Weights to counter the imbalance between classes. Once we are happy with the quality of our input data, we proceed to choosing the optimal deep learning architecture for this task. Given the quality and quantity of data we have been given, we found that the addition of CNN layer provides very little to no additional improvement to our model's performance and sometimes even worsen our F1-score. In the end, the deep learning architecture that gives us the highest macro F1-score is a simple BiLSTM-CNN.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.05280](http://arxiv.org/abs/1903.05280)

##### PDF
[http://arxiv.org/pdf/1903.05280](http://arxiv.org/pdf/1903.05280)

