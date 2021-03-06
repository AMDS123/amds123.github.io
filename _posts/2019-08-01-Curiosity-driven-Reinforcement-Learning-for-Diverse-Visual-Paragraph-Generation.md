---
layout: post
title: "Curiosity-driven Reinforcement Learning for Diverse Visual Paragraph Generation"
date: 2019-08-01 01:33:28
categories: arXiv_CV
tags: arXiv_CV GAN Reinforcement_Learning Caption Prediction Relation
author: Yadan Luo, Zi Huang, Zheng Zhang, Jingjing Li, Yang Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Visual paragraph generation aims to automatically describe a given image from different perspectives and organize sentences in a coherent way. In this paper, we address three critical challenges for this task in a reinforcement learning setting: the mode collapse, the delayed feedback, and the time-consuming warm-up for policy networks. Generally, we propose a novel Curiosity-driven Reinforcement Learning (CRL) framework to jointly enhance the diversity and accuracy of the generated paragraphs. First, by modeling the paragraph captioning as a long-term decision-making process and measuring the prediction uncertainty of state transitions as intrinsic rewards, the model is incentivized to memorize precise but rarely spotted descriptions to context, rather than being biased towards frequent fragments and generic patterns. Second, since the extrinsic reward from evaluation is only available until the complete paragraph is generated, we estimate its expected value at each time step with temporal-difference learning, by considering the correlations between successive actions. Then the estimated extrinsic rewards are complemented by dense intrinsic rewards produced from the derived curiosity module, in order to encourage the policy to fully explore action space and find a global optimum. Third, discounted imitation learning is integrated for learning from human demonstrations, without separately performing the time-consuming warm-up in advance. Extensive experiments conducted on the Standford image-paragraph dataset demonstrate the effectiveness and efficiency of the proposed method, improving the performance by 38.4% compared with state-of-the-art.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.00169](http://arxiv.org/abs/1908.00169)

##### PDF
[http://arxiv.org/pdf/1908.00169](http://arxiv.org/pdf/1908.00169)

