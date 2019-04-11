---
layout: post
title: "A Variational Approach to Weakly Supervised Document-Level Multi-Aspect Sentiment Classification"
date: 2019-04-10 08:24:06
categories: arXiv_CL
tags: arXiv_CL Sentiment Weakly_Supervised Sentiment_Classification Classification
author: Ziqian Zeng, Wenxuan Zhou, Xin Liu, Yangqiu Song
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a variational approach to weakly supervised document-level multi-aspect sentiment classification. Instead of using user-generated ratings or annotations provided by domain experts, we use target-opinion word pairs as "supervision." These word pairs can be extracted by using dependency parsers and simple rules. Our objective is to predict an opinion word given a target word while our ultimate goal is to learn a sentiment polarity classifier to predict the sentiment polarity of each aspect given a document. By introducing a latent variable, i.e., the sentiment polarity, to the objective function, we can inject the sentiment polarity classifier to the objective via the variational lower bound. We can learn a sentiment polarity classifier by optimizing the lower bound. We show that our method can outperform weakly supervised baselines on TripAdvisor and BeerAdvocate datasets and can be comparable to the state-of-the-art supervised method with hundreds of labels per aspect.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.05055](http://arxiv.org/abs/1904.05055)

##### PDF
[http://arxiv.org/pdf/1904.05055](http://arxiv.org/pdf/1904.05055)

