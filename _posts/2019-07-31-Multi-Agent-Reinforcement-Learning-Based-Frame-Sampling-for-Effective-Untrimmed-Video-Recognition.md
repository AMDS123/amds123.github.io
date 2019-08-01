---
layout: post
title: "Multi-Agent Reinforcement Learning Based Frame Sampling for Effective Untrimmed Video Recognition"
date: 2019-07-31 08:51:31
categories: arXiv_CV
tags: arXiv_CV Salient Reinforcement_Learning Video_Classification RNN Classification Recognition
author: Wenhao Wu, Dongliang He, Xiao Tan, Shifeng Chen, Shilei Wen
mathjax: true
---

* content
{:toc}

##### Abstract
Video Recognition has drawn great research interest and great progress has been made. A suitable frame sampling strategy can improve the accuracy and efficiency of recognition. However, mainstream solutions generally adopt hand-crafted frame sampling strategies for recognition. It could degrade the performance, especially in untrimmed videos, due to the variation of frame-level saliency. To this end, we concentrate on improving untrimmed video classification via developing a learning-based frame sampling strategy. We intuitively formulate the frame sampling procedure as multiple parallel Markov decision processes, each of which aims at picking out a frame/clip by gradually adjusting an initial sampling. Then we propose to solve the problems with multi-agent reinforcement learning (MARL). Our MARL framework is composed of a novel RNN-based context-aware observation network which jointly models context information among nearby agents and historical states of a specific agent, a policy network which generates the probability distribution over a predefined action space at each step and a classification network for reward calculation as well as final recognition. Extensive experimental results show that our MARL-based scheme remarkably outperforms hand-crafted strategies with various 2D and 3D baseline methods. Our single RGB model achieves a comparable performance of ActivityNet v1.3 champion submission with multi-modal multi-model fusion and new state-of-the-art results on YouTube Birds and YouTube Cars.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.13369](http://arxiv.org/abs/1907.13369)

##### PDF
[http://arxiv.org/pdf/1907.13369](http://arxiv.org/pdf/1907.13369)

