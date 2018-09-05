---
layout: post
title: "Optical Flow Super-Resolution Based on Image Guidence Using Convolutional Neural Network"
date: 2018-09-03 13:03:21
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN
author: Liping Zhang, Zongqing Lu, Qingmin Liao
mathjax: true
---

* content
{:toc}

##### Abstract
The convolutional neural network model for optical flow estimation usually outputs a low-resolution(LR) optical flow field. To obtain the corresponding full image resolution,interpolation and variational approach are the most common options, which do not effectively improve the results. With the motivation of various convolutional neural network(CNN) structures succeeded in single image super-resolution(SISR) task, an end-to-end convolutional neural network is proposed to reconstruct the high resolution(HR) optical flow field from initial LR optical flow with the guidence of the first frame used in optical flow estimation. Our optical flow super-resolution(OFSR) problem differs from the general SISR problem in two main aspects. Firstly, the optical flow includes less texture information than image so that the SISR CNN structures can't be directly used in our OFSR problem. Secondly, the initial LR optical flow data contains estimation error, while the LR image data for SISR is generally a bicubic downsampled, blurred, and noisy version of HR ground truth. We evaluate the proposed approach on two different optical flow estimation mehods and show that it can not only obtain the full image resolution, but generate more accurate optical flow field (Accuracy improve 15% on FlyingChairs, 13% on MPI Sintel) with sharper edges than the estimation result of original method.

##### Abstract (translated by Google)
用于光流估计的卷积神经网络模型通常输出低分辨率（LR）光流场。为了获得相应的完整图像分辨率，插值和变分方法是最常见的选项，不能有效地改善结果。随着各种卷积神经网络（CNN）结构在单图像超分辨率（SISR）任务中的成功，提出了一种端到端卷积神经网络，用于从初始LR光学重建高分辨率（HR）光流场。在光流估计中使用的第一帧的引导流动。我们的光流超分辨率（OFSR）问题在两个主要方面与一般SISR问题不同。首先，光流包括比图像更少的纹理信息，因此SISR CNN结构不能直接用于我们的OFSR问题。其次，初始LR光流数据包含估计误差，而SISR的LR图像数据通常是双基础下采样，模糊和HR基础事实的噪声版本。我们在两种不同的光流估计方法上评估了所提出的方法，并表明它不仅可以获得完整的图像分辨率，而且可以生成更精确的光流场（FlyingChairs的精度提高15％，MPI Sintel提高13％），边缘比原始方法的估计结果。

##### URL
[http://arxiv.org/abs/1809.00588](http://arxiv.org/abs/1809.00588)

##### PDF
[http://arxiv.org/pdf/1809.00588](http://arxiv.org/pdf/1809.00588)

