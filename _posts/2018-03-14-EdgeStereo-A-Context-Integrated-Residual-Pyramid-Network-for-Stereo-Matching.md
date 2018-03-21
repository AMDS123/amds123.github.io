---
layout: post
title: "EdgeStereo: A Context Integrated Residual Pyramid Network for Stereo Matching"
date: 2018-03-14 10:36:54
categories: arXiv_CV
tags: arXiv_CV Regularization Object_Detection Attention CNN Detection
author: Xiao Song, Xu Zhao, Hanwen Hu, Liangji Fang
mathjax: true
---

* content
{:toc}

##### Abstract
Recently convolutional neural network (CNN) promotes the development of stereo matching greatly. Especially those end-to-end stereo methods achieve best performance. However less attention is paid on encoding context information, simplifying two-stage disparity learning pipeline and improving details in disparity maps. Differently we focus on these problems. Firstly, we propose an one-stage context pyramid based residual pyramid network (CP-RPN) for disparity estimation, in which a context pyramid is embedded to encode multi-scale context clues explicitly. Next, we design a CNN based multi-task learning network called EdgeStereo to recover missing details in disparity maps, utilizing mid-level features from edge detection task. In EdgeStereo, CP-RPN is integrated with a proposed edge detector HED$_\beta$ based on two-fold multi-task interactions. The end-to-end EdgeStereo outputs the edge map and disparity map directly from a stereo pair without any post-processing or regularization. We discover that edge detection task and stereo matching task can help each other in our EdgeStereo framework. Comprehensive experiments on stereo benchmarks such as Scene Flow and KITTI 2015 show that our method achieves state-of-the-art performance.

##### Abstract (translated by Google)
最近卷积神经网络（CNN）极大地促进了立体匹配的发展。特别是那些端到端的立体声方法实现最佳性能。然而，对编码上下文信息的关注较少，简化了两阶段视差学习流水线并改善了视差图中的细节。不同的是，我们专注于这些问题。首先，我们提出了一种基于一阶段上下文金字塔的残差金字塔网络（CP-RPN）进行视差估计，其中嵌入了上下文金字塔以明确地对多尺度上下文线索进行编码。接下来，我们设计了一个名为EdgeStereo的基于CNN的多任务学习网络，利用边缘检测任务中的中级特征来恢复视差图中的缺失细节。在EdgeStereo中，基于双重多任务交互，CP-RPN与建议的边缘检测器HED $ _ \ beta $集成在一起。端到端EdgeStereo直接从立体对输出边缘地图和视差图，而无需任何后期处理或正则化。我们发现边缘检测任务和立体匹配任务可以在我们的EdgeStereo框架中互相帮助。诸如Scene Flow和KITTI 2015等立体基准的全面实验表明，我们的方法达到了最先进的性能。

##### URL
[https://arxiv.org/abs/1803.05196](https://arxiv.org/abs/1803.05196)

##### PDF
[https://arxiv.org/pdf/1803.05196](https://arxiv.org/pdf/1803.05196)

