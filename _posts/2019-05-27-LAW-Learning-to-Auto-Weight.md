---
layout: post
title: "LAW: Learning to Auto Weight"
date: 2019-05-27 09:05:28
categories: arXiv_CV
tags: arXiv_CV Knowledge Reinforcement_Learning
author: Zhenmao Li, Yichao Wu, Ken Chen, Yudong WU, Shunfeng Zhou, Jiaheng Liu, Junjie Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Example weighting algorithm is an effective solution to the training bias problem. However, typical methods are usually limited to human knowledge and require laborious tuning of hyperparameters. In this study, we propose a novel example weighting framework called Learning to Auto Weight (LAW), which can learn weighting policy from data adaptively based on reinforcement learning (RL). 
 To shrink the huge searching space in a complete training process, we divide the training procedure consisting of numerous iterations into a small number of stages, and then search a low-deformational continuous vector as action, which determines the weight of each sample. To make training more efficient, we make an innovative design of the reward to remove randomness during the RL process. 
 Experimental results demonstrate the superiority of weighting policy explored by LAW over standard training pipeline. Especially, compared with baselines, LAW can find a better weighting schedule which achieves higher accuracy in the origin CIFAR dataset, and over 10% higher in accuracy on the contaminated CIFAR dataset with 30% label noises. Our code will be released soon.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.11058](http://arxiv.org/abs/1905.11058)

##### PDF
[http://arxiv.org/pdf/1905.11058](http://arxiv.org/pdf/1905.11058)

