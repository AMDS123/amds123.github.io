---
layout: post
title: "PlaneMatch: Patch Coplanarity Prediction for Robust RGB-D Reconstruction"
date: 2018-03-24 14:35:40
categories: arXiv_CV
tags: arXiv_CV Face CNN Prediction SLAM
author: Yifei Shi, Kai Xu, Matthias Niessner, Szymon Rusinkiewicz, Thomas Funkhouser
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a novel RGB-D patch descriptor designed for detecting coplanar surfaces in SLAM reconstruction. The core of our method is a deep convolutional neural net that takes in RGB, depth, and normal information of a planar patch in an image and outputs a descriptor that can be used to find coplanar patches from other images.We train the network on 10 million triplets of coplanar and non-coplanar patches, and evaluate on a new coplanarity benchmark created from commodity RGB-D scans. Experiments show that our learned descriptor outperforms alternatives extended for this new task by a significant margin. In addition, we demonstrate the benefits of coplanarity matching in a robust RGBD reconstruction formulation.We find that coplanarity constraints detected with our method are sufficient to get reconstruction results comparable to state-of-the-art frameworks on most scenes, but outperform other methods on standard benchmarks when combined with a simple keypoint method.

##### Abstract (translated by Google)
我们引入了一种新颖的RGB-D补丁描述符，用于在SLAM重建中检测共面曲面。我们方法的核心是一个深卷积神经网络，它接收图像中平面斑点的RGB，深度和正常信息，并输出可用于从其他图像找到共面斑点的描述符。我们训练网络10百万三平面共面和非共面面片，并评估由商品RGB-D扫描产生的新共面性基准。实验表明，我们学过的描述符比这个新任务的延伸性要好得多。此外，我们证明了在一个稳健的RGBD重建公式中共面性匹配的好处。我们发现用我们的方法检测到的共面性约束足以获得与大多数场景中最先进的框架相媲美的重建结果，但优于其他方法在与简单的关键点方法相结合的标准基准测试中。

##### URL
[https://arxiv.org/abs/1803.08407](https://arxiv.org/abs/1803.08407)

##### PDF
[https://arxiv.org/pdf/1803.08407](https://arxiv.org/pdf/1803.08407)

