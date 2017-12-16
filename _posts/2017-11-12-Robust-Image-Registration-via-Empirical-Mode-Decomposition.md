---
layout: post
title: "Robust Image Registration via Empirical Mode Decomposition"
date: 2017-11-12 07:45:29
categories: arXiv_CV
tags: arXiv_CV
author: Reza Abbasi-Asl, Aboozar Ghaffari, Emad Fatemizadeh
mathjax: true
---

* content
{:toc}

##### Abstract
Spatially varying intensity noise is a common source of distortion in images. Bias field noise is one example of such distortion that is often present in the magnetic resonance (MR) images. In this paper, we first show that empirical mode decomposition (EMD) can considerably reduce the bias field noise in the MR images. Then, we propose two hierarchical multi-resolution EMD-based algorithms for robust registration of images in the presence of spatially varying noise. One algorithm (LR-EMD) is based on registering EMD feature-maps of both floating and reference images in various resolution levels. In the second algorithm (AFR-EMD), we first extract an average feature-map based on EMD from both floating and reference images. Then, we use a simple hierarchical multi-resolution algorithm based on downsampling to register the average feature-maps. Both algorithms achieve lower error rate and higher convergence percentage compared to the intensity-based hierarchical registration. Specifically, using mutual information as the similarity measure, AFR-EMD achieves 42% lower error rate in intensity and 52% lower error rate in transformation compared to intensity-based hierarchical registration. For LR-EMD, the error rate is 32% lower for the intensity and 41% lower for the transformation.

##### Abstract (translated by Google)
空间变化的强度噪声是图像失真的常见原因。偏磁场噪声是磁共振（MR）图像中经常出现的这种失真的一个例子。在本文中，我们首先表明，经验模式分解（EMD）可以显着降低MR图像中的偏置场噪声。然后，我们提出了两种分层多分辨率EMD算法，用于在存在空间变化噪声的情况下对图像进行鲁棒配准。一种算法（LR-EMD）基于在各种分辨率级别注册浮动图像和参考图像的EMD特征图。在第二种算法（AFR-EMD）中，我们首先从浮动和参考图像中提取基于EMD的平均特征图。然后，我们使用一个简单的分层多分辨率算法基于下采样登记平均特征映射。与基于强度的分层配准相比，这两种算法都可以实现更低的错误率和更高的收敛率。具体而言，使用互信息作为相似性度量，与基于强度的分级登记相比，AFR-EMD在强度上的错误率降低了42％，转换中的错误率降低了52％。对于LR-EMD，强度的错误率低32％，转换的错误率低41％。

##### URL
[https://arxiv.org/abs/1711.04247](https://arxiv.org/abs/1711.04247)

##### PDF
[https://arxiv.org/pdf/1711.04247](https://arxiv.org/pdf/1711.04247)

