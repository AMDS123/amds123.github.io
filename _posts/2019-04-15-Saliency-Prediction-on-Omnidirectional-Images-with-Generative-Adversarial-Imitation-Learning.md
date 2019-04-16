---
layout: post
title: "Saliency Prediction on Omnidirectional Images with Generative Adversarial Imitation Learning"
date: 2019-04-15 14:36:40
categories: arXiv_CV
tags: arXiv_CV Salient Adversarial Attention Reinforcement_Learning Prediction
author: Mai Xu, Li Yang, Xiaoming Tao, Yiping Duan, Zulin Wang
mathjax: true
---

* content
{:toc}

##### Abstract
When watching omnidirectional images (ODIs), subjects can access different viewports by moving their heads. Therefore, it is necessary to predict subjects' head fixations on ODIs. Inspired by generative adversarial imitation learning (GAIL), this paper proposes a novel approach to predict saliency of head fixations on ODIs, named SalGAIL. First, we establish a dataset for attention on ODIs (AOI). In contrast to traditional datasets, our AOI dataset is large-scale, which contains the head fixations of 30 subjects viewing 600 ODIs. Next, we mine our AOI dataset and determine three findings: (1) The consistency of head fixations are consistent among subjects, and it grows alongside the increased subject number; (2) The head fixations exist with a front center bias (FCB); and (3) The magnitude of head movement is similar across subjects. According to these findings, our SalGAIL approach applies deep reinforcement learning (DRL) to predict the head fixations of one subject, in which GAIL learns the reward of DRL, rather than the traditional human-designed reward. Then, multi-stream DRL is developed to yield the head fixations of different subjects, and the saliency map of an ODI is generated via convoluting predicted head fixations. Finally, experiments validate the effectiveness of our approach in predicting saliency maps of ODIs, significantly better than 10 state-of-the-art approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.07080](http://arxiv.org/abs/1904.07080)

##### PDF
[http://arxiv.org/pdf/1904.07080](http://arxiv.org/pdf/1904.07080)

