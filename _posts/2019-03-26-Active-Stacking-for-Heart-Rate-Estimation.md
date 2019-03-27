---
layout: post
title: "Active Stacking for Heart Rate Estimation"
date: 2019-03-26 13:26:34
categories: arXiv_AI
tags: arXiv_AI Knowledge Detection
author: Dongrui Wu, Feifei Liu, Chengyu Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Heart rate estimation from electrocardiogram signals is very important for the early detection of cardiovascular diseases. However, due to large individual differences and varying electrocardiogram signal quality, there does not exist a single reliable estimation algorithm that works well on all subjects. Every algorithm may break down on certain subjects, resulting in a significant estimation error. Ensemble regression, which aggregates the outputs of multiple base estimators for more reliable and stable estimates, can be used to remedy this problem. Moreover, active learning can be used to optimally select a few trials from a new subject to label, based on which a stacking ensemble regression model can be trained to aggregate the base estimators. This paper proposes four active stacking approaches, and demonstrates that they all significantly outperform three common unsupervised ensemble regression approaches, and a supervised stacking approach which randomly selects some trials to label. Remarkably, our active stacking approaches only need three or four labeled trials from each subject to achieve an average root mean squared estimation error below three beats per minute, making them very convenient for real-world applications. To our knowledge, this is the first research on active stacking, and its application to heart rate estimation.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1903.10862](https://arxiv.org/abs/1903.10862)

##### PDF
[https://arxiv.org/pdf/1903.10862](https://arxiv.org/pdf/1903.10862)

