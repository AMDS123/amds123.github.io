---
layout: post
title: "A Divide-and-Conquer Approach to Compressed Sensing MRI"
date: 2018-03-27 06:07:17
categories: arXiv_CV
tags: arXiv_CV Quantitative
author: Liyan Sun, Zhiwen Fan, Xinghao Ding, Congbo Cai, Yue Huang, John Paisley
mathjax: true
---

* content
{:toc}

##### Abstract
Compressed sensing (CS) theory assures us that we can accurately reconstruct magnetic resonance images using fewer k-space measurements than the Nyquist sampling rate requires. In traditional CS-MRI inversion methods, the fact that the energy within the Fourier measurement domain is distributed non-uniformly is often neglected during reconstruction. As a result, more densely sampled low-frequency information tends to dominate penalization schemes for reconstructing MRI at the expense of high-frequency details. In this paper, we propose a new framework for CS-MRI inversion in which we decompose the observed k-space data into "subspaces" via sets of filters in a lossless way, and reconstruct the images in these various spaces individually using off-the-shelf algorithms. We then fuse the results to obtain the final reconstruction. In this way we are able to focus reconstruction on frequency information within the entire k-space more equally, preserving both high and low frequency details. We demonstrate that the proposed framework is competitive with state-of-the-art methods in CS-MRI in terms of quantitative performance, and often improves an algorithm's results qualitatively compared with it's direct application to k-space.

##### Abstract (translated by Google)
压缩感知（CS）理论确保我们能够使用比奈奎斯特采样率所需要的更少的k空间测量精确地重建磁共振图像。在传统的CS-MRI反演方法中，傅立叶测量域内的能量分布不均匀的事实在重建期间经常被忽略。结果，更密集采样的低频信息倾向于支配以高频细节为代价重建MRI的惩罚方案。在本文中，我们提出了一个CS-MRI反演的新框架，其中我们通过无损方式将观察到的k空间数据分解成“子空间”，并且在这些不同空间中分别使用off-the -shelf算法。然后我们融合结果以获得最终的重建。通过这种方式，我们能够更平均地重建整个k空间内的频率信息，同时保留高频和低频细节。我们证明所提出的框架在定量性能方面与CS-MRI中的最先进方法相比具有竞争性，并且通常相比于其直接应用于k空间而定性地提高算法结果。

##### URL
[https://arxiv.org/abs/1803.09909](https://arxiv.org/abs/1803.09909)

##### PDF
[https://arxiv.org/pdf/1803.09909](https://arxiv.org/pdf/1803.09909)

