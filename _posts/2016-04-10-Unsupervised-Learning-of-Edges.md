---
layout: post
title: "Unsupervised Learning of Edges"
date: 2016-04-10 21:55:43
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Detection
author: Yin Li, Manohar Paluri, James M. Rehg, Piotr Dollár
mathjax: true
---

* content
{:toc}

##### Abstract
Data-driven approaches for edge detection have proven effective and achieve top results on modern benchmarks. However, all current data-driven edge detectors require manual supervision for training in the form of hand-labeled region segments or object boundaries. Specifically, human annotators mark semantically meaningful edges which are subsequently used for training. Is this form of strong, high-level supervision actually necessary to learn to accurately detect edges? In this work we present a simple yet effective approach for training edge detectors without human supervision. To this end we utilize motion, and more specifically, the only input to our method is noisy semi-dense matches between frames. We begin with only a rudimentary knowledge of edges (in the form of image gradients), and alternate between improving motion estimation and edge detection in turn. Using a large corpus of video data, we show that edge detectors trained using our unsupervised scheme approach the performance of the same methods trained with full supervision (within 3-5%). Finally, we show that when using a deep network for the edge detector, our approach provides a novel pre-training scheme for object detection.

##### Abstract (translated by Google)
数据驱动的边缘检测方法已被证明是有效的，并在现代基准测试中取得了最好的结果。然而，当前所有的数据驱动的边缘检测器都需要人工监控以手动标记的区域片段或对象边界的形式进行训练。具体来说，人类注释器标记语义上有意义的边缘，随后用于训练。为了准确地检测边缘，实际上是否需要这种强有力的高层监督？在这项工作中，我们提出了一个简单而有效的方法来训练边缘探测器，无需人工监控为此，我们利用运动，更具体地说，我们方法的唯一输入是帧之间的噪声半密集匹配。我们只从边缘的基本知识（以图像梯度的形式）开始，并依次改进运动估计和边缘检测。使用大量视频数据，我们显示使用我们的无监督方案训练的边缘检测器接近完全监督（3-5％）训练的相同方法的性能。最后，我们展示了当使用边缘检测器的深度网络时，我们的方法为对象检测提供了一种新型的预训练方案。

##### URL
[https://arxiv.org/abs/1511.04166](https://arxiv.org/abs/1511.04166)

##### PDF
[https://arxiv.org/pdf/1511.04166](https://arxiv.org/pdf/1511.04166)

