---
layout: post
title: "Frame-Recurrent Video Super-Resolution"
date: 2018-01-14 17:53:53
categories: arXiv_AI
tags: arXiv_AI Super_Resolution CNN
author: Mehdi S. M. Sajjadi, Raviteja Vemulapalli, Matthew Brown
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in video super-resolution have shown that convolutional neural networks combined with motion compensation are able to merge information from multiple low-resolution (LR) frames to generate high-quality images. Current state-of-the-art methods process a batch of LR frames to generate a single high-resolution (HR) frame and run this scheme in a sliding window fashion over the entire video, effectively treating the problem as a large number of separate multi-frame super-resolution tasks. This approach has two main weaknesses: 1) Each input frame is processed and warped multiple times, increasing the computational cost, and 2) each output frame is estimated independently conditioned on the input frames, limiting the system's ability to produce temporally consistent results. In this work, we propose an end-to-end trainable frame-recurrent video super-resolution framework that uses the previously inferred HR estimate to super-resolve the subsequent frame. This naturally encourages temporally consistent results and reduces the computational cost by warping only one image in each step. Furthermore, due to its recurrent nature, the proposed method has the ability to assimilate a large number of previous frames without increased computational demands. Extensive evaluations and comparisons with previous methods validate the strengths of our approach and demonstrate that the proposed framework is able to significantly outperform the current state of the art.

##### Abstract (translated by Google)
视频超分辨率的最新进展表明，结合运动补偿的卷积神经网络能够合并来自多个低分辨率（LR）帧的信息以生成高质量图像。当前最先进的方法处理一批LR帧以生成单个高分辨率（HR）帧，并以滑动窗口的方式在整个视频上运行该方案，有效地将问题看作是大量单独的多帧超分辨率任务。这种方法有两个主要弱点：1）每个输入帧被多次处理和变形，增加了计算成本; 2）每个输出帧是独立估计的，以输入帧为条件，限制了系统产生时间一致结果的能力。在这项工作中，我们提出了一个端到端的可训练帧循环视频超分辨率框架，使用以前推断的人力资源估计超解决后续的框架。这自然会鼓励时间上一致的结果，并通过在每一步中仅翘曲一个图像来降低计算成本。此外，由于其反复性质，所提出的方法有能力吸收大量以前的帧而不增加计算需求。与以前的方法进行广泛的评估和比较验证了我们的方法的优势，并证明所提出的框架能够显着地超越当前的技术水平。

##### URL
[https://arxiv.org/abs/1801.04590](https://arxiv.org/abs/1801.04590)

##### PDF
[https://arxiv.org/pdf/1801.04590](https://arxiv.org/pdf/1801.04590)

