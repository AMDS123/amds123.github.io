---
layout: post
title: "Deep Image Compression via End-to-End Learning"
date: 2018-06-05 05:07:51
categories: arXiv_CV
tags: arXiv_CV Adversarial CNN Transfer_Learning Optimization
author: Haojie Liu, Tong Chen, Qiu Shen, Tao Yue, Zhan Ma
mathjax: true
---

* content
{:toc}

##### Abstract
We present a lossy image compression method based on deep convolutional neural networks (CNNs), which outperforms the existing BPG, WebP, JPEG2000 and JPEG as measured via multi-scale structural similarity (MS-SSIM), at the same bit rate. Currently, most of the CNNs based approaches train the network using a L2 loss between the reconstructions and the ground-truths in the pixel domain, which leads to over-smoothing results and visual quality degradation especially at a very low bit rate. Therefore, we improve the subjective quality with the combination of a perception loss and an adversarial loss additionally. To achieve better rate-distortion optimization (RDO), we also introduce an easy-to-hard transfer learning when adding quantization error and rate constraint. Finally, we evaluate our method on public Kodak and the Test Dataset P/M released by the Computer Vision Lab of ETH Zurich, resulting in averaged 7.81% and 19.1% BD-rate reduction over BPG, respectively.

##### Abstract (translated by Google)
我们提出了一种基于深度卷积神经网络（CNNs）的有损图像压缩方法，该方法在相同比特率下优于现有的BPG，WebP，JPEG2000和JPEG，通过多尺度结构相似性（MS-SSIM）测量。目前，大多数基于CNN的方法使用像素域中的重建和地面实况之间的L2损失来训练网络，这导致过度平滑的结果和视觉质量退化，尤其是在非常低的比特率下。因此，我们还通过感知损失和对抗性损失的组合来提高主观质量。为了实现更好的码率失真优化（RDO），我们在添加量化误差和速率约束时还引入了易于传输的学习。最后，我们评估了我们的公共柯达方法和苏黎世联邦理工学院计算机视觉实验室发布的测试数据集P / M，结果平均分别比BPG平均降低了7.81％和19.1％的BD率。

##### URL
[http://arxiv.org/abs/1806.01496](http://arxiv.org/abs/1806.01496)

##### PDF
[http://arxiv.org/pdf/1806.01496](http://arxiv.org/pdf/1806.01496)

