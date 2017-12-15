---
layout: post
title: "Real-time Action Recognition with Enhanced Motion Vector CNNs"
date: 2016-04-26 13:21:37
categories: arXiv_CV
tags: arXiv_CV Knowledge Action_Recognition Recognition
author: Bowen Zhang, Limin Wang, Zhe Wang, Yu Qiao, Hanli Wang
mathjax: true
---

* content
{:toc}

##### Abstract
The deep two-stream architecture exhibited excellent performance on video based action recognition. The most computationally expensive step in this approach comes from the calculation of optical flow which prevents it to be real-time. This paper accelerates this architecture by replacing optical flow with motion vector which can be obtained directly from compressed videos without extra calculation. However, motion vector lacks fine structures, and contains noisy and inaccurate motion patterns, leading to the evident degradation of recognition performance. Our key insight for relieving this problem is that optical flow and motion vector are inherent correlated. Transferring the knowledge learned with optical flow CNN to motion vector CNN can significantly boost the performance of the latter. Specifically, we introduce three strategies for this, initialization transfer, supervision transfer and their combination. Experimental results show that our method achieves comparable recognition performance to the state-of-the-art, while our method can process 390.7 frames per second, which is 27 times faster than the original two-stream method.

##### Abstract (translated by Google)
深度双流架构在基于视频的动作识别方面表现出色。这种方法中计算量最大的步骤来自光流的计算，这阻止了它是实时的。本文通过将运动矢量替换成可以直接从压缩视频中获得的运动矢量而不需要额外的计算来加速这种结构。然而，运动矢量缺乏精细的结构，并且包含噪声和不准确的运动模式，导致识别性能的明显下降。我们解决这个问题的关键洞察力是光流和运动矢量是内在相关的。将光流CNN学到的知识转化为运动矢量CNN可以显着提高后者的性能。具体来说，我们介绍了三种策略，初始化转移，监督转移及其组合。实验结果表明，我们的方法实现了可比较的识别性能的最先进的，而我们的方法可以处理每秒390.7帧，比原来的双流方法快27倍。

##### URL
[https://arxiv.org/abs/1604.07669](https://arxiv.org/abs/1604.07669)

##### PDF
[https://arxiv.org/pdf/1604.07669](https://arxiv.org/pdf/1604.07669)

