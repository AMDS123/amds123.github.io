---
layout: post
title: "Recurrent Scale Approximation for Object Detection in CNN"
date: 2017-07-29 15:38:27
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face_Detection CNN Detection
author: Yu Liu, Hongyang Li, Junjie Yan, Fangyin Wei, Xiaogang Wang, Xiaoou Tang
mathjax: true
---

* content
{:toc}

##### Abstract
Since convolutional neural network (CNN) lacks an inherent mechanism to handle large scale variations, we always need to compute feature maps multiple times for multi-scale object detection, which has the bottleneck of computational cost in practice. To address this, we devise a recurrent scale approximation (RSA) to compute feature map once only, and only through this map can we approximate the rest maps on other levels. At the core of RSA is the recursive rolling out mechanism: given an initial map on a particular scale, it generates the prediction on a smaller scale that is half the size of input. To further increase efficiency and accuracy, we (a): design a scale-forecast network to globally predict potential scales in the image since there is no need to compute maps on all levels of the pyramid. (b): propose a landmark retracing network (LRN) to retrace back locations of the regressed landmarks and generate a confidence score for each landmark; LRN can effectively alleviate false positives due to the accumulated error in RSA. The whole system could be trained end-to-end in a unified CNN framework. Experiments demonstrate that our proposed algorithm is superior against state-of-the-arts on face detection benchmarks and achieves comparable results for generic proposal generation. The source code of RSA is available at github.com/sciencefans/RSA-for-object-detection.

##### Abstract (translated by Google)
由于卷积神经网络（CNN）缺乏处理大规模变化的内在机制，因此对于多尺度目标检测，我们总是需要多次计算特征映射，这在实践中存在计算成本的瓶颈。为了解决这个问题，我们设计一个经常性尺度近似（RSA）来计算一次特征地图，只有通过这个地图我们才能近似其他地图上的其他地图。 RSA的核心是递归推出机制：给定一个特定尺度的初始地图，它会产生一个比输入尺寸小一半的较小尺度的预测。为了进一步提高效率和准确性，我们（a）：设计一个尺度预测网络来全局预测图像中的潜在尺度，因为不需要计算金字塔所有层面上的地图。 （b）：提出一个具有里程碑意义的回溯网络（LRN）来回溯倒退的地标的位置，并为每个地标产生一个置信度分数; LRN可以有效缓解由于RSA中累积误差导致的误报。整个系统可以在一个统一的CNN框架下进行端到端的培训。实验证明，我们提出的算法在人脸检测基准方面优于现有技术，并且为通用建议生成实现可比较的结果。 RSA的源代码可以在github.com/sciencefans/RSA-for-object-detection上找到。

##### URL
[https://arxiv.org/abs/1707.09531](https://arxiv.org/abs/1707.09531)

##### PDF
[https://arxiv.org/pdf/1707.09531](https://arxiv.org/pdf/1707.09531)

