---
layout: post
title: "Dual Recovery Network with Online Compensation for Image Super-Resolution"
date: 2017-01-23 05:27:42
categories: arXiv_CV
tags: arXiv_CV Super_Resolution
author: Sifeng Xia, Wenhan Yang, Tiesong Zhao, Jiaying Liu
mathjax: true
---

* content
{:toc}

##### Abstract
The image super-resolution (SR) methods will essentially lead to a loss of some high-frequency (HF) information when predicting high-resolution (HR) images from low-resolution (LR) images without using external references. To address that, we additionally utilize online retrieved data to facilitate image SR in a unified deep framework. A novel dual high-frequency recovery network (DHN) is proposed to predict an HR image with three parts: an LR image, an internal inferred HF (IHF) map (HF missing part inferred solely from the LR image) and an external extracted HF (EHF) map. In particular, we infer the HF information based on both the LR image and similar HR references which is retrieved online. For the EHF map, we align the references with affine transformation and then in the aligned references, part of HF signals are extracted by the proposed DHN to compensate for the HF loss. Extensive experimental results demonstrate that our DHN achieves notably better performance than state-of-the-art SR methods.

##### Abstract (translated by Google)
当使用低分辨率（LR）图像预测高分辨率（HR）图像而不使用外部参考时，图像超分辨率（SR）方法将基本上导致丢失一些高频（HF）信息。为了解决这个问题，我们另外利用在线检索的数据来促进图像SR在一个统一的深层框架中。提出了一种新的双频高频恢复网络（DHN），该算法分为三个部分：一个LR图像，一个内部推断的HF（IHF）图谱（HF缺失部分仅由LR图像推断）和一个外部提取的HF （EHF）地图。具体而言，我们推断基于LR图像和在线检索的类似HR参考的HF信息。对于EHF映射，我们将参考与仿射变换对齐，然后在对齐的参考中，由提出的DHN提取一部分HF信号以补偿HF损失。广泛的实验结果表明，我们的DHN比最先进的SR方法具有更好的性能。

##### URL
[https://arxiv.org/abs/1701.05652](https://arxiv.org/abs/1701.05652)

##### PDF
[https://arxiv.org/pdf/1701.05652](https://arxiv.org/pdf/1701.05652)

