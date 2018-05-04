---
layout: post
title: "Latent Fingerprint Recognition: Role of Texture Template"
date: 2018-04-27 04:26:03
categories: arXiv_CV
tags: arXiv_CV CNN Recognition
author: Kai Cao, Anil K. Jain
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a texture template approach, consisting of a set of virtual minutiae, to improve the overall latent fingerprint recognition accuracy. To compensate for the lack of sufficient number of minutiae in poor quality latent prints, we generate a set of virtual minutiae. However, due to a large number of these regularly placed virtual minutiae, texture based template matching has a large computational requirement compared to matching true minutiae templates. To improve both the accuracy and efficiency of the texture template matching, we investigate: i) both original and enhanced fingerprint patches for training convolutional neural networks (ConvNets) to improve the distinctiveness of descriptors associated with each virtual minutiae, ii) smaller patches around virtual minutiae and a fast ConvNet architecture to speed up descriptor extraction, iii) reduce the descriptor length, iv) a modified hierarchical graph matching strategy to improve the matching speed, and v) extraction of multiple texture templates to boost the performance. Experiments on NIST SD27 latent database show that the above strategies can improve the matching speed from 11 ms (24 threads) per comparison (between a latent and a reference print) to only 7.7 ms (single thread) per comparison while improving the rank-1 accuracy by 8.9% against 10K gallery.

##### Abstract (translated by Google)
我们提出了一种纹理模板方法，由一组虚拟细节组成，以提高整体潜在指纹识别的准确性。为了补偿缺乏足够数量的劣质潜在印刷品中的细节，我们生成了一组虚拟细节。然而，由于大量的这些定期放置的虚拟细节，与匹配真细节模板相比，基于纹理的模板匹配具有较大的计算需求。为了提高纹理模板匹配的准确性和效率，我们研究：i）用于训练卷积神经网络（ConvNets）的原始和增强指纹斑块，以改善与每个虚拟细节点相关的描述符的独特性，ii）围绕虚拟细节点和快速ConvNet体系结构来加速描述符提取，iii）减少描述符长度，iv）修改后的分层图匹配策略以提高匹配速度，以及v）提取多个纹理模板以提高性能。在NIST SD27潜在数据库上进行的实验表明，上述策略可以将匹配速度从每比较（潜在和参考打印之间）的11ms（24线程）提高到每比较仅7.7ms（单线程），同时提高等级1对10K画廊的准确率为8.9％。

##### URL
[https://arxiv.org/abs/1804.10337](https://arxiv.org/abs/1804.10337)

##### PDF
[https://arxiv.org/pdf/1804.10337](https://arxiv.org/pdf/1804.10337)

