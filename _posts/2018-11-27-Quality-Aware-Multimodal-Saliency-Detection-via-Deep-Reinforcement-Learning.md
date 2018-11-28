---
layout: post
title: "Quality-Aware Multimodal Saliency Detection via Deep Reinforcement Learning"
date: 2018-11-27 01:10:34
categories: arXiv_CV
tags: arXiv_CV Salient Adversarial Object_Detection Reinforcement_Learning Deep_Learning Detection
author: Xiao Wang, Tao Sun, Rui Yang, Chenglong Li, Bin Luo, Jin Tang
mathjax: true
---

* content
{:toc}

##### Abstract
Incorporating various modes of information into the machine learning procedure is becoming a new trend. And data from various source can provide more information than single one no matter they are heterogeneous or homogeneous. Existing deep learning based algorithms usually directly concatenate features from each domain to represent the input data. Seldom of them take the quality of data into consideration which is a key issue in related multimodal problems. In this paper, we propose an efficient quality-aware deep neural network to model the weight of data from each domain using deep reinforcement learning (DRL). Specifically, we take the weighting of each domain as a decision-making problem and teach an agent learn to interact with the environment. The agent can tune the weight of each domain through discrete action selection and obtain a positive reward if the saliency results are improved. The target of the agent is to achieve maximum rewards after finished its sequential action selection. We validate the proposed algorithms on multimodal saliency detection in a coarse-to-fine way. The coarse saliency maps are generated from an encoder-decoder framework which is trained with content loss and adversarial loss. The final results can be obtained via adaptive weighting of maps from each domain. Experiments conducted on two kinds of salient object detection benchmarks validated the effectiveness of our proposed quality-aware deep neural network.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.10763](http://arxiv.org/abs/1811.10763)

##### PDF
[http://arxiv.org/pdf/1811.10763](http://arxiv.org/pdf/1811.10763)

