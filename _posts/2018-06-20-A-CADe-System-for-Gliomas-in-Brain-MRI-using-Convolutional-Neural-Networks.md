---
layout: post
title: "A CADe System for Gliomas in Brain MRI using Convolutional Neural Networks"
date: 2018-06-20 07:30:38
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Classification Detection
author: Subhasis Banerjee, Sushmita Mitra, Anmol Sharma, B. Uma Shankar
mathjax: true
---

* content
{:toc}

##### Abstract
Inspired by the success of Convolutional Neural Networks (CNN), we develop a novel Computer Aided Detection (CADe) system using CNN for Glioblastoma Multiforme (GBM) detection and segmentation from multi channel MRI data. A two-stage approach first identifies the presence of GBM. This is followed by a GBM localization in each "abnormal" MR slice. As part of the CADe system, two CNN architectures viz. Classification CNN (C-CNN) and Detection CNN (D-CNN) are employed. The CADe system considers MRI data consisting of four sequences ($T_1$, $T_{1c},$ $T_2$, and $T_{2FLAIR}$) as input, and automatically generates the bounding boxes encompassing the tumor regions in each slice which is deemed abnormal. Experimental results demonstrate that the proposed CADe system, when used as a preliminary step before segmentation, can allow improved delineation of tumor region while reducing false positives arising in normal areas of the brain. The GrowCut method, employed for tumor segmentation, typically requires a foreground and background seed region for initialization. Here the algorithm is initialized with seeds automatically generated from the output of the proposed CADe system, thereby resulting in improved performance as compared to that using random seeds.

##### Abstract (translated by Google)
受到卷积神经网络（CNN）的成功启发，我们开发了一种新颖的计算机辅助检测（CADe）系统，使用CNN进行多通道MRI数据的胶质母细胞瘤（GBM）检测和分割。两阶段方法首先确定GBM的存在。随后在每个“异常”MR切片中进行GBM定位。作为CADe系统的一部分，两个CNN体系结构即：使用分类CNN（C-CNN）和检测CNN（D-CNN）。 CADe系统考虑由四个序列（$ T_1 $，$ T_ {1c}，$ $ T_2 $和$ T_ {2FLAIR} $）组成的MRI数据作为输入，并自动生成包含每个切片中肿瘤区域的边界框这被认为是不正常的。实验结果表明，所提出的CADe系统在用作分割前的初步步骤时，可以改善肿瘤区域的描绘，同时减少大脑正常区域出现的假阳性。用于肿瘤分割的GrowCut方法通常需要用于初始化的前景和背景种子区域。在这里，算法使用从提出的CADe系统的输出自动生成的种子进行初始化，从而与使用随机种子相比导致改进的性能。

##### URL
[http://arxiv.org/abs/1806.07589](http://arxiv.org/abs/1806.07589)

##### PDF
[http://arxiv.org/pdf/1806.07589](http://arxiv.org/pdf/1806.07589)

