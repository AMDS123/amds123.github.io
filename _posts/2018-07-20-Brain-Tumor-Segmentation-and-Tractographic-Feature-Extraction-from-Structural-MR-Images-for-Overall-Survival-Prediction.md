---
layout: post
title: "Brain Tumor Segmentation and Tractographic Feature Extraction from Structural MR Images for Overall Survival Prediction"
date: 2018-07-20 07:10:24
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification Prediction
author: Po-Yu Kao, Thuyen Ngo, Angela Zhang, Jefferson Chen, B.S. Manjunath
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces a novel methodology to integrate human brain connectomics and parcellation for tumor segmentation and survival prediction. For segmentation, we utilize an existing brain parcellation atlas in the MNI152 1mm space and map the parcellation to each individual subject data. We leverage current state-of-the-art deep networks together with hard negative mining to achieve the final voxel level classification. This method achieves mean Dice scores of 0.904, 0.785 and 0.805 on segmentation of the whole tumor, tumor core and enhancing tumor, respectively. For survival prediction, we present a new method for combining features from connectomics data, brain parcellation, and the segmented brain tumor. Since the BraTS dataset does not include diffusion tensor imaging data for computing tractography, we use the average connectome information from the Human Connectome Project and map each subject brain volume onto this common connectome space. From this, we compute tractographic features that describe potential disruptions due to the brain tumor. These features are then used to predict the overall survival time. The proposed tractographic features achieve an average accuracy of 69% on training data and 50% on validation data.

##### Abstract (translated by Google)
本文介绍了一种将人脑连接组学与分割相结合的新方法，用于肿瘤分割和生存预测。对于分割，我们利用MNI152 1mm空间中的现有脑分割图谱并将分割图映射到每个单独的主题数据。我们利用当前最先进的深度网络和硬负挖掘来实现最终的体素级别分类。该方法分别对整个肿瘤，肿瘤核心和增强肿瘤的分割均达到0.904,0.785和0.805的平均Dice评分。对于生存预测，我们提出了一种结合连通组学数据，脑分割和分割脑肿瘤特征的新方法。由于BraTS数据集不包括用于计算纤维束成像的扩散张量成像数据，我们使用来自Human Connectome Project的平均连接组信息，并将每个主题脑容量映射到这个共同的连接组空间。由此，我们计算描述由脑肿瘤引起的潜在破坏的特征描述。然后使用这些特征来预测总体存活时间。建议的纤维束成像特征对训练数据的平均准确率为69％，对验证数据的平均准确率为50％。

##### URL
[http://arxiv.org/abs/1807.07716](http://arxiv.org/abs/1807.07716)

##### PDF
[http://arxiv.org/pdf/1807.07716](http://arxiv.org/pdf/1807.07716)

