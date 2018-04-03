---
layout: post
title: "Deep Residual Learning for Accelerated MRI using Magnitude and Phase Networks"
date: 2018-04-02 09:08:02
categories: arXiv_AI
tags: arXiv_AI Deep_Learning
author: Dongwook Lee, Jaejun Yoo, Sungho Tak, Jong Chul Ye
mathjax: true
---

* content
{:toc}

##### Abstract
Accelerated magnetic resonance (MR) scan acquisition with compressed sensing (CS) and parallel imaging is a powerful method to reduce MR imaging scan time. However, many reconstruction algorithms have high computational costs. To address this, we investigate deep residual learning networks to remove aliasing artifacts from artifact corrupted images. The proposed deep residual learning networks are composed of magnitude and phase networks that are separately trained. If both phase and magnitude information are available, the proposed algorithm can work as an iterative k-space interpolation algorithm using framelet representation. When only magnitude data is available, the proposed approach works as an image domain post-processing algorithm. Even with strong coherent aliasing artifacts, the proposed network successfully learned and removed the aliasing artifacts, whereas current parallel and CS reconstruction methods were unable to remove these artifacts. Comparisons using single and multiple coil show that the proposed residual network provides good reconstruction results with orders of magnitude faster computational time than existing compressed sensing methods. The proposed deep learning framework may have a great potential for accelerated MR reconstruction by generating accurate results immediately.

##### Abstract (translated by Google)
利用压缩感测（CS）和平行成像进行加速磁共振（MR）扫描采集是减少MR成像扫描时间的有效方法。然而，许多重建算法具有高计算成本。为了解决这个问题，我们研究了深度残留学习网络，以消除伪像损坏图像中的混叠伪像。所提出的深度剩余学习网络由经过分别训练的幅度网络和相位网络组成。如果相位和幅度信息都可用，则所提出的算法可以作为使用框架表示的迭代k空间插值算法。当只有量级数据可用时，所提出的方法用作图像域后处理算法。即使有强烈的相干锯齿伪影，所提出的网络也能成功地学习和消除锯齿伪影，而目前的并行和CS重建方法无法去除这些伪影。使用单线圈和多线圈的比较表明，所提出的残留网络提供了比现有压缩感测方法计算时间快几个数量级的良好重建结果。所提出的深度学习框架可能通过立即产生精确的结果而具有加速MR重建的巨大潜力。

##### URL
[http://arxiv.org/abs/1804.00432](http://arxiv.org/abs/1804.00432)

##### PDF
[http://arxiv.org/pdf/1804.00432](http://arxiv.org/pdf/1804.00432)

