---
layout: post
title: "Improved Dense Trajectory with Cross Streams"
date: 2016-04-29 13:39:40
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN Recognition
author: Katsunori Ohnishi, Masatoshi Hidaka, Tatsuya Harada
mathjax: true
---

* content
{:toc}

##### Abstract
Improved dense trajectories (iDT) have shown great performance in action recognition, and their combination with the two-stream approach has achieved state-of-the-art performance. It is, however, difficult for iDT to completely remove background trajectories from video with camera shaking. Trajectories in less discriminative regions should be given modest weights in order to create more discriminative local descriptors for action recognition. In addition, the two-stream approach, which learns appearance and motion information separately, cannot focus on motion in important regions when extracting features from spatial convolutional layers of the appearance network, and vice versa. In order to address the above mentioned problems, we propose a new local descriptor that pools a new convolutional layer obtained from crossing two networks along iDT. This new descriptor is calculated by applying discriminative weights learned from one network to a convolutional layer of the other network. Our method has achieved state-of-the-art performance on ordinal action recognition datasets, 92.3% on UCF101, and 66.2% on HMDB51.

##### Abstract (translated by Google)
改进的密集轨迹（iDT）在动作识别中表现出了很好的性能，并且它们与双流方法的结合已经达到了最先进的性能。然而，iDT很难从相机抖动的视频中完全消除背景轨迹。在较不区分的区域中的轨迹应该被赋予适度的权重，以便为动作识别创建更加区分性的局部描述符。另外，当从外观网络的空间卷积层提取特征时，分别学习外观和运动信息的双流方法不能集中于重要区域中的运动，反之亦然。为了解决上述问题，我们提出了一种新的局部描述符，它将沿着iDT跨越两个网络而获得的新的卷积层进行聚合。这个新的描述符是通过将从一个网络学习到的区分权重应用到另一个网络的卷积层来计算的。我们的方法已经在有序动作识别数据集上达到了最高水平的表现，UCF101为92.3％，HMDB51为66.2％。

##### URL
[https://arxiv.org/abs/1604.08826](https://arxiv.org/abs/1604.08826)

##### PDF
[https://arxiv.org/pdf/1604.08826](https://arxiv.org/pdf/1604.08826)

