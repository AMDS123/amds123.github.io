---
layout: post
title: "Real-time self-adaptive deep stereo"
date: 2018-10-12 09:17:53
categories: arXiv_CV
tags: arXiv_CV CNN
author: Alessio Tonioni, Fabio Tosi, Matteo Poggi, Stefano Mattoccia, Luigi Di Stefano
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural networks trained end-to-end are the undisputed state-of-the-art methods to regress dense disparity maps directly from stereo pairs. However, such methods suffer from notable accuracy drops when exposed to scenarios significantly different from those seen in the training phase (e.g.real vs synthetic images, indoor vs outdoor, etc). As it is unlikely to be able to gather enough samples to achieve effective training/ tuning in any target domain, we propose to perform unsupervised and continuous online adaptation of a deep stereo network in order to preserve its accuracy independently of the sensed environment. However, such a strategy can be extremely demanding regarding computational resources and thus not enabling real-time performance. Therefore, we address this side effect by introducing a new lightweight, yet effective, deep stereo architecture Modularly ADaptive Network (MADNet) and by developing Modular ADaptation (MAD), an algorithm to train independently only sub-portions of our model. By deploying MADNet together with MAD we propose the first ever realtime self-adaptive deep stereo system.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.05424](https://arxiv.org/abs/1810.05424)

##### PDF
[https://arxiv.org/pdf/1810.05424](https://arxiv.org/pdf/1810.05424)

