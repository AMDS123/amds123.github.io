---
layout: post
title: "Predicting Deeper into the Future of Semantic Segmentation"
date: 2017-08-08 10:02:36
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Prediction
author: Pauline Luc, Natalia Neverova, Camille Couprie, Jakob Verbeek, Yann LeCun
mathjax: true
---

* content
{:toc}

##### Abstract
The ability to predict and therefore to anticipate the future is an important attribute of intelligence. It is also of utmost importance in real-time systems, e.g. in robotics or autonomous driving, which depend on visual scene understanding for decision making. While prediction of the raw RGB pixel values in future video frames has been studied in previous work, here we introduce the novel task of predicting semantic segmentations of future frames. Given a sequence of video frames, our goal is to predict segmentation maps of not yet observed video frames that lie up to a second or further in the future. We develop an autoregressive convolutional neural network that learns to iteratively generate multiple frames. Our results on the Cityscapes dataset show that directly predicting future segmentations is substantially better than predicting and then segmenting future RGB frames. Prediction results up to half a second in the future are visually convincing and are much more accurate than those of a baseline based on warping semantic segmentations using optical flow.

##### Abstract (translated by Google)
预测和预测未来的能力是智力的重要属性。在实时系统中，这也是最重要的。在机器人或自主驾驶中，依靠视觉场景理解来做出决策。虽然在以前的工作中已经研究了未来视频帧中的原始RGB像素值的预测，但是在这里我们介绍预测未来帧的语义分割的新任务。给定一个视频帧序列，我们的目标是预测未来观察到的视频帧的分割图，这些视频帧将在第二秒钟甚至更远的时间进行。我们开发了一个自回归卷积神经网络，学习迭代生成多个帧。我们在Cityscapes数据集上的结果显示，直接预测未来的分割比预测和分割未来的RGB帧好得多。未来的预测结果达到半秒钟，这在视觉上是令人信服的，并且比基于使用光流的翘曲语义分割的基线准确得多。

##### URL
[https://arxiv.org/abs/1703.07684](https://arxiv.org/abs/1703.07684)

##### PDF
[https://arxiv.org/pdf/1703.07684](https://arxiv.org/pdf/1703.07684)

