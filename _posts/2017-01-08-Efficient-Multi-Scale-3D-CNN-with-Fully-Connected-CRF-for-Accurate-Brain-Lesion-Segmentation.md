---
layout: post
title: "Efficient Multi-Scale 3D CNN with Fully Connected CRF for Accurate Brain Lesion Segmentation"
date: 2017-01-08 13:55:35
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Konstantinos Kamnitsas, Christian Ledig, Virginia F.J. Newcombe, Joanna P. Simpson, Andrew D. Kane, David K. Menon, Daniel Rueckert, Ben Glocker
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a dual pathway, 11-layers deep, three-dimensional Convolutional Neural Network for the challenging task of brain lesion segmentation. The devised architecture is the result of an in-depth analysis of the limitations of current networks proposed for similar applications. To overcome the computational burden of processing 3D medical scans, we have devised an efficient and effective dense training scheme which joins the processing of adjacent image patches into one pass through the network while automatically adapting to the inherent class imbalance present in the data. Further, we analyze the development of deeper, thus more discriminative 3D CNNs. In order to incorporate both local and larger contextual information, we employ a dual pathway architecture that processes the input images at multiple scales simultaneously. For post-processing of the network's soft segmentation, we use a 3D fully connected Conditional Random Field which effectively removes false positives. Our pipeline is extensively evaluated on three challenging tasks of lesion segmentation in multi-channel MRI patient data with traumatic brain injuries, brain tumors, and ischemic stroke. We improve on the state-of-the-art for all three applications, with top ranking performance on the public benchmarks BRATS 2015 and ISLES 2015. Our method is computationally efficient, which allows its adoption in a variety of research and clinical settings. The source code of our implementation is made publicly available.

##### Abstract (translated by Google)
我们提出了一个双通道，11层深的三维卷积神经网络，用于脑病灶分割的挑战性任务。设计的架构是深入分析当前提出的类似应用网络的局限性的结果。为了克服处理三维医学扫描的计算负担，我们设计了一种高效而有效的密集训练方案，将相邻图像块的处理连接成一次通过网络，同时自动适应数据中存在的固有类别不平衡。此外，我们分析更深层次，因此更有鉴别力的3D CNNs的发展。为了结合本地和更大的上下文信息，我们采用双路径架构，同时处理多个尺度的输入图像。对于网络软分割的后处理，我们使用3D全连接的条件随机场来有效地去除误报。对于多通道MRI患者脑外伤，脑肿瘤和缺血性脑卒中患者数据中的三个具有挑战性的病灶分割任务，我们对其管道进行了广泛的评估。我们改进了所有三个应用程序的最新技术水平，在公共基准BRATS 2015和ISLES 2015上排名最高。我们的方法计算效率高，可以用于各种研究和临床环境。我们的实现的源代码是公开的。

##### URL
[https://arxiv.org/abs/1603.05959](https://arxiv.org/abs/1603.05959)

##### PDF
[https://arxiv.org/pdf/1603.05959](https://arxiv.org/pdf/1603.05959)

