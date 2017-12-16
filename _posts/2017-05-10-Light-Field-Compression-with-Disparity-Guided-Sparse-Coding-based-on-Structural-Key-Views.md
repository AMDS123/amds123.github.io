---
layout: post
title: "Light Field Compression with Disparity Guided Sparse Coding based on Structural Key Views"
date: 2017-05-10 07:30:34
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Jie Chen, Junhui Hou, Lap-Pui Chau
mathjax: true
---

* content
{:toc}

##### Abstract
Recent imaging technologies are rapidly evolving for sampling richer and more immersive representations of the 3D world. And one of the emerging technologies are light field (LF) cameras based on micro-lens arrays. To record the directional information of the light rays, a much larger storage space and transmission bandwidth are required by a LF image as compared with a conventional 2D image of similar spatial dimension, and the compression of LF data becomes a vital part of its application. In this paper, we propose a LF codec that fully exploits the intrinsic geometry between the LF sub-views by first approximating the LF with disparity guided sparse coding over a perspective shifted light field dictionary. The sparse coding is only based on several optimized Structural Key Views (SKV); however the entire LF can be recovered from the coding coefficients. By keeping the approximation identical between encoder and decoder, only the residuals of the non-key views, disparity map and the SKVs need to be compressed into the bit stream. An optimized SKV selection method is proposed such that most LF spatial information could be preserved. And to achieve optimum dictionary efficiency, the LF is divided into several Coding Regions (CR), over which the reconstruction works individually. Experiments and comparisons have been carried out over benchmark LF dataset, which show that the proposed SC-SKV codec produces convincing compression results in terms of both rate-distortion performance and visual quality compared with High Efficiency Video Coding (HEVC): with 47.87% BD-rate reduction and 1.59 dB BD-PSNR improvement achieved on average, especially with up to 4 dB improvement for low bit rate scenarios.

##### Abstract (translated by Google)
最近的成像技术正在迅速发展，以取样更丰富，更逼真的三维世界。而新兴的技术之一是基于微透镜阵列的光场（LF）相机。为了记录光线的方向信息，相比空间尺寸相似的传统2D图像，LF图像需要更大的存储空间和传输带宽，LF数据的压缩成为其应用的重要部分。在本文中，我们提出了一种LF编解码器，通过在透视移位光场字典中首先使用视差导引稀疏编码首先逼近LF，充分利用LF子视图之间的内在几何。稀疏编码仅基于几个优化的结构密钥视图（SKV）;但是整个LF可以从编码系数中恢复。通过保持编码器和解码器之间的近似一致，只有非关键视图的残差，视差图和SKV需要被压缩到比特流中。提出了一种优化的SKV选择方法，可以保留大部分LF空间信息。为了达到最佳的字典效率，LF被分成几个编码区域（CR），其中重建单独工作。在基准LF数据集上进行了实验和比较，结果表明，与高效率视频编码（HEVC）相比，所提出的SC-SKV编解码器在速率失真性能和视觉质量方面产生令人信服的压缩结果：具有47.87％的BD平均降低了1.59 dB BD-PSNR，特别是在低比特率情况下提高了4 dB。

##### URL
[https://arxiv.org/abs/1610.03684](https://arxiv.org/abs/1610.03684)

##### PDF
[https://arxiv.org/pdf/1610.03684](https://arxiv.org/pdf/1610.03684)

