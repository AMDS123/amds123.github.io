---
layout: post
title: "Gradual Machine Learning for Entity Resolution"
date: 2018-10-29 13:47:52
categories: arXiv_AI
tags: arXiv_AI Inference Classification
author: Boyi Hou, Qun Chen, Yanyan Wang, Ping Zhong, Ahmed Murtadha, Zhaoqiang Chen, Zhanhuai Li
mathjax: true
---

* content
{:toc}

##### Abstract
Usually considered as a classification problem, entity resolution can be very challenging on real data due to the prevalence of dirty values. The state-of-the-art solutions for ER were built on a variety of learning models (most notably deep neural networks), which require lots of accurately labeled training data. Unfortunately, high-quality labeled data usually require expensive manual work, and are therefore not readily available in many real scenarios. In this paper, we propose a novel learning paradigm for ER, called gradual machine learning, which aims to enable effective machine learning without the requirement for manual labeling effort. It begins with some easy instances in a task, which can be automatically labeled by the machine with high accuracy, and then gradually labels more challenging instances based on iterative factor graph inference. In gradual machine learning, the hard instances in a task are gradually labeled in small stages based on the estimated evidential certainty provided by the labeled easier instances. Our extensive experiments on real data have shown that the proposed approach performs considerably better than its unsupervised alternatives, and it is highly competitive with the state-of-the-art supervised techniques. Using ER as a test case, we demonstrate that gradual machine learning is a promising paradigm potentially applicable to other challenging classification tasks requiring extensive labeling effort.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.12125](http://arxiv.org/abs/1810.12125)

##### PDF
[http://arxiv.org/pdf/1810.12125](http://arxiv.org/pdf/1810.12125)

