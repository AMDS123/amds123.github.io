---
layout: post
title: "Temporal Sequence Distillation: Towards Few-Frame Action Recognition in Videos"
date: 2018-08-15 13:59:00
categories: arXiv_CV
tags: arXiv_CV Knowledge Attention Action_Recognition Recognition
author: Zhaoyang Zhang, Zhanghui Kuang, Ping Luo, Litong Feng, Wei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Video Analytics Software as a Service (VA SaaS) has been rapidly growing in recent years. VA SaaS is typically accessed by users using a lightweight client. Because the transmission bandwidth between the client and cloud is usually limited and expensive, it brings great benefits to design cloud video analysis algorithms with a limited data transmission requirement. Although considerable research has been devoted to video analysis, to our best knowledge, little of them has paid attention to the transmission bandwidth limitation in SaaS. As the first attempt in this direction, this work introduces a problem of few-frame action recognition, which aims at maintaining high recognition accuracy, when accessing only a few frames during both training and test. Unlike previous work that processed dense frames, we present Temporal Sequence Distillation (TSD), which distills a long video sequence into a very short one for transmission. By end-to-end training with 3D CNNs for video action recognition, TSD learns a compact and discriminative temporal and spatial representation of video frames. On Kinetics dataset, TSD+I3D typically requires only 50\% of the number of frames compared to I3D, a state-of-the-art video action recognition algorithm, to achieve almost the same accuracies. The proposed TSD has three appealing advantages. Firstly, TSD has a lightweight architecture and can be deployed in the client, eg. mobile devices, to produce compressed representative frames to save transmission bandwidth. Secondly, TSD significantly reduces the computations to run video action recognition with compressed frames on the cloud, while maintaining high recognition accuracies. Thirdly, TSD can be plugged in as a preprocessing module of any existing 3D CNNs. Extensive experiments show the effectiveness and characteristics of TSD.

##### Abstract (translated by Google)
视频分析软件即服务（VA SaaS）近年来发展迅速。 VA SaaS通常由使用轻量级客户端的用户访问。由于客户端和云之间的传输带宽通常有限且昂贵，因此设计具有有限数据传输要求的云视频分析算法带来了巨大的好处。尽管已经对视频分析进行了大量研究，但据我们所知，其中很少有人关注SaaS中的传输带宽限制。作为这方面的第一次尝试，这项工作引入了一个小帧动作识别问题，旨在保持高识别精度，在训练和测试期间仅访问几帧。与之前处理密集帧的工作不同，我们提供时间序列蒸馏（TSD），它将长视频序列提取为非常短的视频序列以进行传输。通过用于视频动作识别的3D CNN的端到端训练，TSD学习视频帧的紧凑且有区别的时间和空间表示。在动力学数据集中，与I3D（一种最先进的视频动作识别算法）相比，TSD + I3D通常仅需要50％的帧数，以实现几乎相同的精度。拟议的TSD具有三个吸引人的优点。首先，TSD具有轻量级架构，可以部署在客户端中，例如。移动设备，产生压缩的代表帧以节省传输带宽。其次，TSD显着减少了在云上使用压缩帧运行视频动作识别的计算，同时保持高识别精度。第三，TSD可以作为任何现有3D CNN的预处理模块插入。大量实验表明TSD的有效性和特征。

##### URL
[http://arxiv.org/abs/1808.05085](http://arxiv.org/abs/1808.05085)

##### PDF
[http://arxiv.org/pdf/1808.05085](http://arxiv.org/pdf/1808.05085)

