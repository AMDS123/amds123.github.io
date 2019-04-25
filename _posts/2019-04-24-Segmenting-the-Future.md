---
layout: post
title: "Segmenting the Future"
date: 2019-04-24 07:30:34
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation Semantic_Segmentation
author: Hsu-kuang Chiu, Ehsan Adeli, Juan Carlos Niebles
mathjax: true
---

* content
{:toc}

##### Abstract
Predicting the future is an important aspect for decision-making in robotics or autonomous driving systems, which heavily rely upon visual scene understanding. While prior work attempts to predict future video pixels, anticipate activities or forecast future scene semantic segments from segmentation of the preceding frames, methods that predict future semantic segmentation solely from the previous frame RGB data in a single end-to-end trainable model do not exist. In this paper, we propose a temporal encoder-decoder network architecture that encodes RGB frames from the past and decodes the future semantic segmentation. The network is coupled with a new knowledge distillation training framework specifically for the forecasting task. Our method, only seeing preceding video frames, implicitly models the scene segments while simultaneously accounting for the object dynamics to infer the future scene semantic segments. Our results on Cityscapes outperform the baseline and current state-of-the-art methods. Code is available at https://github.com/eddyhkchiu/segmenting_the_future/.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.10666](http://arxiv.org/abs/1904.10666)

##### PDF
[http://arxiv.org/pdf/1904.10666](http://arxiv.org/pdf/1904.10666)

