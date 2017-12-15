---
layout: post
title: "Scale-aware Fast R-CNN for Pedestrian Detection"
date: 2016-06-25 09:26:07
categories: arXiv_CV
tags: arXiv_CV Detection
author: Jianan Li, Xiaodan Liang, ShengMei Shen, Tingfa Xu, Jiashi Feng, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we consider the problem of pedestrian detection in natural scenes. Intuitively, instances of pedestrians with different spatial scales may exhibit dramatically different features. Thus, large variance in instance scales, which results in undesirable large intra-category variance in features, may severely hurt the performance of modern object instance detection methods. We argue that this issue can be substantially alleviated by the divide-and-conquer philosophy. Taking pedestrian detection as an example, we illustrate how we can leverage this philosophy to develop a Scale-Aware Fast R-CNN (SAF R-CNN) framework. The model introduces multiple built-in sub-networks which detect pedestrians with scales from disjoint ranges. Outputs from all the sub-networks are then adaptively combined to generate the final detection results that are shown to be robust to large variance in instance scales, via a gate function defined over the sizes of object proposals. Extensive evaluations on several challenging pedestrian detection datasets well demonstrate the effectiveness of the proposed SAF R-CNN. Particularly, our method achieves state-of-the-art performance on Caltech, INRIA, and ETH, and obtains competitive results on KITTI.

##### Abstract (translated by Google)
在这项工作中，我们考虑自然场景中的行人检测问题。直观地说，具有不同空间尺度的行人实例可能表现出显着不同的特征。因此，实例尺度的大的变化导致了特征中的不希望有的大的类内变异，这可能严重地损害现代对象实例检测方法的性能。我们认为，这个问题可以通过分而治之的哲学大大缓解。以行人检测为例，我们说明了如何利用这一理念来开发一个规模感知快速R-CNN（SAF R-CNN）框架。该模型引入了多个内置的子网络，可以检测不相交范围内的行人。然后自适应地组合所有子网络的输出，以产生最终的检测结果，通过在对象提议的大小上定义的门函数，显示出对实例尺度的大的变化是稳健的。对几个具有挑战性的行人检测数据集进行广泛的评估，证明了所提出的SAF R-CNN的有效性。特别是，我们的方法达到了加州理工学院，INRIA和ETH的最先进的表现，并获得了KITTI的竞争结果。

##### URL
[https://arxiv.org/abs/1510.08160](https://arxiv.org/abs/1510.08160)

##### PDF
[https://arxiv.org/pdf/1510.08160](https://arxiv.org/pdf/1510.08160)

