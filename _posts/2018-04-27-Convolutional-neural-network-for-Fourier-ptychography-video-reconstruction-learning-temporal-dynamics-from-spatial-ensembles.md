---
layout: post
title: "Convolutional neural network for Fourier ptychography video reconstruction: learning temporal dynamics from spatial ensembles"
date: 2018-04-27 02:53:25
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Thanh Nguyen, Yujia Xue, Yunzhe Li, Lei Tian, George Nehmetallah
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNNs) have gained tremendous success in solving complex inverse problems for both problems involving independent datasets from input-output pairs of static objects, as well as sequential datasets from dynamic objects. In order to learn the underlying temporal statistics, a video sequence is typically used at the cost of network complexity and computation. The aim of this work is to develop a novel CNN framework to reconstruct video sequence of dynamic live cells captured using a computational microscopy technique, Fourier ptychographic microscopy (FPM). The unique feature of the FPM is its capability to reconstruct images with both wide field-of-view (FOV) and high resolution, i.e. a large space-bandwidth-product (SBP), by taking a series of low resolution intensity images. For live cell imaging, a single FPM frame contains thousands of cell samples with different morphological features. Our idea is to fully exploit the statistical information provided by this large spatial ensembles so as to learn temporal information in a sequential measurement, without using any additional temporal dataset. Specifically, we show that it is possible to reconstruct high-SBP dynamic cell videos by a CNN trained only on the first FPM dataset captured at the beginning of a time-series experiment. Our CNN approach reconstructs a 12800x10800 pixels phase image using only ~25 seconds, a 50x speedup compared to the model-based FPM algorithm. In addition, the CNN further reduces the required number of images in each time frame by ~6x. Overall, this significantly improves the imaging throughput by reducing both the acquisition and computational times. Our technique demonstrates a promising deep learning approach to continuously monitor large live-cell populations over an extended time and gather useful spatial and temporal information with sub-cellular resolution.

##### Abstract (translated by Google)
卷积神经网络（CNNs）在解决复杂的反问题方面取得了巨大的成功，这些问题涉及静态物体的输入 - 输出对的独立数据集以及动态物体的顺序数据集。为了学习基础的时间统计，通常以网络复杂度和计算为代价来使用视频序列。这项工作的目的是开发一种新颖的CNN框架，以重建使用计算显微镜技术，傅里叶形态显微镜（FPM）捕获的动态活细胞的视频序列。 FPM的独特之处在于能够通过拍摄一系列低分辨率强度图像来重建具有宽视野（FOV）和高分辨率的图像，即大空间带宽乘积（SBP）。对于活细胞成像，单个FPM框架包含数千个具有不同形态特征的细胞样品。我们的想法是充分利用这些大型空间集合提供的统计信息，以便在顺序测量中学习时间信息，而无需使用任何附加的时间数据集。具体来说，我们表明可以通过仅在第一个时间序列实验开始时捕获的FPM数据集上训练的CNN重建高SBP动态细胞视频。与基于模型的FPM算法相比，我们的CNN方法仅使用约25秒即可重建12800x10800像素的相位图像，速度提高了50倍。此外，CNN进一步减少了每个时间帧所需的图像数量约6倍。总体而言，这通过减少采集和计算时间显着提高了成像吞吐量。我们的技术展示了一种有前景的深度学习方法，能够在较长时间内持续监测大型活细胞群，并通过亚细胞分辨率收集有用的空间和时间信息。

##### URL
[https://arxiv.org/abs/1805.00334](https://arxiv.org/abs/1805.00334)

##### PDF
[https://arxiv.org/pdf/1805.00334](https://arxiv.org/pdf/1805.00334)

