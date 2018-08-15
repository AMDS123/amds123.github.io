---
layout: post
title: "EdgeStereo: A Context Integrated Residual Pyramid Network for Stereo Matching"
date: 2018-08-14 10:05:02
categories: arXiv_CV
tags: arXiv_CV Regularization Embedding CNN Prediction Detection
author: Xiao Song, Xu Zhao, Hanwen Hu, Liangji Fang
mathjax: true
---

* content
{:toc}

##### Abstract
Recent convolutional neural networks, especially end-to-end disparity estimation models, achieve remarkable performance on stereo matching task. However, existed methods, even with the complicated cascade structure, may fail in the regions of non-textures, boundaries and tiny details. Focus on these problems, we propose a multi-task network EdgeStereo that is composed of a backbone disparity network and an edge sub-network. Given a binocular image pair, our model enables end-to-end prediction of both disparity map and edge map. Basically, we design a context pyramid to encode multi-scale context information in disparity branch, followed by a compact residual pyramid for cascaded refinement. To further preserve subtle details, our EdgeStereo model integrates edge cues by feature embedding and edge-aware smoothness loss regularization. Comparative results demonstrates that stereo matching and edge detection can help each other in the unified model. Furthermore, our method achieves state-of-art performance on both KITTI Stereo and Scene Flow benchmarks, which proves the effectiveness of our design.

##### Abstract (translated by Google)
最近的卷积神经网络，尤其是端到端视差估计模型，在立体匹配任务上实现了显着的性能。然而，即使具有复杂的级联结构，现有方法也可能在非纹理，边界和微小细节的区域中失败。针对这些问题，我们提出了一个由骨干差异网络和边缘子网络组成的多任务网络EdgeStereo。给定双目图像对，我们的模型能够实现视差图和边缘图的端到端预测。基本上，我们设计了一个上下文金字塔来编码视差分支中的多尺度上下文信息，然后是用于级联细化的紧凑残差金字塔。为了进一步保留细微的细节，我们的EdgeStereo模型通过特征嵌入和边缘感知平滑度损失正则化来集成边缘线索。比较结果表明，立体匹配和边缘检测可以在统一模型中相互帮助。此外，我们的方法在KITTI Stereo和Scene Flow基准测试中实现了最先进的性能，这证明了我们设计的有效性。

##### URL
[http://arxiv.org/abs/1803.05196](http://arxiv.org/abs/1803.05196)

##### PDF
[http://arxiv.org/pdf/1803.05196](http://arxiv.org/pdf/1803.05196)

