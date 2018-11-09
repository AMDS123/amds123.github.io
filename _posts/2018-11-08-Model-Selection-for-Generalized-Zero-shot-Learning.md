---
layout: post
title: "Model Selection for Generalized Zero-shot Learning"
date: 2018-11-08 03:47:46
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Embedding Classification
author: Hongguang Zhang, Piotr Koniusz
mathjax: true
---

* content
{:toc}

##### Abstract
In the problem of generalized zero-shot learning, the datapoints from unknown classes are not available during training. The main challenge for generalized zero-shot learning is the unbalanced data distribution which makes it hard for the classifier to distinguish if a given testing sample comes from a seen or unseen class. However, using Generative Adversarial Network (GAN) to generate auxiliary datapoints by the semantic embeddings of unseen classes alleviates the above problem. Current approaches combine the auxiliary datapoints and original training data to train the generalized zero-shot learning model and obtain state-of-the-art results. Inspired by such models, we propose to feed the generated data via a model selection mechanism. Specifically, we leverage two sources of datapoints (observed and auxiliary) to train some classifier to recognize which test datapoints come from seen and which from unseen classes. This way, generalized zero-shot learning can be divided into two disjoint classification tasks, thus reducing the negative influence of the unbalanced data distribution. Our evaluations on four publicly available datasets for generalized zero-shot learning show that our model obtains state-of-the-art results.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.03252](http://arxiv.org/abs/1811.03252)

##### PDF
[http://arxiv.org/pdf/1811.03252](http://arxiv.org/pdf/1811.03252)

