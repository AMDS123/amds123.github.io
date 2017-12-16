---
layout: post
title: "Recovering Dense Tissue Multispectral Signal from in vivo RGB Images"
date: 2017-06-20 15:38:44
categories: arXiv_CV
tags: arXiv_CV Classification
author: Jianyu Lin, Neil T. Clancy, Daniel S. Elson
mathjax: true
---

* content
{:toc}

##### Abstract
Hyperspectral/multispectral imaging (HSI/MSI) contains rich information clinical applications, such as 1) narrow band imaging for vascular visualisation; 2) oxygen saturation for intraoperative perfusion monitoring and clinical decision making [1]; 3) tissue classification and identification of pathology [2]. The current systems which provide pixel-level HSI/MSI signal can be generally divided into two types: spatial scanning and spectral scanning. However, the trade-off between spatial/spectral resolution, the acquisition time, and the hardware complexity hampers implementation in real-world applications, especially intra-operatively. Acquiring high resolution images in real-time is important for HSI/MSI in intra-operative imaging, to alleviate the side effect caused by breathing, heartbeat, and other sources of motion. Therefore, we developed an algorithm to recover a pixel-level MSI stack using only the captured snapshot RGB images from a normal camera. We refer to this technique as "super-spectral-resolution". The proposed method enables recovery of pixel-level-dense MSI signals with 24 spectral bands at ~11 frames per second (FPS) on a GPU. Multispectral data captured from porcine bowel and sheep/rabbit uteri in vivo has been used for training, and the algorithm has been validated using unseen in vivo animal experiments.

##### Abstract (translated by Google)
高光谱/多光谱成像（HSI / MSI）包含丰富的信息临床应用，例如1）用于血管显像的窄带成像; 2）术中灌注监测和临床决策的氧饱和度[1]; 3）组织分类和病理鉴定[2]。目前提供像素级HSI / MSI信号的系统一般可以分为空间扫描和频谱扫描两种。然而，空间/光谱分辨率，采集时间和硬件复杂性之间的折衷妨碍了在实际应用中的实施，特别是在手术中。实时获取高分辨率图像对于HSI / MSI术中成像非常重要，可以缓解由呼吸，心跳和其他运动源引起的副作用。因此，我们开发了一种算法来恢复一个像素级的MSI堆栈，只使用捕获的普通摄像机的快照RGB图像。我们称这种技术为“超光谱分辨率”。所提出的方法使得能够在GPU上以约11帧每秒（FPS）恢复具有24个光谱带的像素级密集的MSI信号。从猪肠道和绵羊/兔子体内采集的多光谱数据已经用于训练，并且该算法已经使用看不见的体内动物实验进行验证。

##### URL
[https://arxiv.org/abs/1707.03468](https://arxiv.org/abs/1707.03468)

##### PDF
[https://arxiv.org/pdf/1707.03468](https://arxiv.org/pdf/1707.03468)

