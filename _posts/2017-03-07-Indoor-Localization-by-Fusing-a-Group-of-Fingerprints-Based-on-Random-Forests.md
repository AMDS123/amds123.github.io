---
layout: post
title: "Indoor Localization by Fusing a Group of Fingerprints Based on Random Forests"
date: 2017-03-07 02:41:40
categories: arXiv_CV
tags: arXiv_CV
author: Xiansheng Guo, Nirwan Ansari, Huiyong Li
mathjax: true
---

* content
{:toc}

##### Abstract
Indoor localization based on SIngle Of Fingerprint (SIOF) is rather susceptible to the changing environment, multipath, and non-line-of-sight (NLOS) propagation. Building SIOF is also a very time-consuming process. Recently, we first proposed a GrOup Of Fingerprints (GOOF) to improve the localization accuracy and reduce the burden of building fingerprints. However, the main drawback is the timeliness. In this paper, we propose a novel localization framework by Fusing A Group Of fingerprinTs (FAGOT) based on random forests. In the offline phase, we first build a GOOF from different transformations of the received signals of multiple antennas. Then, we design multiple GOOF strong classifiers based on Random Forests (GOOF-RF) by training each fingerprint in the GOOF. In the online phase, we input the corresponding transformations of the real measurements into these strong classifiers to obtain multiple independent decisions. Finally, we propose a Sliding Window aIded Mode-based (SWIM) fusion algorithm to balance the localization accuracy and time. Our proposed approaches can work better in an unknown indoor scenario. The burden of building fingerprints can also be reduced drastically. We demonstrate the performance of our algorithms through simulations and real experimental data using two Universal Software Radio Peripheral (USRP) platforms.

##### Abstract (translated by Google)
基于指纹识别（SIOF）的室内定位非常容易受到环境变化，多路径和非视距（NLOS）传播的影响。建立SIOF也是一个非常耗时的过程。最近，我们首先提出了一个GOF指纹（GOF）来提高定位精度，减轻构建指纹的负担。但主要缺点是及时性。在本文中，我们提出了一个新的本地化框架融合了一组基于随机森林的指纹（FAGOT）。在离线阶段，我们首先从多个天线的接收信号的不同变换中建立一个GOOF。然后，通过训练GOOF中的每个指纹，设计了多个基于随机森林（GOOF-RF）的GOOF强分类器。在在线阶段，我们将实际测量的相应变换输入到这些强分类器中以获得多个独立的决定。最后，我们提出了一种基于滑动窗口模式（SWIM）融合算法来平衡定位精度和时间。我们提出的方法可以在未知的室内情况下更好地工作。构建指纹的负担也可以大大降低。我们通过使用两个通用软件无线电外设（USRP）平台的模拟和真实的实验数据演示了我们算法的性能。

##### URL
[https://arxiv.org/abs/1703.02185](https://arxiv.org/abs/1703.02185)

##### PDF
[https://arxiv.org/pdf/1703.02185](https://arxiv.org/pdf/1703.02185)

