---
layout: post
title: "Super SloMo: High Quality Estimation of Multiple Intermediate Frames for Video Interpolation"
date: 2017-11-30 21:05:15
categories: arXiv_CV
tags: arXiv_CV CNN
author: Huaizu Jiang, Deqing Sun, Varun Jampani, Ming-Hsuan Yang, Erik Learned-Miller, Jan Kautz
---

* content
{:toc}

##### Abstract
Given two consecutive frames, video interpolation aims at generating intermediate frame(s) to form both spatially and temporally coherent video sequences. While most existing methods focus on single-frame interpolation, we propose an end-to-end convolutional neural network for variable-length multi-frame video interpolation, where the motion interpretation and occlusion reasoning are jointly modeled. We start by computing bi-directional optical flow between the input images using a U-Net architecture. These flows are then linearly combined at each time step to approximate the intermediate bi-directional optical flows. These approximate flows, however, only work well in locally smooth regions and produce artifacts around motion boundaries. To address this shortcoming, we employ another U-Net to refine the approximated flow and also predict soft visibility maps. Finally, the two input images are warped and linearly fused to form each intermediate frame. By applying the visibility maps to the warped images before fusion, we exclude the contribution of occluded pixels to the interpolated intermediate frame to avoid artifacts. Since none of our learned network parameters are time-dependent, our approach is able to produce as many intermediate frames as needed. We use 1,132 video clips with 240-fps, containing 300K individual video frames, to train our network. Experimental results on several datasets, predicting different numbers of interpolated frames, demonstrate that our approach performs consistently better than existing methods.

##### Abstract (translated by Google)
给定两个连续的帧，视频内插旨在生成中间帧以形成空间和时间相干的视频序列。虽然大多数现有的方法都集中在单帧插值上，但是我们提出了一种用于可变长度多帧视频插值的端到端卷积神经网络，其中运动解释和遮挡推理被联合建模。我们首先通过使用U-Net架构来计算输入图像之间的双向光流。然后在每个时间步骤将这些流线性地组合以近似中间的双向光流。然而，这些近似的流动仅在局部平滑区域中运行良好，并在运动边界周围产生伪影。为了解决这个缺点，我们采用另一个U-Net来改进近似流量，并预测软性能见度图。最后，两个输入图像被扭曲并线性融合以形成每个中间帧。通过将可见性图应用于融合之前的变形图像，我们排除了被遮挡的像素对插入的中间帧的贡献以避免伪影。由于我们学习的网络参数都不依赖于时间，所以我们的方法能够根据需要生成尽可能多的中间帧。我们使用1,132个240 fps的视频剪辑，包含300K个人视频帧，来训练我们的网络。对几个数据集的实验结果，预测不同数量的内插帧，表明我们的方法执行一贯比现有的方法更好。

##### URL
[https://arxiv.org/abs/1712.00080](https://arxiv.org/abs/1712.00080)

