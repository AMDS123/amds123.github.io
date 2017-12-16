---
layout: post
title: "Automatic Emphysema Detection using Weakly Labeled HRCT Lung Images"
date: 2017-06-07 05:38:49
categories: arXiv_CV
tags: arXiv_CV Classification Detection Relation
author: Isabel Pino Peña, Veronika Cheplygina, Sofia Paschaloudi, Morten Vuust, Jesper Carl, Ulla Møller Weinreich, Lasse Riis Østergaard, Marleen de Bruijne
mathjax: true
---

* content
{:toc}

##### Abstract
A method for automatically quantifying emphysema regions using High-Resolution Computed Tomography (HRCT) scans of patients with chronic obstructive pulmonary disease (COPD) that does not require manually annotated scans for training is presented. HRCT scans of controls and of COPD patients with diverse disease severity are acquired at two different centers. Textural features from co-occurrence matrices and Gaussian filter banks are used to characterize the lung parenchyma in the scans. Two robust versions of multiple instance learning (MIL) classifiers, miSVM and MILES, are investigated. The classifiers are trained with the weak labels extracted from the forced expiratory volume in one minute (FEV$_1$) and diffusing capacity of the lungs for carbon monoxide (DLCO). At test time, the classifiers output a patient label indicating overall COPD diagnosis and local labels indicating the presence of emphysema. The classifier performance is compared with manual annotations by two radiologists, a classical density based method, and pulmonary function tests (PFTs). The miSVM classifier performed better than MILES on both patient and emphysema classification. The classifier has a stronger correlation with PFT than the density based method, the percentage of emphysema in the intersection of annotations from both radiologists, and the percentage of emphysema annotated by one of the radiologists. The correlation between the classifier and the PFT is only outperformed by the second radiologist. The method is therefore promising for facilitating assessment of emphysema and reducing inter-observer variability.

##### Abstract (translated by Google)
提出了一种使用高分辨率计算机断层扫描（HRCT）扫描对慢性阻塞性肺病（COPD）患者自动量化肺气肿区域的方法，该方法不需要手动注释扫描以进行训练。在两个不同的中心获得了具有不同疾病严重程度的对照和COPD患者的HRCT扫描。用共生矩阵和高斯滤波器库的纹理特征来表征扫描中的肺实质。研究了多个实例学习（MIL）分类器miSVM和MILES的两个强健版本。用一分钟内用力呼气量（FEV $ _1 $）和肺部一氧化碳扩散能力（DLCO）中提取的微弱标签对分类器进行训练。在测试时间，分类器输出指示总体COPD诊断的患者标签和指示存在肺气肿的本地标签。分类器的性能与两位放射科医师的手工注释（基于经典密度的方法）和肺功能测试（PFT）进行比较。 miSVM分类器在病人和肺气肿分类上均表现优于MILES。与基于密度的方法相比，分类器与PFT的相关性更强，放射科医生的注释交叉处的肺气肿百分比以及放射科医师注释的肺气肿百分比。分类器和PFT之间的相关性只有第二位放射科医师才能胜出。因此该方法有利于促进肺气肿的评估并减少观察者间的差异性。

##### URL
[https://arxiv.org/abs/1706.02051](https://arxiv.org/abs/1706.02051)

##### PDF
[https://arxiv.org/pdf/1706.02051](https://arxiv.org/pdf/1706.02051)

