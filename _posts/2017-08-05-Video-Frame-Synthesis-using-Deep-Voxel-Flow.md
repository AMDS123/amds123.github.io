---
layout: post
title: "Video Frame Synthesis using Deep Voxel Flow"
date: 2017-08-05 04:43:44
categories: arXiv_CV
tags: arXiv_CV Quantitative
author: Ziwei Liu, Raymond A. Yeh, Xiaoou Tang, Yiming Liu, Aseem Agarwala
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of synthesizing new video frames in an existing video, either in-between existing frames (interpolation), or subsequent to them (extrapolation). This problem is challenging because video appearance and motion can be highly complex. Traditional optical-flow-based solutions often fail where flow estimation is challenging, while newer neural-network-based methods that hallucinate pixel values directly often produce blurry results. We combine the advantages of these two methods by training a deep network that learns to synthesize video frames by flowing pixel values from existing ones, which we call deep voxel flow. Our method requires no human supervision, and any video can be used as training data by dropping, and then learning to predict, existing frames. The technique is efficient, and can be applied at any video resolution. We demonstrate that our method produces results that both quantitatively and qualitatively improve upon the state-of-the-art.

##### Abstract (translated by Google)
我们解决了在现有视频中合成新视频帧的问题，无论是在现有帧（插值）之间，还是在其之后（外插）。这个问题很具挑战性，因为视频外观和动作可能非常复杂。传统的基于光流的解决方案通常在流量估算具有挑战性的情况下失败，而基于神经网络的新方法直接幻觉像素值通常会产生模糊的结果。我们结合这两种方法的优点，通过训练一个深度网络，通过从现有的像素值流动，学习合成视频帧，我们称之为深体素流。我们的方法不需要人工监督，任何视频都可以作为训练数据，通过丢弃，然后学习预测现有帧。该技术是有效的，可以应用于任何视频分辨率。我们证明，我们的方法产生的结果，在数量上和质量上都改进了最先进的水平。

##### URL
[https://arxiv.org/abs/1702.02463](https://arxiv.org/abs/1702.02463)

##### PDF
[https://arxiv.org/pdf/1702.02463](https://arxiv.org/pdf/1702.02463)

