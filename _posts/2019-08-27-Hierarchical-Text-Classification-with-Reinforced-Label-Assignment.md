---
layout: post
title: "Hierarchical Text Classification with Reinforced Label Assignment"
date: 2019-08-27 19:15:26
categories: arXiv_CL
tags: arXiv_CL Text_Classification Reinforcement_Learning Inference Classification
author: Yuning Mao, Jingjing Tian, Jiawei Han, Xiang Ren
mathjax: true
---

* content
{:toc}

##### Abstract
While existing hierarchical text classification (HTC) methods attempt to capture label hierarchies for model training, they either make local decisions regarding each label or completely ignore the hierarchy information during inference. To solve the mismatch between training and inference as well as modeling label dependencies in a more principled way, we formulate HTC as a Markov decision process and propose to learn a Label Assignment Policy via deep reinforcement learning to determine where to place an object and when to stop the assignment process. The proposed method, HiLAP, explores the hierarchy during both training and inference time in a consistent manner and makes inter-dependent decisions. As a general framework, HiLAP can incorporate different neural encoders as base models for end-to-end training. Experiments on five public datasets and four base models show that HiLAP yields an average improvement of 33.4% in Macro-F1 over flat classifiers and outperforms state-of-the-art HTC methods by a large margin. Data and code can be found at https://github.com/morningmoni/HiLAP.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.10419](http://arxiv.org/abs/1908.10419)

##### PDF
[http://arxiv.org/pdf/1908.10419](http://arxiv.org/pdf/1908.10419)

