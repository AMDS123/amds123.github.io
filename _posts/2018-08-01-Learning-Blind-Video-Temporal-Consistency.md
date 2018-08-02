---
layout: post
title: "Learning Blind Video Temporal Consistency"
date: 2018-08-01 17:59:15
categories: arXiv_CV
tags: arXiv_CV Knowledge Style_Transfer
author: Wei-Sheng Lai, Jia-Bin Huang, Oliver Wang, Eli Shechtman, Ersin Yumer, Ming-Hsuan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Applying image processing algorithms independently to each frame of a video often leads to undesired inconsistent results over time. Developing temporally consistent video-based extensions, however, requires domain knowledge for individual tasks and is unable to generalize to other applications. In this paper, we present an efficient end-to-end approach based on deep recurrent network for enforcing temporal consistency in a video. Our method takes the original unprocessed and per-frame processed videos as inputs to produce a temporally consistent video. Consequently, our approach is agnostic to specific image processing algorithms applied on the original video. We train the proposed network by minimizing both short-term and long-term temporal losses as well as the perceptual loss to strike a balance between temporal stability and perceptual similarity with the processed frames. At test time, our model does not require computing optical flow and thus achieves real-time speed even for high-resolution videos. We show that our single model can handle multiple and unseen tasks, including but not limited to artistic style transfer, enhancement, colorization, image-to-image translation and intrinsic image decomposition. Extensive objective evaluation and subject study demonstrate that the proposed approach performs favorably against the state-of-the-art methods on various types of videos.

##### Abstract (translated by Google)
将图像处理算法独立地应用于视频的每个帧通常会导致不期望的不一致结果。然而，开发时间上一致的基于视频的扩展需要针对单个任务的领域知识，并且无法推广到其他应用程序。在本文中，我们提出了一种基于深度循环网络的有效端到端方法，用于实现视频的时间一致性。我们的方法将原始未处理和每帧处理的视频作为输入，以产生时间上一致的视频。因此，我们的方法与应用于原始视频的特定图像处理算法无关。我们通过最小化短期和长期时间损失以及感知损失来训练所提出的网络，以在时间稳定性和与处理帧的感知相似性之间取得平衡。在测试时，我们的模型不需要计算光流，因此即使对于高分辨率视频也能实现实时速度。我们展示了我们的单一模型可以处理多个和看不见的任务，包括但不限于艺术风格转移，增强，着色，图像到图像转换和内在图像分解。广泛的客观评估和主题研究表明，所提出的方法对各种类型的视频的最新方法表现出色。

##### URL
[https://arxiv.org/abs/1808.00449](https://arxiv.org/abs/1808.00449)

##### PDF
[https://arxiv.org/pdf/1808.00449](https://arxiv.org/pdf/1808.00449)

