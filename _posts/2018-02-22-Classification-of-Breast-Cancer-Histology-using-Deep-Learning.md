---
layout: post
title: "Classification of Breast Cancer Histology using Deep Learning"
date: 2018-02-22 14:56:38
categories: arXiv_CV
tags: arXiv_CV CNN Classification Deep_Learning
author: Aditya Golatkar, Deepak Anand, Amit Sethi
mathjax: true
---

* content
{:toc}

##### Abstract
Breast Cancer is a major cause of death worldwide among women. Hematoxylin and Eosin (H&amp;E) stained breast tissue samples from biopsies are observed under microscopes for the primary diagnosis of breast cancer. In this paper, we propose a deep learning-based method for classification of H&amp;E stained breast tissue images released for BACH challenge 2018 by fine-tuning Inception-v3 convolutional neural network (CNN) proposed by Szegedy et al. These images are to be classified into four classes namely, i) normal tissue, ii) benign tumor, iii) in-situ carcinoma and iv) invasive carcinoma. Our strategy is to extract patches based on nuclei density instead of random or grid sampling, along with rejection of patches that are not rich in nuclei (non-epithelial) regions for training and testing. Every patch (nuclei-dense region) in an image is classified in one of the four above mentioned categories. The class of the entire image is determined using majority voting over the nuclear classes. We obtained an average four class accuracy of 85% and an average two class (non-cancer vs. carcinoma) accuracy of 93%, which improves upon a previous benchmark by Araujo et al.

##### Abstract (translated by Google)
乳腺癌是全球女性死亡的主要原因。在显微镜下观察来自活组织检查的苏木精和曙红（H＆amp; E）染色的乳房组织样品用于乳腺癌的主要诊断。在本文中，我们提出了一种基于深度学习的方法，用于分类H＆amp; E染色乳房组织图像，通过微调Szegedy等人提出的Inception-v3卷积神经网络（CNN）为BACH挑战2018发布。这些图像被分为四类，即i）正常组织，ii）良性肿瘤，iii）原位癌和iv）浸润性癌。我们的策略是根据核密度而不是随机或网格采样来提取贴片，同时拒绝不具有核（非上皮）区域的补丁以进行训练和测试。图像中的每个斑块（核心密集的区域）都被归类为上述四个类别之一。整个图像的类别是通过对核类进行多数投票来确定的。我们获得了平均四类85％的准确性和93％的平均两类（非癌症与癌）准确性，这改善了Araujo等人以前的基准。

##### URL
[http://arxiv.org/abs/1802.08080](http://arxiv.org/abs/1802.08080)

##### PDF
[http://arxiv.org/pdf/1802.08080](http://arxiv.org/pdf/1802.08080)

