---
layout: post
title: "Don't Worry About the Weather: Unsupervised Condition-Dependent Domain Adaptation"
date: 2019-07-25 12:28:35
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation
author: Horia Porav, Tom Bruls, Paul Newman
mathjax: true
---

* content
{:toc}

##### Abstract
Modern models that perform system-critical tasks such as segmentation and localization exhibit good performance and robustness under ideal conditions (i.e. daytime, overcast) but performance degrades quickly and often catastrophically when input conditions change. In this work, we present a domain adaptation system that uses light-weight input adapters to pre-processes input images, irrespective of their appearance, in a way that makes them compatible with off-the-shelf computer vision tasks that are trained only on inputs with ideal conditions. No fine-tuning is performed on the off-the-shelf models, and the system is capable of incrementally training new input adapters in a self-supervised fashion, using the computer vision tasks as supervisors, when the input domain differs significantly from previously seen domains. We report large improvements in semantic segmentation and topological localization performance on two popular datasets, RobotCar and BDD.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.11004](http://arxiv.org/abs/1907.11004)

##### PDF
[http://arxiv.org/pdf/1907.11004](http://arxiv.org/pdf/1907.11004)

