---
layout: post
title: "OffsetNet: Deep Learning for Localization in the Lung using Rendered Images"
date: 2018-09-15 04:15:16
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Tracking Deep_Learning
author: Jake Sganga, David Eng, Chauncey Graetzel, David Camarillo
mathjax: true
---

* content
{:toc}

##### Abstract
Navigating surgical tools in the dynamic and tortuous anatomy of the lung's airways requires accurate, real-time localization of the tools with respect to the preoperative scan of the anatomy. Such localization can inform human operators or enable closed-loop control by autonomous agents, which would require accuracy not yet reported in the literature. In this paper, we introduce a deep learning architecture, called OffsetNet, to accurately localize a bronchoscope in the lung in real-time. After training on only 30 minutes of recorded camera images in conserved regions of a lung phantom, OffsetNet tracks the bronchoscope's motion on a held-out recording through these same regions at an update rate of 47 Hz and an average position error of 1.4 mm. Because this model performs poorly in less conserved regions, we augment the training dataset with simulated images from these regions. To bridge the gap between camera and simulated domains, we implement domain randomization and a generative adversarial network (GAN). After training on simulated images, OffsetNet tracks the bronchoscope's motion in less conserved regions at an average position error of 2.4 mm, which meets conservative thresholds required for successful tracking.

##### Abstract (translated by Google)
在肺部气道的动态和曲折的解剖结构中导航手术工具需要相对于解剖结构的术前扫描准确，实时地定位工具。这种定位可以通知人类操作员或通过自主代理实现闭环控制，这需要文献中尚未报道的准确性。在本文中，我们引入了一种称为OffsetNet的深度学习架构，以实时准确地定位肺部支气管镜。在肺部模型的保守区域中仅记录30分钟记录的摄像机图像后，OffsetNet以47 Hz的更新速率和1.4 mm的平均位置误差通过这些相同区域跟踪支气管镜在保持记录上的运动。由于该模型在较不保守的区域中表现不佳，因此我们使用来自这些区域的模拟图像来增强训练数据集。为了弥合相机和模拟域之间的差距，我们实现了域随机化和生成对抗网络（GAN）。在对模拟图像进行训练后，OffsetNet在较不保守的区域跟踪支气管镜的运动，平均位置误差为2.4 mm，满足成功跟踪所需的保守阈值。

##### URL
[http://arxiv.org/abs/1809.05645](http://arxiv.org/abs/1809.05645)

##### PDF
[http://arxiv.org/pdf/1809.05645](http://arxiv.org/pdf/1809.05645)

