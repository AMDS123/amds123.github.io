---
layout: post
title: "Bone marrow cells detection: A technique for the microscopic image analysis"
date: 2018-05-05 13:56:03
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification Detection Recognition
author: Haichao Cao, Hong Liu, Enmin Song
mathjax: true
---

* content
{:toc}

##### Abstract
In the detection of myeloproliferative, the number of cells in each type of bone marrow cells (BMC) is an important parameter for the evaluation. In this study, we propose a new counting method, which also consists of three modules including localization, segmentation and classification. The localization of BMC is achieved from a color transformation enhanced BMC sample image and stepwise averaging method (SAM). In the nucleus segmentation, both SAM and Otsu's method will be applied to obtain a weighted threshold for segmenting the patch into nucleus and non-nucleus. In the cytoplasm segmentation, a color weakening transformation, an improved region growing method and the K-Means algorithm are used. The connected cells with BMC will be separated by the marker-controlled watershed algorithm. The features will be extracted for the classification after the segmentation. In this study, the BMC are classified using the SVM, Random Forest, Artificial Neural Networks, Adaboost and Bayesian Networks into five classes including one outlier, namely, neutrophilic split granulocyte, neutrophilic stab granulocyte, metarubricyte, mature lymphocytes and the outlier (all other cells not listed). Our experimental results show that the best average recognition rate is 87.49% for the SVM.

##### Abstract (translated by Google)
在骨髓增生性疾病的检测中，每种类型的骨髓细胞（BMC）中的细胞数量是评估的重要参数。在这项研究中，我们提出了一种新的计数方法，它也包括三个模块，包括本地化，分割和分类。 BMC的本地化是通过色彩转换增强的BMC样本图像和逐步平均法（SAM）实现的。在细胞核分割中，将SAM和Otsu的方法应用于获得将贴片分割成核和非核的加权阈值。在细胞质分割中，使用弱色转换，改进的区域生长方法和K-Means算法。与BMC连接的细胞将通过标记控制的分水岭算法进行分离。分割后的特征将被提取用于分类。在这项研究中，BMC使用支持向量机，随机森林，人工神经网络，Adaboost和贝叶斯网络分为五类，包括一个异常点，即中性粒细胞分裂粒细胞，嗜中性粒细胞刺激粒细胞，metarubricyte，成熟淋巴细胞和异常值细胞未列出）。我们的实验结果表明SVM的最佳平均识别率为87.49％。

##### URL
[http://arxiv.org/abs/1805.02058](http://arxiv.org/abs/1805.02058)

##### PDF
[http://arxiv.org/pdf/1805.02058](http://arxiv.org/pdf/1805.02058)

