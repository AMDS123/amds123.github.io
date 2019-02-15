---
layout: post
title: "Long and Short Memory Balancing in Visual Co-Tracking using Q-Learning"
date: 2019-02-14 04:17:29
categories: arXiv_CV
tags: arXiv_CV Attention Tracking Reinforcement_Learning Detection
author: Kourosh Meshgi, Maryam Sadat Mirzaei, Shigeyuki Oba
mathjax: true
---

* content
{:toc}

##### Abstract
Employing one or more additional classifiers to break the self-learning loop in tracing-by-detection has gained considerable attention. Most of such trackers merely utilize the redundancy to address the accumulating label error in the tracking loop, and suffer from high computational complexity as well as tracking challenges that may interrupt all classifiers (e.g. temporal occlusions). We propose the active co-tracking framework, in which the main classifier of the tracker labels samples of the video sequence, and only consults auxiliary classifier when it is uncertain. Based on the source of the uncertainty and the differences of two classifiers (e.g. accuracy, speed, update frequency, etc.), different policies should be taken to exchange the information between two classifiers. Here, we introduce a reinforcement learning approach to find the appropriate policy by considering the state of the tracker in a specific sequence. The proposed method yields promising results in comparison to the best tracking-by-detection approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.05211](http://arxiv.org/abs/1902.05211)

##### PDF
[http://arxiv.org/pdf/1902.05211](http://arxiv.org/pdf/1902.05211)

