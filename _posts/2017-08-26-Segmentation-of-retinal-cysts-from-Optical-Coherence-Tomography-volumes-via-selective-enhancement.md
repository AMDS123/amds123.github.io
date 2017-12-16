---
layout: post
title: "Segmentation of retinal cysts from Optical Coherence Tomography volumes via selective enhancement"
date: 2017-08-26 10:25:43
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Detection
author: Karthik Gopinath, Jayanthi Sivaswamy
mathjax: true
---

* content
{:toc}

##### Abstract
Automated and accurate segmentation of cystoid structures in Optical Coherence Tomography (OCT) is of interest in the early detection of retinal diseases. It is, however, a challenging task. We propose a novel method for localizing cysts in 3D OCT volumes. The proposed work is biologically inspired and based on selective enhancement of the cysts, by inducing motion to a given OCT slice. A Convolutional Neural Network (CNN) is designed to learn a mapping function that combines the result of multiple such motions to produce a probability map for cyst locations in a given slice. The final segmentation of cysts is obtained via simple clustering of the detected cyst locations. The proposed method is evaluated on two public datasets and one private dataset. The public datasets include the one released for the OPTIMA Cyst segmentation challenge (OCSC) in MICCAI 2015 and the DME dataset. After training on the OCSC train set, the method achieves a mean Dice Coefficient (DC) of 0.71 on the OCSC test set. The robustness of the algorithm was examined by cross-validation on the DME and AEI (private) datasets and a mean DC values obtained were 0.69 and 0.79, respectively. Overall, the proposed system outperforms all benchmarks. These results underscore the strengths of the proposed method in handling variations in both data acquisition protocols and scanners.

##### Abstract (translated by Google)
光学相干层析成像（OCT）中的囊状结构的自动准确分割对视网膜疾病的早期检测具有重要意义。然而，这是一项具有挑战性的任务。我们提出了一种新的方法来定位在三维OCT卷囊肿。拟议的工作是生物启发和基于囊肿的选择性增强，通过诱导运动到给定的OCT切片。卷积神经网络（CNN）被设计用于学习映射函数，该函数将多个这样的运动的结果组合起来，以产生给定切片中的囊肿位置的概率图。囊肿的最终分割是通过对检测到的囊肿位置进行简单聚类而获得的。所提出的方法在两个公共数据集和一个私有数据集上进行评估。公开数据集包括2015年MICCAI中的OPTIMA囊肿分割挑战（OCSC）和DME数据集。在OCSC训练集训练后，该方法在OCSC测试集上达到0.71的平均Dice系数（DC）。通过在DME和AEI（私有）数据集上进行交叉验证来检验算法的稳健性，并且获得的平均DC值分别为0.69和0.79。总的来说，建议的系统胜过所有的基准。这些结果突出了所提出的方法在处理数据采集协议和扫描仪中的变化方面的优势。

##### URL
[https://arxiv.org/abs/1708.06197](https://arxiv.org/abs/1708.06197)

##### PDF
[https://arxiv.org/pdf/1708.06197](https://arxiv.org/pdf/1708.06197)

