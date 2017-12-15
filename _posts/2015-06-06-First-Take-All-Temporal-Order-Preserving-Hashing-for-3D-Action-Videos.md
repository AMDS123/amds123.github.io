---
layout: post
title: "First-Take-All: Temporal Order-Preserving Hashing for 3D Action Videos"
date: 2015-06-06 19:36:11
categories: arXiv_CV
tags: arXiv_CV Face Action_Recognition Recognition
author: Jun Ye, Hao Hu, Kai Li, Guo-Jun Qi, Kien A. Hua
mathjax: true
---

* content
{:toc}

##### Abstract
With the prevalence of the commodity depth cameras, the new paradigm of user interfaces based on 3D motion capturing and recognition have dramatically changed the way of interactions between human and computers. Human action recognition, as one of the key components in these devices, plays an important role to guarantee the quality of user experience. Although the model-driven methods have achieved huge success, they cannot provide a scalable solution for efficiently storing, retrieving and recognizing actions in the large-scale applications. These models are also vulnerable to the temporal translation and warping, as well as the variations in motion scales and execution rates. To address these challenges, we propose to treat the 3D human action recognition as a video-level hashing problem and propose a novel First-Take-All (FTA) Hashing algorithm capable of hashing the entire video into hash codes of fixed length. We demonstrate that this FTA algorithm produces a compact representation of the video invariant to the above mentioned variations, through which action recognition can be solved by an efficient nearest neighbor search by the Hamming distance between the FTA hash codes. Experiments on the public 3D human action datasets shows that the FTA algorithm can reach a recognition accuracy higher than 80%, with about 15 bits per frame considering there are 65 frames per video over the datasets.

##### Abstract (translated by Google)
随着商品化深度相机的普及，基于3D动作捕捉和识别的用户界面的新范例极大地改变了人机交互的方式。人类行为识别作为这些设备中的关键组件之一，对保证用户体验质量起着重要的作用。虽然模型驱动的方法已经取得了巨大的成功，但是它们不能提供用于在大规模应用中有效地存储，检索和识别动作的可伸缩解决方案。这些模型也容易受到时间平移和翘曲，以及运动尺度和执行率的变化。为了解决这些挑战，我们提出将三维人类行为识别视为一个视频级别的哈希问题，并提出一种能够将整个视频哈希成固定长度的哈希码的新颖的先合并（FTA）哈希算法。我们证明了这个FTA算法产生了一个紧凑的视频不变性的上述变化，通过它可以通过有效的最近邻搜索来解决FTA哈希码之间的汉明距离。对公共3D人体动作数据集的实验表明，FTA算法可以达到高于80％的识别精度，考虑到每个视频在数据集上有65帧，每帧大约15比特。

##### URL
[https://arxiv.org/abs/1506.02184](https://arxiv.org/abs/1506.02184)

##### PDF
[https://arxiv.org/pdf/1506.02184](https://arxiv.org/pdf/1506.02184)

