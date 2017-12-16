---
layout: post
title: "Image Splicing Localization Using A Multi-Task Fully Convolutional Network"
date: 2017-09-06 22:23:05
categories: arXiv_CV
tags: arXiv_CV Face CNN
author: Ronald Salloum, Yuzhuo Ren, C.-C. Jay Kuo
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose a technique that utilizes a fully convolutional network (FCN) to localize image splicing attacks. We first evaluated a single-task FCN (SFCN) trained only on the surface label. Although the SFCN is shown to provide superior performance over existing methods, it still provides a coarse localization output in certain cases. Therefore, we propose the use of a multi-task FCN (MFCN) that utilizes two output branches for multi-task learning. One branch is used to learn the surface label, while the other branch is used to learn the edge or boundary of the spliced region. We trained the networks using the CASIA v2.0 dataset, and tested the trained models on the CASIA v1.0, Columbia Uncompressed, Carvalho, and the DARPA/NIST Nimble Challenge 2016 SCI datasets. Experiments show that the SFCN and MFCN outperform existing splicing localization algorithms, and that the MFCN can achieve finer localization than the SFCN.

##### Abstract (translated by Google)
在这项工作中，我们提出了一种利用完全卷积网络（FCN）来定位图像拼接攻击的技术。我们首先评估了仅在表面标签上训练的单任务FCN（SFCN）。虽然SFCN被证明可以提供比现有方法更优越的性能，但在某些情况下它仍然提供粗略的本地化输出。因此，我们提出使用多任务FCN（MFCN），它利用两个输出分支来进行多任务学习。一个分支用于学习表面标签，而另一个分支用于学习拼接区域的边缘或边界。我们使用CASIA v2.0数据集对网络进行训练，并在CASIA v1.0，Columbia Uncompressed，Carvalho和DARPA / NIST Nimble Challenge 2016 SCI数据集上测试了训练好的模型。实验表明，SFCN和MFCN优于现有的拼接定位算法，并且MFCN可以实现比SFCN更好的定位。

##### URL
[https://arxiv.org/abs/1709.02016](https://arxiv.org/abs/1709.02016)

##### PDF
[https://arxiv.org/pdf/1709.02016](https://arxiv.org/pdf/1709.02016)

