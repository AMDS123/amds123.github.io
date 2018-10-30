---
layout: post
title: "$A^2$-Nets: Double Attention Networks"
date: 2018-10-27 02:32:22
categories: arXiv_CV
tags: arXiv_CV Attention Action_Recognition Relation Recognition
author: Yunpeng Chen, Yannis Kalantidis, Jianshu Li, Shuicheng Yan, Jiashi Feng
mathjax: true
---

* content
{:toc}

##### Abstract
Learning to capture long-range relations is fundamental to image/video recognition. Existing CNN models generally rely on increasing depth to model such relations which is highly inefficient. In this work, we propose the "double attention block", a novel component that aggregates and propagates informative global features from the entire spatio-temporal space of input images/videos, enabling subsequent convolution layers to access features from the entire space efficiently. The component is designed with a double attention mechanism in two steps, where the first step gathers features from the entire space into a compact set through second-order attention pooling and the second step adaptively selects and distributes features to each location via another attention. The proposed double attention block is easy to adopt and can be plugged into existing deep neural networks conveniently. We conduct extensive ablation studies and experiments on both image and video recognition tasks for evaluating its performance. On the image recognition task, a ResNet-50 equipped with our double attention blocks outperforms a much larger ResNet-152 architecture on ImageNet-1k dataset with over 40% less the number of parameters and less FLOPs. On the action recognition task, our proposed model achieves the state-of-the-art results on the Kinetics and UCF-101 datasets with significantly higher efficiency than recent works.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.11579](http://arxiv.org/abs/1810.11579)

##### PDF
[http://arxiv.org/pdf/1810.11579](http://arxiv.org/pdf/1810.11579)

