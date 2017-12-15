---
layout: post
title: "Click Carving: Segmenting Objects in Video with Point Clicks"
date: 2016-07-05 05:35:22
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Suyog Dutt Jain, Kristen Grauman
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel form of interactive video object segmentation where a few clicks by the user helps the system produce a full spatio-temporal segmentation of the object of interest. Whereas conventional interactive pipelines take the user's initialization as a starting point, we show the value in the system taking the lead even in initialization. In particular, for a given video frame, the system precomputes a ranked list of thousands of possible segmentation hypotheses (also referred to as object region proposals) using image and motion cues. Then, the user looks at the top ranked proposals, and clicks on the object boundary to carve away erroneous ones. This process iterates (typically 2-3 times), and each time the system revises the top ranked proposal set, until the user is satisfied with a resulting segmentation mask. Finally, the mask is propagated across the video to produce a spatio-temporal object tube. On three challenging datasets, we provide extensive comparisons with both existing work and simpler alternative methods. In all, the proposed Click Carving approach strikes an excellent balance of accuracy and human effort. It outperforms all similarly fast methods, and is competitive or better than those requiring 2 to 12 times the effort.

##### Abstract (translated by Google)
我们提出了一种新颖的交互式视频对象分割形式，用户点击几下就可以帮助系统产生感兴趣对象的完整空间 - 时间分割。而传统的交互式流水线以用户的初始化为起点，我们显示系统中的值即使在初始化中也处于领先地位。具体而言，对于给定的视频帧，系统使用图像和运动提示预先计算数千个可能的分段假设（也称为对象区域提议）的排序列表。然后，用户查看排名最高的提议，并且点击对象边界来去除错误的提议。这个过程迭代（通常2-3次），并且每次系统修改排名最高的提议集合，直到用户对得到的分段掩码满意为止。最后，掩模在视频上传播以产生时空物体管。在三个具有挑战性的数据集上，我们提供与现有工作和更简单的替代方法的广泛比较。总之，所提出的点击雕刻方法在准确性和人力上达到了极佳的平衡。它胜过所有类似的快速方法，比那些需要2到12倍努力的方法更具竞争力或更好。

##### URL
[https://arxiv.org/abs/1607.01115](https://arxiv.org/abs/1607.01115)

##### PDF
[https://arxiv.org/pdf/1607.01115](https://arxiv.org/pdf/1607.01115)

