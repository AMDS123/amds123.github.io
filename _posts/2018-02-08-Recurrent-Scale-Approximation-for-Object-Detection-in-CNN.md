---
layout: post
title: "Recurrent Scale Approximation for Object Detection in CNN"
date: 2018-02-08 05:49:21
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face CNN Prediction Detection Face_Detection
author: Yu Liu, Hongyang Li, Junjie Yan, Fangyin Wei, Xiaogang Wang, Xiaoou Tang
mathjax: true
---

* content
{:toc}

##### Abstract
Since convolutional neural network (CNN) lacks an inherent mechanism to handle large scale variations, we always need to compute feature maps multiple times for multi-scale object detection, which has the bottleneck of computational cost in practice. To address this, we devise a recurrent scale approximation (RSA) to compute feature map once only, and only through this map can we approximate the rest maps on other levels. At the core of RSA is the recursive rolling out mechanism: given an initial map at a particular scale, it generates the prediction at a smaller scale that is half the size of input. To further increase efficiency and accuracy, we (a): design a scale-forecast network to globally predict potential scales in the image since there is no need to compute maps on all levels of the pyramid. (b): propose a landmark retracing network (LRN) to trace back locations of the regressed landmarks and generate a confidence score for each landmark; LRN can effectively alleviate false positives caused by the accumulated error in RSA. The whole system can be trained end-to-end in a unified CNN framework. Experiments demonstrate that our proposed algorithm is superior against state-of-the-art methods on face detection benchmarks and achieves comparable results for generic proposal generation. The source code of RSA is available at this http URL.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1707.09531](https://arxiv.org/abs/1707.09531)

##### PDF
[https://arxiv.org/pdf/1707.09531](https://arxiv.org/pdf/1707.09531)

