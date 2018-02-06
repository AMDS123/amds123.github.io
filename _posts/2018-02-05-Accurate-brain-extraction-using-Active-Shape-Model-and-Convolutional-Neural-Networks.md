---
layout: post
title: "Accurate brain extraction using Active Shape Model and Convolutional Neural Networks"
date: 2018-02-05 05:01:25
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation CNN
author: Nguyen Ho Minh Duy, Nguyen Manh Duy, Mai Thanh Nhat Truong, Pham The Bao, Nguyen Thanh Binh
mathjax: true
---

* content
{:toc}

##### Abstract
Brain extraction or skull stripping is a fundamental procedure in most of neuroimaging processing systems. The performance of this procedure has had a critical impact on the success of neuroimaging analysis. After several years of research and development, brain extraction still remains a challenging problem. In this paper, we propose an effective method for skull stripping in Magnetic Resonance Imaging (MRI) scans named ASM-CNN. Our system is a combination of Active Shape Model (ASM) and Convolutional Neural Network (CNN), taking full advantage of these two methods to achieve remarkable results. Instead of working with 3D structures, we process 2D image sequences in sagittal plane. First, we divide images into different groups such that, in each group, the shapes and structures of brain boundaries have similar appearances. This allows developing precise algorithms for each group in order to produce high performance segmentation results. Second, a modified version of ASM is used to detect the brain boundary in images by utilizing prior knowledge of each group. Finally, CNN and the post-processing methods such as Conditional Random Field, Gaussian Process and some special rules are applied to refine segmentation contour produced by ASM. We compared ASM-CNN with the latest version of five state-of-the-art, publicly available methods, namely BET, BSE, 3DSS, ROBEX and BEAST. The evaluation was carried out by using three public datasets IBSR, LPBA and OASIS. The experimental results show that the proposed method outperforms five states-of-the-art algorithms, surpassing all the other methods by a significant margin in all experiments.

##### Abstract (translated by Google)
脑提取或颅骨剥离是大多数神经影像处理系统的基本程序。这个过程的表现对神经影像学分析的成功有着重要的影响。经过几年的研究和发展，脑部提取仍然是一个具有挑战性的问题。在本文中，我们提出了一种有效的磁共振成像（MRI）扫描头骨剥离方法，称为ASM-CNN。我们的系统是主动形状模型（ASM）和卷积神经网络（CNN）的组合，充分利用这两种方法取得显着成果。我们没有使用三维结构，而是在矢状面上处理二维图像序列。首先，我们将图像划分为不同的组，使得在每组中，脑边界的形状和结构具有相似的外观。这允许为每个组开发精确的算法，以产生高性能的分割结果。其次，使用ASM的修改版本通过利用每个组的先验知识来检测图像中的脑边界。最后，将CNN和条件随机场，高斯过程等后处理方法以及一些特殊规则应用于细化ASM生成的分割轮廓。我们比较了ASM-CNN和最新版本的五种最先进的公开可用的方法，即BET，BSE，3DSS，ROBEX和BEAST。评估是通过使用三个公共数据集IBSR，LPBA和OASIS进行的。实验结果表明，所提出的方法胜过五个最先进的算法，在所有的实验中都超过了所有其他的方法。

##### URL
[http://arxiv.org/abs/1802.01268](http://arxiv.org/abs/1802.01268)

##### PDF
[http://arxiv.org/pdf/1802.01268](http://arxiv.org/pdf/1802.01268)

