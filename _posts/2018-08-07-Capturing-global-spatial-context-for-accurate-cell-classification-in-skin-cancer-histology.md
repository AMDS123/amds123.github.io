---
layout: post
title: "Capturing global spatial context for accurate cell classification in skin cancer histology"
date: 2018-08-07 13:31:09
categories: arXiv_CV
tags: arXiv_CV Knowledge Face Classification Deep_Learning
author: Konstantinos Zormpas-Petridis, Henrik Failmezger, Ioannis Roxanis, Matthew Blackledge, Yann Jamin, Yinyin Yuan
mathjax: true
---

* content
{:toc}

##### Abstract
The spectacular response observed in clinical trials of immunotherapy in patients with previously uncurable Melanoma, a highly aggressive form of skin cancer, calls for a better understanding of the cancer-immune interface. Computational pathology provides a unique opportunity to spatially dissect such interface on digitised pathological slides. Accurate cellular classification is a key to ensure meaningful results, but is often challenging even with state-of-art machine learning and deep learning methods. 
 We propose a hierarchical framework, which mirrors the way pathologists perceive tumour architecture and define tumour heterogeneity to improve cell classification methods that rely solely on cell nuclei morphology. The SLIC superpixel algorithm was used to segment and classify tumour regions in low resolution H&amp;E-stained histological images of melanoma skin cancer to provide a global context. Classification of superpixels into tumour, stroma, epidermis and lumen/white space, yielded a 97.7% training set accuracy and 95.7% testing set accuracy in 58 whole-tumour images of the TCGA melanoma dataset. The superpixel classification was projected down to high resolution images to enhance the performance of a single cell classifier, based on cell nuclear morphological features, and resulted in increasing its accuracy from 86.4% to 91.6%. Furthermore, a voting scheme was proposed to use global context as biological a priori knowledge, pushing the accuracy further to 92.8%. 
 This study demonstrates how using the global spatial context can accurately characterise the tumour microenvironment and allow us to extend significantly beyond single-cell morphological classification.

##### Abstract (translated by Google)
在以前无法治愈的黑色素瘤（一种高度侵袭性的皮肤癌）患者的免疫治疗临床试验中观察到的惊人反应要求更好地了解癌症免疫界面。计算病理学为在数字化病理载玻片上空间剖析这种界面提供了独特的机会。准确的细胞分类是确保有意义结果的关键，但即使使用最先进的机器学习和深度学习方法，也经常具有挑战性。
 我们提出了一种分层框架，它反映了病理学家对肿瘤结构的看法，并定义了肿瘤的异质性，以改进仅依赖于细胞核形态的细胞分类方法。 SLIC超像素算法用于在黑素瘤皮肤癌的低分辨率H＆amp; E染色的组织学图像中分割和分类肿瘤区域，以提供全局背景。将超像素分类为肿瘤，基质，表皮和管腔/白色空间，在TCGA黑素瘤数据集的58个全肿瘤图像中产生97.7％的训练集准确度和95.7％的测试集准确度。基于细胞核形态特征，超像素分类被投射到高分辨率图像以增强单细胞分类器的性能，并且导致其准确度从86.4％增加到91.6％。此外，提出了一种投票方案，将全球背景作为生物学先验知识，将准确性进一步提高到92.8％。
 这项研究表明，使用全球空间背景可以准确地表征肿瘤微环境，并使我们能够显着超越单细胞形态分类。

##### URL
[http://arxiv.org/abs/1808.02355](http://arxiv.org/abs/1808.02355)

##### PDF
[http://arxiv.org/pdf/1808.02355](http://arxiv.org/pdf/1808.02355)

