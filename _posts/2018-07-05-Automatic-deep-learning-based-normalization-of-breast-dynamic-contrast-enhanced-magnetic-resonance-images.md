---
layout: post
title: "Automatic deep learning-based normalization of breast dynamic contrast-enhanced magnetic resonance images"
date: 2018-07-05 18:56:14
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation Deep_Learning
author: Jun Zhang, Ashirbani Saha, Brian J. Soher, Maciej A. Mazurowski
mathjax: true
---

* content
{:toc}

##### Abstract
Objective: To develop an automatic image normalization algorithm for intensity correction of images from breast dynamic contrast-enhanced magnetic resonance imaging (DCE-MRI) acquired by different MRI scanners with various imaging parameters, using only image information. Methods: DCE-MR images of 460 subjects with breast cancer acquired by different scanners were used in this study. Each subject had one T1-weighted pre-contrast image and three T1-weighted post-contrast images available. Our normalization algorithm operated under the assumption that the same type of tissue in different patients should be represented by the same voxel value. We used four tissue/material types as the anchors for the normalization: 1) air, 2) fat tissue, 3) dense tissue, and 4) heart. The algorithm proceeded in the following two steps: First, a state-of-the-art deep learning-based algorithm was applied to perform tissue segmentation accurately and efficiently. Then, based on the segmentation results, a subject-specific piecewise linear mapping function was applied between the anchor points to normalize the same type of tissue in different patients into the same intensity ranges. We evaluated the algorithm with 300 subjects used for training and the rest used for testing. Results: The application of our algorithm to images with different scanning parameters resulted in highly improved consistency in pixel values and extracted radiomics features. Conclusion: The proposed image normalization strategy based on tissue segmentation can perform intensity correction fully automatically, without the knowledge of the scanner parameters. Significance: We have thoroughly tested our algorithm and showed that it successfully normalizes the intensity of DCE-MR images. We made our software publicly available for others to apply in their analyses.

##### Abstract (translated by Google)
目的：利用图像信息，开发一种自动图像归一化算法，用于不同MRI扫描仪采集的乳腺动态增强磁共振成像（DCE-MRI）图像强度校正。方法：采用不同扫描仪获得的460例乳腺癌患者的DCE-MR图像进行研究。每个受试者具有一个T1加权的对比前图像和三个T1加权的对比后图像。我们的归一化算法在假设不同患者中的相同类型的组织应由相同的体素值表示的情况下操作。我们使用四种组织/材料类型作为标准化的锚点：1）空气，2）脂肪组织，3）致密组织，和4）心脏。该算法按以下两个步骤进行：首先，应用最先进的基于深度学习的算法来准确有效地执行组织分割。然后，基于分割结果，在锚点之间应用特定于主题的分段线性映射函数，以将不同患者中的相同类型的组织标准化为相同的强度范围。我们用300个用于训练的受试者评估了该算法，其余用于测试。结果：将我们的算法应用于具有不同扫描参数的图像，导致像素值和提取的放射性组学特征的一致性大大提高。结论：基于组织分割的图像归一化策略可以完全自动地进行强度校正，而不需要了解扫描仪参数。意义：我们已经彻底测试了我们的算法，并证明它成功地将DCE-MR图像的强度归一化。我们公开我们的软件供其他人应用于他们的分析。

##### URL
[http://arxiv.org/abs/1807.02152](http://arxiv.org/abs/1807.02152)

##### PDF
[http://arxiv.org/pdf/1807.02152](http://arxiv.org/pdf/1807.02152)

