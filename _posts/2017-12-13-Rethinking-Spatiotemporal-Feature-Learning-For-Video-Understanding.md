---
layout: post
title: "Rethinking Spatiotemporal Feature Learning For Video Understanding"
date: 2017-12-13 16:40:55
categories: arXiv_CV
tags: arXiv_CV Video_Caption CNN Classification Detection
author: Saining Xie, Chen Sun, Jonathan Huang, Zhuowen Tu, Kevin Murphy
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we study 3D convolutional networks for video understanding tasks. Our starting point is the state-of-the-art I3D model, which "inflates" all the 2D filters of the Inception architecture to 3D. We first consider "deflating" the I3D model at various levels to understand the role of 3D convolutions. Interestingly, we found that 3D convolutions at the top layers of the network contribute more than 3D convolutions at the bottom layers, while also being computationally more efficient. This indicates that I3D is better at capturing high-level temporal patterns than low-level motion signals. We also consider replacing 3D convolutions with spatiotemporal-separable 3D convolutions (i.e., replacing convolution using a k * k * k filter with 1 * k * k followed by k * 1 * 1 filters); we show that such a model, which we call S3D, is 1.5x more computationally efficient (in terms of FLOPS) than I3D, and achieves better accuracy. Finally, we explore spatiotemporal feature gating on top of S3D. The resulting model, which we call S3D-G, outperforms the state-of-the-art I3D model by 3.5% accuracy on Kinetics and reduces the FLOPS by 34%. It also achieves a new state-of-the-art performance when transferred to other action classification (UCF-101 and HMDB-51) and detection (UCF-101 and JHMDB) datasets.

##### Abstract (translated by Google)
在本文中，我们研究用于视频理解任务的三维卷积网络。我们的出发点是最先进的I3D模型，它将Inception架构的所有2D滤镜“膨胀”为3D。我们首先考虑在各级“缩小”I3D模型来理解3D卷积的作用。有趣的是，我们发现网络顶层的3D卷积比底层的3D卷积贡献更多，而计算效率更高。这表明I3D在捕捉高层次的时间模式方面比低层的运动信号更好。我们也考虑用时空可分离的三维卷积替换三维卷积（即，用一个k * k * k滤波器替换卷积，其中k * k * k滤波器跟随着k * 1 * 1滤波器）。我们展示了这样的模型，我们称之为S3D，比I3D计算效率高1.5倍（按FLOPS计算），并且达到了更好的精度。最后，我们探索S3D上的时空特征门控。我们称之为S3D-G的模型在动力学方面的表现优于最先进的I3D模型，精度为3.5％，FLOPS降低了34％。当转移到其他行动分类（UCF-101和HMDB-51）和检测（UCF-101和JHMDB）数据集时，它还实现了新的最新性能。

##### URL
[http://arxiv.org/abs/1712.04851](http://arxiv.org/abs/1712.04851)

##### PDF
[http://arxiv.org/pdf/1712.04851](http://arxiv.org/pdf/1712.04851)

