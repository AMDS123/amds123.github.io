---
layout: post
title: "Label-driven weakly-supervised learning for multimodal deformable image registration"
date: 2017-11-05 22:01:57
categories: arXiv_CV
tags: arXiv_CV GAN CNN Inference
author: Yipeng Hu, Marc Modat, Eli Gibson, Nooshin Ghavami, Ester Bonmati, Caroline M. Moore, Mark Emberton, J. Alison Noble, Dean C. Barratt, Tom Vercauteren
mathjax: true
---

* content
{:toc}

##### Abstract
Spatially aligning medical images from different modalities remains a challenging task, especially for intraoperative applications that require fast and robust algorithms. We propose a weakly-supervised, label-driven formulation for learning 3D voxel correspondence from higher-level label correspondence, thereby bypassing classical intensity-based image similarity measures. During training, a convolutional neural network is optimised by outputting a dense displacement field (DDF) that warps a set of available anatomical labels from the moving image to match their corresponding counterparts in the fixed image. These label pairs, including solid organs, ducts, vessels, point landmarks and other ad hoc structures, are only required at training time and can be spatially aligned by minimising a cross-entropy function of the warped moving label and the fixed label. During inference, the trained network takes a new image pair to predict an optimal DDF, resulting in a fully-automatic, label-free, real-time and deformable registration. For interventional applications where large global transformation prevails, we also propose a neural network architecture to jointly optimise the global- and local displacements. Experiment results are presented based on cross-validating registrations of 111 pairs of T2-weighted magnetic resonance images and 3D transrectal ultrasound images from prostate cancer patients with a total of over 4000 anatomical labels, yielding a median target registration error of 4.2 mm on landmark centroids and a median Dice of 0.88 on prostate glands.

##### Abstract (translated by Google)
空间对齐来自不同模态的医学图像仍然是一项具有挑战性的任务，特别是对于需要快速和稳健算法的术中应用。我们提出了一种弱监督的标签驱动公式，用于从较高级别的标签对应关系中学习三维体素对应，从而绕过经典的基于强度的图像相似性度量。在训练期间，卷积神经网络通过输出稠密位移场（DDF）来优化，所述稠密位移场从运动图像扭曲一组可用的解剖标签以匹配固定图像中的对应对应物。这些标签对，包括实体器官，管道，容器，点标志和其他ad hoc结构，只需要在训练时间，并可以通过最小化翘曲移动标签和固定标签的交叉熵函数在空间上对齐。在推断过程中，训练好的网络采用新的图像对来预测最佳的DDF，从而实现全自动，无标签，实时和可变形的配准。对于大规模全球变革盛行的介入应用，我们还提出了一个神经网络结构来共同优化全球和当地的位移。实验结果的基础上交叉验证注册111对T2加权磁共振图像和三维经直肠超声图像来自前列腺癌患者总共超过4000个解剖标签，产生中位数目标配准误差4.2毫米的地标中心和0.88的中位数骰子在前列腺。

##### URL
[https://arxiv.org/abs/1711.01666](https://arxiv.org/abs/1711.01666)

##### PDF
[https://arxiv.org/pdf/1711.01666](https://arxiv.org/pdf/1711.01666)

