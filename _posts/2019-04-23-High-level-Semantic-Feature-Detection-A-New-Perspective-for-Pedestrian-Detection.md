---
layout: post
title: "High-level Semantic Feature Detection: A New Perspective for Pedestrian Detection"
date: 2019-04-23 14:42:58
categories: arXiv_CV
tags: arXiv_CV Object_Detection Deep_Learning Prediction Detection
author: Wei Liu, Shengcai Liao, Weiqiang Ren, Weidong Hu, Yinan Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection generally requires sliding-window classifiers in tradition or anchor-based predictions in modern deep learning approaches. However, either of these approaches requires tedious configurations in windows or anchors. In this paper, taking pedestrian detection as an example, we provide a new perspective where detecting objects is motivated as a high-level semantic feature detection task. Like edges, corners, blobs and other feature detectors, the proposed detector scans for feature points all over the image, for which the convolution is naturally suited. However, unlike these traditional low-level features, the proposed detector goes for a higher-level abstraction, that is, we are looking for central points where there are pedestrians, and modern deep models are already capable of such a high-level semantic abstraction. Besides, like blob detection, we also predict the scales of the pedestrian points, which is also a straightforward convolution. Therefore, in this paper, pedestrian detection is simplified as a straightforward center and scale prediction task through convolutions. This way, the proposed method enjoys an anchor-free setting. Though structurally simple, it presents competitive accuracy and good speed on challenging pedestrian detection benchmarks, and hence leading to a new attractive pedestrian detector. Code and models will be available at \url{https://github.com/liuwei16/CSP}.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.02948](http://arxiv.org/abs/1904.02948)

##### PDF
[http://arxiv.org/pdf/1904.02948](http://arxiv.org/pdf/1904.02948)

