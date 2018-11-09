---
layout: post
title: "Correlation Filter Selection for Visual Tracking Using Reinforcement Learning"
date: 2018-11-08 00:24:42
categories: arXiv_CV
tags: arXiv_CV Tracking Reinforcement_Learning Optimization Relation
author: Yanchun Xie, Jimin Xiao, Kaizhu Huang, Jeyarajan Thiyagalingam, Yao Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Correlation filter has been proven to be an effective tool for a number of approaches in visual tracking, particularly for seeking a good balance between tracking accuracy and speed. However, correlation filter based models are susceptible to wrong updates stemming from inaccurate tracking results. To date, little effort has been devoted towards handling the correlation filter update problem. In this paper, we propose a novel approach to address the correlation filter update problem. In our approach, we update and maintain multiple correlation filter models in parallel, and we use deep reinforcement learning for the selection of an optimal correlation filter model among them. To facilitate the decision process in an efficient manner, we propose a decision-net to deal target appearance modeling, which is trained through hundreds of challenging videos using proximal policy optimization and a lightweight learning network. An exhaustive evaluation of the proposed approach on the OTB100 and OTB2013 benchmarks show that the approach is effective enough to achieve the average success rate of 62.3% and the average precision score of 81.2%, both exceeding the performance of traditional correlation filter based trackers.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.03196](http://arxiv.org/abs/1811.03196)

##### PDF
[http://arxiv.org/pdf/1811.03196](http://arxiv.org/pdf/1811.03196)

