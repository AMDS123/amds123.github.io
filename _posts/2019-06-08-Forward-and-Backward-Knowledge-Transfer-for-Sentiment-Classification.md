---
layout: post
title: "Forward and Backward Knowledge Transfer for Sentiment Classification"
date: 2019-06-08 19:18:18
categories: arXiv_AI
tags: arXiv_AI Sentiment Knowledge Sentiment_Classification Classification
author: Hao Wang, Bing Liu, Shuai Wang, Nianzu Ma, Yan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper studies the problem of learning a sequence of sentiment classification tasks. The learned knowledge from each task is retained and used to help future or subsequent task learning. This learning paradigm is called Lifelong Learning (LL). However, existing LL methods either only transfer knowledge forward to help future learning and do not go back to improve the model of a previous task or require the training data of the previous task to retrain its model to exploit backward/reverse knowledge transfer. This paper studies reverse knowledge transfer of LL in the context of naive Bayesian (NB) classification. It aims to improve the model of a previous task by leveraging future knowledge without retraining using its training data. This is done by exploiting a key characteristic of the generative model of NB. That is, it is possible to improve the NB classifier for a task by improving its model parameters directly by using the retained knowledge from other tasks. Experimental results show that the proposed method markedly outperforms existing LL baselines.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.03506](http://arxiv.org/abs/1906.03506)

##### PDF
[http://arxiv.org/pdf/1906.03506](http://arxiv.org/pdf/1906.03506)

