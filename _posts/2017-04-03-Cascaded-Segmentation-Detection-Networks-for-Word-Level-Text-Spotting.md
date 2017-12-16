---
layout: post
title: "Cascaded Segmentation-Detection Networks for Word-Level Text Spotting"
date: 2017-04-03 23:55:13
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Detection
author: Siyang Qin, Roberto Manduchi
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce an algorithm for word-level text spotting that is able to accurately and reliably determine the bounding regions of individual words of text "in the wild". Our system is formed by the cascade of two convolutional neural networks. The first network is fully convolutional and is in charge of detecting areas containing text. This results in a very reliable but possibly inaccurate segmentation of the input image. The second network (inspired by the popular YOLO architecture) analyzes each segment produced in the first stage, and predicts oriented rectangular regions containing individual words. No post-processing (e.g. text line grouping) is necessary. With execution time of 450 ms for a 1000-by-560 image on a Titan X GPU, our system achieves the highest score to date among published algorithms on the ICDAR 2015 Incidental Scene Text dataset benchmark.

##### Abstract (translated by Google)
我们引入了一种能够准确可靠地确定“野外”文本中各个单词的边界区域的单词级文本识别算法。我们的系统由两个卷积神经网络的级联组成。第一个网络是完全卷积的，负责检测包含文本的区域。这导致输入图像的非常可靠但可能不准确的分割。第二个网络（受到流行的YOLO架构的启发）分析了第一阶段产生的每个段，并预测包含单个词的定向矩形区域。不需要后处理（例如文本行分组）。对于Titan X GPU上的1000×560图像，执行时间为450 ms，我们的系统达到了ICDAR 2015 Incidental Scene Text数据集基准测试中发布算法的最高分数。

##### URL
[https://arxiv.org/abs/1704.00834](https://arxiv.org/abs/1704.00834)

##### PDF
[https://arxiv.org/pdf/1704.00834](https://arxiv.org/pdf/1704.00834)

