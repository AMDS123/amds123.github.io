---
layout: post
title: "ReconNet: Non-Iterative Reconstruction of Images from Compressively Sensed Random Measurements"
date: 2016-03-07 23:31:08
categories: arXiv_CV
tags: arXiv_CV Tracking CNN
author: Kuldeep Kulkarni, Suhas Lohit, Pavan Turaga, Ronan Kerviche, Amit Ashok
mathjax: true
---

* content
{:toc}

##### Abstract
The goal of this paper is to present a non-iterative and more importantly an extremely fast algorithm to reconstruct images from compressively sensed (CS) random measurements. To this end, we propose a novel convolutional neural network (CNN) architecture which takes in CS measurements of an image as input and outputs an intermediate reconstruction. We call this network, ReconNet. The intermediate reconstruction is fed into an off-the-shelf denoiser to obtain the final reconstructed image. On a standard dataset of images we show significant improvements in reconstruction results (both in terms of PSNR and time complexity) over state-of-the-art iterative CS reconstruction algorithms at various measurement rates. Further, through qualitative experiments on real data collected using our block single pixel camera (SPC), we show that our network is highly robust to sensor noise and can recover visually better quality images than competitive algorithms at extremely low sensing rates of 0.1 and 0.04. To demonstrate that our algorithm can recover semantically informative images even at a low measurement rate of 0.01, we present a very robust proof of concept real-time visual tracking application.

##### Abstract (translated by Google)
本文的目的是提出一个非迭代，更重要的是一个非常快速的算法来重建压缩感测（CS）随机测量图像。为此，我们提出了一种新的卷积神经网络（CNN）体系结构，它将图像的CS测量作为输入并输出中间重构。我们称这个网络为ReconNet。中间重建被送入现成的降噪器以获得最终的重建图像。在标准的图像数据集上，我们展示了重建结果（PSNR和时间复杂度）在不同测量速率下的最新迭代CS重建算法的重大改进。此外，通过对使用我们的块单像素相机（SPC）收集的实际数据进行定性实验，我们显示，我们的网络对传感器噪声具有高度的稳健性，并且可以在0.1和0.04的极低检测速率下，以比竞争算法更高的视觉恢复质量。为了证明我们的算法能够在0.01的低测量速率下恢复语义信息图像，我们提出了一个非常强大的实时视觉跟踪应用概念证明。

##### URL
[https://arxiv.org/abs/1601.06892](https://arxiv.org/abs/1601.06892)

##### PDF
[https://arxiv.org/pdf/1601.06892](https://arxiv.org/pdf/1601.06892)

