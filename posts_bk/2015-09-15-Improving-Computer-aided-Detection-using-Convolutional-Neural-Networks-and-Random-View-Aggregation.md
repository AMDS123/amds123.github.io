---
layout: post
title: "Improving Computer-aided Detection using Convolutional Neural Networks and Random View Aggregation"
date: 2015-09-15 20:08:00
categories: arXiv_CV
tags: arXiv_CV GAN CNN Classification Detection
author: Holger R. Roth, Le Lu, Jiamin Liu, Jianhua Yao, Ari Seff, Kevin Cherry, Lauren Kim, Ronald M. Summers
mathjax: true
---

* content
{:toc}

##### Abstract
Automated computer-aided detection (CADe) in medical imaging has been an important tool in clinical practice and research. State-of-the-art methods often show high sensitivities but at the cost of high false-positives (FP) per patient rates. We design a two-tiered coarse-to-fine cascade framework that first operates a candidate generation system at sensitivities of $\sim$100% but at high FP levels. By leveraging existing CAD systems, coordinates of regions or volumes of interest (ROI or VOI) for lesion candidates are generated in this step and function as input for a second tier, which is our focus in this study. In this second stage, we generate $N$ 2D (two-dimensional) or 2.5D views via sampling through scale transformations, random translations and rotations with respect to each ROI's centroid coordinates. These random views are used to train deep convolutional neural network (ConvNet) classifiers. In testing, the trained ConvNets are employed to assign class (e.g., lesion, pathology) probabilities for a new set of $N$ random views that are then averaged at each ROI to compute a final per-candidate classification probability. This second tier behaves as a highly selective process to reject difficult false positives while preserving high sensitivities. The methods are evaluated on three different data sets with different numbers of patients: 59 patients for sclerotic metastases detection, 176 patients for lymph node detection, and 1,186 patients for colonic polyp detection. Experimental results show the ability of ConvNets to generalize well to different medical imaging CADe applications and scale elegantly to various data sets. Our proposed methods improve CADe performance markedly in all cases. CADe sensitivities improved from 57% to 70%, from 43% to 77% and from 58% to 75% at 3 FPs per patient for sclerotic metastases, lymph nodes and colonic polyps, respectively.

##### Abstract (translated by Google)
医学影像中的自动计算机辅助检测（CADe）一直是临床实践和研究中的重要工具。最先进的方法通常表现出高度的敏感性，但是以每个患者的高假阳性（FP）为代价。我们设计了一个两级的从粗到精的级联框架，首先运行一个候选代系统，灵敏度为$ 100％，但是FP级别高。通过利用现有的CAD系统，在这个步骤中生成病灶候选区域或感兴趣区域（ROI或VOI）的坐标，并作为第二层的输入，这是本研究的焦点。在第二阶段，我们通过对每个ROI的质心坐标进行缩放变换，随机平移和旋转的采样，生成$ N $ 2D（二维）或2.5D视图。这些随机视图用于训练深度卷积神经网络（ConvNet）分类器。在测试中，训练的ConvNets被用来为一组新的$ N $随机视图分配类别（例如病变，病理学）概率，然后在每个ROI对这些视图进行平均，以计算最终的每个候选分类概率。这第二层行为是一个高度选择性的过程，以拒绝困难的误报，同时保持高敏感性。方法评估三个不同的数据集与不同数量的患者：硬化转移检测59例，淋巴结检测176例，结肠息肉检测1,186例。实验结果表明，ConvNets能够很好地推广到不同的医学影像CADe应用，并优雅地扩展到各种数据集。我们提出的方法在所有情况下显着提高CADe性能。对于硬化性转移瘤，淋巴结和结肠息肉，每个患者3个FP的CADe敏感性分别从57％增加到70％，从43％增加到77％，从58％增加到75％。

##### URL
[https://arxiv.org/abs/1505.03046](https://arxiv.org/abs/1505.03046)

##### PDF
[https://arxiv.org/pdf/1505.03046](https://arxiv.org/pdf/1505.03046)

