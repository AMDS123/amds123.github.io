---
layout: post
title: "Joint Object and Part Segmentation using Deep Learned Potentials"
date: 2015-05-01 20:35:24
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Prediction
author: Peng Wang, Xiaohui Shen, Zhe Lin, Scott Cohen, Brian Price, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
Segmenting semantic objects from images and parsing them into their respective semantic parts are fundamental steps towards detailed object understanding in computer vision. In this paper, we propose a joint solution that tackles semantic object and part segmentation simultaneously, in which higher object-level context is provided to guide part segmentation, and more detailed part-level localization is utilized to refine object segmentation. Specifically, we first introduce the concept of semantic compositional parts (SCP) in which similar semantic parts are grouped and shared among different objects. A two-channel fully convolutional network (FCN) is then trained to provide the SCP and object potentials at each pixel. At the same time, a compact set of segments can also be obtained from the SCP predictions of the network. Given the potentials and the generated segments, in order to explore long-range context, we finally construct an efficient fully connected conditional random field (FCRF) to jointly predict the final object and part labels. Extensive evaluation on three different datasets shows that our approach can mutually enhance the performance of object and part segmentation, and outperforms the current state-of-the-art on both tasks.

##### Abstract (translated by Google)
从图像中分割出语义对象并将它们解析成它们各自的语义部分是在计算机视觉中细化对象理解的基本步骤。在本文中，我们提出了一个同时解决语义对象和零件分割的联合解决方案，其中提供了更高级的对象级上下文来指导零件分割，利用更详细的零件级定位来细化对象分割。具体来说，我们首先介绍语义构成部分（SCP）的概念，其中相似的语义部分被分组并在不同的对象之间共享。然后训练双通道完全卷积网络（FCN）以在每个像素处提供SCP和目标电位。同时，也可以从网络的SCP预测中获得一组紧凑的分段。为了探索远程环境，我们最后构建了一个高效的全连通条件随机场（FCRF）来联合预测最终的对象和部分标签。对三个不同数据集的广泛评估表明，我们的方法可以相互提高对象和零件分割的性能，并且在两个任务上都胜过当前的最新技术。

##### URL
[https://arxiv.org/abs/1505.00276](https://arxiv.org/abs/1505.00276)

##### PDF
[https://arxiv.org/pdf/1505.00276](https://arxiv.org/pdf/1505.00276)

