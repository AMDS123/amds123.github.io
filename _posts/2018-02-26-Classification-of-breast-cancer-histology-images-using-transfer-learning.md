---
layout: post
title: "Classification of breast cancer histology images using transfer learning"
date: 2018-02-26 16:10:40
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Transfer_Learning Classification Detection
author: Sulaiman Vesal, Nishant Ravikumar, AmirAbbas Davari, Stephan Ellmann, Andreas Maier
mathjax: true
---

* content
{:toc}

##### Abstract
Breast cancer is one of the leading causes of mortality in women. Early detection and treatment are imperative for improving survival rates, which have steadily increased in recent years as a result of more sophisticated computer-aided-diagnosis (CAD) systems. A critical component of breast cancer diagnosis relies on histopathology, a laborious and highly subjective process. Consequently, CAD systems are essential to reduce inter-rater variability and supplement the analyses conducted by specialists. In this paper, a transfer-learning based approach is proposed, for the task of breast histology image classification into four tissue sub-types, namely, normal, benign, \textit{in situ} carcinoma and invasive carcinoma. The histology images, provided as part of the BACH 2018 grand challenge, were first normalized to correct for color variations resulting from inconsistencies during slide preparation. Subsequently, image patches were extracted and used to fine-tune Google`s Inception-V3 and ResNet50 convolutional neural networks (CNNs), both pre-trained on the ImageNet database, enabling them to learn domain-specific features, necessary to classify the histology images. The ResNet50 network (based on residual learning) achieved a test classification accuracy of 97.50% for four classes, outperforming the Inception-V3 network which achieved an accuracy of 91.25%.

##### Abstract (translated by Google)
乳腺癌是女性死亡的主要原因之一。早期发现和治疗对于提高存活率是必不可少的，近年来，由于更复杂的计算机辅助诊断（CAD）系统，存活率稳步增加。乳腺癌诊断的一个关键组成部分依赖于组织病理学，这是一种费力且高度主观的过程。因此，CAD系统对减少评估者间的变异性和补充专家的分析至关重要。在本文中，提出了一种基于转移学习的方法，用于乳腺组织学图像分类为四种组织亚型的任务，即正常，良性，原位癌和浸润癌。作为BACH 2018盛大挑战的一部分提供的组织学图像首先被归一化，以校正由于载玻片制备期间的不一致而导致的颜色变化。随后，图像补丁被提取并用于微调Google的Inception-V3和ResNet50卷积神经网络（CNN），这两种网络都是在ImageNet数据库上预先训练好的，使他们能够学习特定领域的特征，这是组织学分类所必需的图片。 ResNet50网络（基于残差学习）为四类提供了97.50％的测试分类准确率，其表现优于Inception-V3网络，准确性达到了91.25％。

##### URL
[http://arxiv.org/abs/1802.09424](http://arxiv.org/abs/1802.09424)

##### PDF
[http://arxiv.org/pdf/1802.09424](http://arxiv.org/pdf/1802.09424)

