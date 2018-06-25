---
layout: post
title: "Video Inpainting by Jointly Learning Temporal Structure and Spatial Details"
date: 2018-06-22 03:32:57
categories: arXiv_CV
tags: arXiv_CV CNN Inference Deep_Learning Quantitative
author: Chuan Wang, Haibin Huang, Xiaoguang Han, Jue Wang
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new data-driven video inpainting method for recovering missing regions of video frames. A novel deep learning architecture is proposed which contains two sub-networks: a temporal structure inference network and a spatial detail recovering network. The temporal structure inference network is built upon a 3D fully convolutional architecture: It only learns to complete a low-resolution video volume given the expensive computational cost of 3D convolution. The low resolution result provides temporal guidance to the spatial detail recovering network, which performs image-based inpainting with a 2D fully convolutional network to produce recovered video frames in their original resolution. Such two-step network design ensures both the spatial quality of each frame and the temporal coherence across frames. Our method jointly trains both sub-networks in an end-to-end manner. We provide qualitative and quantitative evaluation on three datasets, demonstrating that our method outperforms previous learning-based video inpainting methods.

##### Abstract (translated by Google)
我们提出了一种新的数据驱动的视频修复方法，用于恢复视频帧的丢失区域。提出了一种新的深度学习体系结构，它包含两个子网络：时间结构推理网络和空间细节恢复网络。时间结构推理网络建立在三维完全卷积体系结构之上：由于3D卷积的昂贵计算成本，它仅学习完成低分辨率视频体积。低分辨率结果为空间细节恢复网络提供时间指导，该网络使用2D完全卷积网络执行基于图像的修复，以产生其原始分辨率的恢复的视频帧。这种两步网络设计确保了每个帧的空间质量和跨帧的时间一致性。我们的方法以端到端的方式联合训练这两个子网络。我们对三个数据集进行定性和定量评估，证明我们的方法优于先前的基于学习的视频修补方法。

##### URL
[http://arxiv.org/abs/1806.08482](http://arxiv.org/abs/1806.08482)

##### PDF
[http://arxiv.org/pdf/1806.08482](http://arxiv.org/pdf/1806.08482)

