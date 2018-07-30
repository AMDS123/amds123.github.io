---
layout: post
title: "Improving High Resolution Histology Image Classification with Deep Spatial Fusion Network"
date: 2018-07-27 12:34:34
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification Prediction Relation
author: Yongxiang Huang, Albert Chi-shing Chung
mathjax: true
---

* content
{:toc}

##### Abstract
Histology imaging is an essential diagnosis method to finalize the grade and stage of cancer of different tissues, especially for breast cancer diagnosis. Specialists often disagree on the final diagnosis on biopsy tissue due to the complex morphological variety. Although convolutional neural networks (CNN) have advantages in extracting discriminative features in image classification, directly training a CNN on high resolution histology images is computationally infeasible currently. Besides, inconsistent discriminative features often distribute over the whole histology image, which incurs challenges in patch-based CNN classification method. In this paper, we propose a novel architecture for automatic classification of high resolution histology images. First, an adapted residual network is employed to explore hierarchical features without attenuation. Second, we develop a robust deep fusion network to utilize the spatial relationship between patches and learn to correct the prediction bias generated from inconsistent discriminative feature distribution. The proposed method is evaluated using 10-fold cross-validation on 400 high resolution breast histology images with balanced labels and reports 95% accuracy on 4-class classification and 98.5% accuracy, 99.6% AUC on 2-class classification (carcinoma and non-carcinoma), which substantially outperforms previous methods and close to pathologist performance.

##### Abstract (translated by Google)
组织学成像是确定不同组织的癌症等级和阶段，尤其是乳腺癌诊断的必要诊断方法。由于复杂的形态变化，专家经常不同意活检组织的最终诊断。尽管卷积神经网络（CNN）在提取图像分类中的判别特征方面具有优势，但是目前在高分辨率组织学图像上直接训练CNN在计算上是不可行的。此外，不一致的判别特征通常分布在整个组织学图像上，这在基于补丁的CNN分类方法中引起挑战。在本文中，我们提出了一种新的高分辨率组织学图像自动分类架构。首先，采用适应的剩余网络来探索没有衰减的分层特征。其次，我们开发了一个强大的深度融合网络，以利用补丁之间的空间关系，并学习纠正由不一致的判别特征分布产生的预测偏差。所提出的方法使用具有平衡标签的400个高分辨率乳房组织学图像的10倍交叉验证来评估，并且报告4级分类的准确率为95％，准确度为98.5％，A级分类为99.6％AUC（癌和非癌症），基本上优于以前的方法，接近病理学家的表现。

##### URL
[http://arxiv.org/abs/1807.10552](http://arxiv.org/abs/1807.10552)

##### PDF
[http://arxiv.org/pdf/1807.10552](http://arxiv.org/pdf/1807.10552)

