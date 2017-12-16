---
layout: post
title: "On the use of convolutional neural networks for robust classification of multiple fingerprint captures"
date: 2017-05-15 09:17:35
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Classification
author: Daniel Peralta, Isaac Triguero, Salvador García, Yvan Saeys, Jose M. Benitez, Francisco Herrera
mathjax: true
---

* content
{:toc}

##### Abstract
Fingerprint classification is one of the most common approaches to accelerate the identification in large databases of fingerprints. Fingerprints are grouped into disjoint classes, so that an input fingerprint is compared only with those belonging to the predicted class, reducing the penetration rate of the search. The classification procedure usually starts by the extraction of features from the fingerprint image, frequently based on visual characteristics. In this work, we propose an approach to fingerprint classification using convolutional neural networks, which avoid the necessity of an explicit feature extraction process by incorporating the image processing within the training of the classifier. Furthermore, such an approach is able to predict a class even for low-quality fingerprints that are rejected by commonly used algorithms, such as FingerCode. The study gives special importance to the robustness of the classification for different impressions of the same fingerprint, aiming to minimize the penetration in the database. In our experiments, convolutional neural networks yielded better accuracy and penetration rate than state-of-the-art classifiers based on explicit feature extraction. The tested networks also improved on the runtime, as a result of the joint optimization of both feature extraction and classification.

##### Abstract (translated by Google)
指纹分类是在大型数据库中加速识别指纹的最常用方法之一。指纹被分组为不相交的类别，使得输入指纹仅与属于预测类别的指纹进行比较，从而降低搜索的渗透率。分类过程通常从指纹图像中提取特征开始，通常基于视觉特征。在这项工作中，我们提出了一种使用卷积神经网络进行指纹分类的方法，通过将图像处理结合到分类器的训练中，避免了显式特征提取过程的必要性。此外，即使对于被诸如FingerCode之类的常用算法所拒绝的低质量指纹，这种方法也能够预测类别。该研究对同一指纹的不同印象的分类的鲁棒性给予了特别的重视，旨在最小化数据库中的渗透。在我们的实验中，卷积神经网络比基于显式特征提取的现有技术分类器具有更好的准确性和穿透率。由于特征提取和分类的联合优化，所测试的网络在运行时间上也得到了改善。

##### URL
[https://arxiv.org/abs/1703.07270](https://arxiv.org/abs/1703.07270)

##### PDF
[https://arxiv.org/pdf/1703.07270](https://arxiv.org/pdf/1703.07270)

