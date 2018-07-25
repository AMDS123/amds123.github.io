---
layout: post
title: "Identity Preserving Face Completion for Large Ocular Region Occlusion"
date: 2018-07-23 18:13:16
categories: arXiv_CV
tags: arXiv_CV Face Deep_Learning
author: Yajie Zhao, Weikai Chen, Jun Xing, Xiaoming Li, Zach Bessinger, Fuchang Liu, Wangmeng Zuo, Ruigang Yang
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel deep learning approach to synthesize complete face images in the presence of large ocular region occlusions. This is motivated by recent surge of VR/AR displays that hinder face-to-face communications. Different from the state-of-the-art face inpainting methods that have no control over the synthesized content and can only handle frontal face pose, our approach can faithfully recover the missing content under various head poses while preserving the identity. At the core of our method is a novel generative network with dedicated constraints to regularize the synthesis process. To preserve the identity, our network takes an arbitrary occlusion-free image of the target identity to infer the missing content, and its high-level CNN features as an identity prior to regularize the searching space of generator. Since the input reference image may have a different pose, a pose map and a novel pose discriminator are further adopted to supervise the learning of implicit pose transformations. Our method is capable of generating coherent facial inpainting with consistent identity over videos with large variations of head motions. Experiments on both synthesized and real data demonstrate that our method greatly outperforms the state-of-the-art methods in terms of both synthesis quality and robustness.

##### Abstract (translated by Google)
我们提出了一种新的深度学习方法，用于在存在大眼睛区域遮挡的情况下合成完整的面部图像。最近，VR / AR显示器的激增阻碍了面对面的通信。与最先进的面部修复方法不同，无法控制合成内容并且只能处理正面姿势，我们的方法可以在保留身份的同时忠实地恢复各种头部姿势下的缺失内容。我们方法的核心是一个新的生成网络，具有专门的约束来规范合成过程。为了保持身份，我们的网络采用目标身份的任意无遮挡图像来推断缺失内容，并且在规范发生器的搜索空间之前将其高级CNN特征作为身份。由于输入参考图像可以具有不同的姿势，因此进一步采用姿势图和新颖的姿势鉴别器来监督隐式姿势变换的学习。我们的方法能够产生连贯的面部修复，并且在具有大的头部运动变化的视频上具有一致的身份。对合成数据和实际数据的实验表明，我们的方法在综合质量和稳健性方面都大大优于最先进的方法。

##### URL
[https://arxiv.org/abs/1807.08772](https://arxiv.org/abs/1807.08772)

##### PDF
[https://arxiv.org/pdf/1807.08772](https://arxiv.org/pdf/1807.08772)

