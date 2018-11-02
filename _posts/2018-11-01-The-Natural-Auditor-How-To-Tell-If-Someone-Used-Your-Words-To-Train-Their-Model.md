---
layout: post
title: "The Natural Auditor: How To Tell If Someone Used Your Words To Train Their Model"
date: 2018-11-01 17:32:44
categories: arXiv_CL
tags: arXiv_CL Inference Prediction
author: Congzheng Song, Vitaly Shmatikov
mathjax: true
---

* content
{:toc}

##### Abstract
To help enforce data-protection regulations such as GDPR and detect unauthorized uses of personal data, we propose a new \emph{model auditing} technique that enables users to check if their data was used to train a machine learning model. We focus on auditing deep-learning models that generate natural-language text, including word prediction and dialog generation. These models are at the core of many popular online services. Furthermore, they are often trained on very sensitive personal data, such as users' messages, searches, chats, and comments. 
 We design and evaluate an effective black-box auditing method that can detect, with very few queries to a model, if a particular user's texts were used to train it (among thousands of other users). In contrast to prior work on membership inference against ML models, we do not assume that the model produces numeric confidence values. We empirically demonstrate that we can successfully audit models that are well-generalized and not overfitted to the training data. We also analyze how text-generation models memorize word sequences and explain why this memorization makes them amenable to auditing.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.00513](http://arxiv.org/abs/1811.00513)

##### PDF
[http://arxiv.org/pdf/1811.00513](http://arxiv.org/pdf/1811.00513)

