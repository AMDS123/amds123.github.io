---
layout: post
title: "A Generative Map for Image-based Camera Localization"
date: 2019-02-18 13:18:36
categories: arXiv_CV
tags: arXiv_CV Attention
author: Mingpan Guo, Stefan Matthes, Jiaojiao Ye, Hao Shen
mathjax: true
---

* content
{:toc}

##### Abstract
In image-based camera localization systems, information about the environment is usually stored in some representation, which can be referred to as a map. Conventionally, most map representations are built upon hand-crafted features. Recently, neural networks have attracted attention as a data-driven map representation, and have shown promising results in visual localization. However, these neural network maps are generally unreadable and hard to interpret. A readable map is not only accessible to humans, but also provides a way to be verified when the ground truth pose is unavailable. To tackle this problem, we propose Generative Map, a new framework for learning human-readable neural network maps. Our framework can be used for localization as previous learning maps, and also allows us to inspect the map by querying images from specified viewpoints of interest. We combine a generative model with the Kalman filter, which exploits the sequential structure of the localization problem. This also allows our approach to naturally incorporate additional sensor information and a transition model of the system. For evaluation we use real world images from the 7-Scenes dataset. We show that our approach can be used for localization tasks. For readability, we demonstrate that our Generative Map can be queried with poses from the test sequence to generate images, which closely resemble the true images.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.11124](http://arxiv.org/abs/1902.11124)

##### PDF
[http://arxiv.org/pdf/1902.11124](http://arxiv.org/pdf/1902.11124)

