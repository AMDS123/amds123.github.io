---
layout: post
title: "Deep learning approach to Fourier ptychographic microscopy"
date: 2018-07-30 22:59:06
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN CNN Transfer_Learning Deep_Learning Prediction
author: Thanh Nguyen, Yujia Xue, Yunzhe Li, Lei Tian, George Nehmetallah
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNNs) have gained tremendous success in solving complex inverse problems. The aim of this work is to develop a novel CNN framework to reconstruct video sequence of dynamic live cells captured using a computational microscopy technique, Fourier ptychographic microscopy (FPM). The unique feature of the FPM is its capability to reconstruct images with both wide field-of-view (FOV) and high resolution, i.e. a large space-bandwidth-product (SBP), by taking a series of low resolution intensity images. For live cell imaging, a single FPM frame contains thousands of cell samples with different morphological features. Our idea is to fully exploit the statistical information provided by this large spatial ensemble so as to make predictions in a sequential measurement, without using any additional temporal dataset. Specifically, we show that it is possible to reconstruct high-SBP dynamic cell videos by a CNN trained only on the first FPM dataset captured at the beginning of a time-series experiment. Our CNN approach reconstructs a 12800X10800 pixels phase image using only ~25 seconds, a 50X speedup compared to the model-based FPM algorithm. In addition, the CNN further reduces the required number of images in each time frame by ~6X. Overall, this significantly improves the imaging throughput by reducing both the acquisition and computational times. The proposed CNN is based on the conditional generative adversarial network (cGAN) framework. Additionally, we also exploit transfer learning so that our pre-trained CNN can be further optimized to image other cell types. Our technique demonstrates a promising deep learning approach to continuously monitor large live-cell populations over an extended time and gather useful spatial and temporal information with sub-cellular resolution.

##### Abstract (translated by Google)
卷积神经网络（CNN）在解决复杂的逆问题方面取得了巨大的成功。这项工作的目的是开发一种新的CNN框架，以重建使用计算显微镜技术，傅立叶重叠显微镜（FPM）捕获的动态活细胞的视频序列。 FPM的独特之处在于它能够通过拍摄一系列低分辨率强度图像来重建具有宽视场（FOV）和高分辨率的图像，即大空间带宽积（SBP）。对于活细胞成像，单个FPM框架包含数千个具有不同形态特征的细胞样本。我们的想法是充分利用这个大空间集合提供的统计信息，以便在顺序测量中进行预测，而无需使用任何额外的时间数据集。具体来说，我们表明，可以通过仅在时间序列实验开始时捕获的第一个FPM数据集上训练的CNN重建高SBP动态单元视频。我们的CNN方法仅使用~25秒重建12800X10800像素相位图像，与基于模型的FPM算法相比，速度提高了50倍。此外，CNN进一步将每个时间帧中所需的图像数量减少了约6倍。总的来说，这通过减少采集和计算时间显着提高了成像吞吐量。提议的CNN基于条件生成对抗网络（cGAN）框架。此外，我们还利用转移学习，以便我们的预训练CNN可以进一步优化，以成像其他细胞类型。我们的技术展示了一种有前途的深度学习方法，可以在较长时间内持续监测大型活细胞群，并通过亚细胞分辨率收集有用的空间和时间信息。

##### URL
[http://arxiv.org/abs/1805.00334](http://arxiv.org/abs/1805.00334)

##### PDF
[http://arxiv.org/pdf/1805.00334](http://arxiv.org/pdf/1805.00334)

