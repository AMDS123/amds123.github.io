---
layout: post
title: "An End-to-End Deep Learning Histochemical Scoring System for Breast Cancer Tissue Microarray"
date: 2018-01-19 04:04:50
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Deep_Learning Quantitative Relation
author: Jingxin Liu, Bolei Xu, Chi Zheng, Yuanhao Gong, Jon Garibaldi, Daniele Soria, Andew Green, Ian O. Ellis, Wenbin Zou, Guoping Qiu
mathjax: true
---

* content
{:toc}

##### Abstract
One of the methods for stratifying different molecular classes of breast cancer is the Nottingham Prognostic Index Plus (NPI+) which uses breast cancer relevant biomarkers to stain tumour tissues prepared on tissue microarray (TMA). To determine the molecular class of the tumour, pathologists will have to manually mark the nuclei activity biomarkers through a microscope and use a semi-quantitative assessment method to assign a histochemical score (H-Score) to each TMA core. Manually marking positively stained nuclei is a time consuming, imprecise and subjective process which will lead to inter-observer and intra-observer discrepancies. In this paper, we present an end-to-end deep learning system which directly predicts the H-Score automatically. Our system imitates the pathologists' decision process and uses one fully convolutional network (FCN) to extract all nuclei region (tumour and non-tumour), a second FCN to extract tumour nuclei region, and a multi-column convolutional neural network which takes the outputs of the first two FCNs and the stain intensity description image as input and acts as the high-level decision making mechanism to directly output the H-Score of the input TMA image. To the best of our knowledge, this is the first end-to-end system that takes a TMA image as input and directly outputs a clinical score. We will present experimental results which demonstrate that the H-Scores predicted by our model have very high and statistically significant correlation with experienced pathologists' scores and that the H-Score discrepancy between our algorithm and the pathologists is on par with the inter-subject discrepancy between the pathologists.

##### Abstract (translated by Google)
分层不同分子类型乳腺癌的方法之一是使用乳腺癌相关生物标志物对组织微阵列（TMA）上制备的肿瘤组织染色的Nottingham Prognostic Index Plus（NPI +）。为了确定肿瘤的分子类型，病理学家将不得不通过显微镜手动标记核活性生物标志物，并使用半定量评估方法将组织化学评分（H-Score）分配给每个TMA核心。手动标记阳性染色的细胞核是耗时，不精确和主观的过程，这将导致观察者间和观察者间的差异。在本文中，我们提出了一个端到端的深度学习系统，可以直接预测H-Score。我们的系统模仿病理学家的决策过程，使用一个完全卷积网络（FCN）提取所有细胞核区域（肿瘤和非肿瘤），第二个FCN提取肿瘤细胞核区域，以及多列卷积神经网络前两个FCN的输出和污点强度描述图像作为输入，并作为直接输出输入TMA图像的H-Score的高级决策机制。就我们所知，这是第一个将TMA图像作为输入并直接输出临床评分的端对端系统。我们将给出实验结果，证明我们的模型预测的H分数与经验丰富的病理学家的分数具有非常高的统计学显着相关性，并且我们的算法与病理学家之间的H分数差异与主体间差异病理学家之间。

##### URL
[http://arxiv.org/abs/1801.06288](http://arxiv.org/abs/1801.06288)

##### PDF
[http://arxiv.org/pdf/1801.06288](http://arxiv.org/pdf/1801.06288)

