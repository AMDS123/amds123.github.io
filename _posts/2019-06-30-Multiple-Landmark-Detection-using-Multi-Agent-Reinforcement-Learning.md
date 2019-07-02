---
layout: post
title: "Multiple Landmark Detection using Multi-Agent Reinforcement Learning"
date: 2019-06-30 05:14:23
categories: arXiv_CV
tags: arXiv_CV Knowledge Reinforcement_Learning Detection
author: Athanasios Vlontzos, Amir Alansary, Konstantinos Kamnitsas, Daniel Rueckert, Bernhard Kainz
mathjax: true
---

* content
{:toc}

##### Abstract
The detection of anatomical landmarks is a vital step for medical image analysis and applications for diagnosis, interpretation and guidance. Manual annotation of landmarks is a tedious process that requires domain-specific expertise and introduces inter-observer variability. This paper proposes a new detection approach for multiple landmarks based on multi-agent reinforcement learning. Our hypothesis is that the position of all anatomical landmarks is interdependent and non-random within the human anatomy, thus finding one landmark can help to deduce the location of others. Using a Deep Q-Network (DQN) architecture we construct an environment and agent with implicit inter-communication such that we can accommodate K agents acting and learning simultaneously, while they attempt to detect K different landmarks. During training the agents collaborate by sharing their accumulated knowledge for a collective gain. We compare our approach with state-of-the-art architectures and achieve significantly better accuracy by reducing the detection error by 50%, while requiring fewer computational resources and time to train compared to the naive approach of training K agents separately.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.00318](http://arxiv.org/abs/1907.00318)

##### PDF
[http://arxiv.org/pdf/1907.00318](http://arxiv.org/pdf/1907.00318)

