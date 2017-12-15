---
layout: post
title: "Zoom Better to See Clearer: Human and Object Parsing with Hierarchical Auto-Zoom Net"
date: 2016-03-28 21:53:31
categories: arXiv_CV
tags: arXiv_CV CNN
author: Fangting Xia, Peng Wang, Liang-Chieh Chen, Alan L. Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
Parsing articulated objects, e.g. humans and animals, into semantic parts (e.g. body, head and arms, etc.) from natural images is a challenging and fundamental problem for computer vision. A big difficulty is the large variability of scale and location for objects and their corresponding parts. Even limited mistakes in estimating scale and location will degrade the parsing output and cause errors in boundary details. To tackle these difficulties, we propose a "Hierarchical Auto-Zoom Net" (HAZN) for object part parsing which adapts to the local scales of objects and parts. HAZN is a sequence of two "Auto-Zoom Net" (AZNs), each employing fully convolutional networks that perform two tasks: (1) predict the locations and scales of object instances (the first AZN) or their parts (the second AZN); (2) estimate the part scores for predicted object instance or part regions. Our model can adaptively "zoom" (resize) predicted image regions into their proper scales to refine the parsing. We conduct extensive experiments over the PASCAL part datasets on humans, horses, and cows. For humans, our approach significantly outperforms the state-of-the-arts by 5% mIOU and is especially better at segmenting small instances and small parts. We obtain similar improvements for parsing cows and horses over alternative methods. In summary, our strategy of first zooming into objects and then zooming into parts is very effective. It also enables us to process different regions of the image at different scales adaptively so that, for example, we do not need to waste computational resources scaling the entire image.

##### Abstract (translated by Google)
解析关节物体，例如人类和动物从自然图像转化为语义部分（例如身体，头部和手臂等）是计算机视觉的一个具有挑战性和根本性的问题。物体及其相应部分的尺度和位置的巨大变化是一个很大的困难。即使在估计尺度和位置方面有限的错误也会降低解析输出并导致边界细节的错误。为了解决这些困难，我们提出了一种适用于对象和零件局部尺度的“分层自动缩放网”（HAZN）。 HAZN是两个“自动缩放网络”（AZN）的序列，每个都使用完全卷积网络执行两个任务：（1）预测对象实例（第一个AZN）或其部分（第二个AZN） ; （2）估计预测的对象实例或部分区域的部分分数。我们的模型可以自适应地“缩放”（调整大小）预测的图像区域到合适的比例来优化解析。我们在人，马，牛的PASCAL部分数据集上进行了大量的实验。对于人类来说，我们的方法显着优于现有技术的5％mIOU，尤其在分割小型实例和小型零件方面更为出色。我们通过替代方法获得了类似的解析牛和马的改进。总之，我们首先放大对象然后放大部分的策略是非常有效的。它还使我们能够自适应地在不同的尺度上处理图像的不同区域，例如，我们不需要浪费计算资源来缩放整个图像。

##### URL
[https://arxiv.org/abs/1511.06881](https://arxiv.org/abs/1511.06881)

##### PDF
[https://arxiv.org/pdf/1511.06881](https://arxiv.org/pdf/1511.06881)

