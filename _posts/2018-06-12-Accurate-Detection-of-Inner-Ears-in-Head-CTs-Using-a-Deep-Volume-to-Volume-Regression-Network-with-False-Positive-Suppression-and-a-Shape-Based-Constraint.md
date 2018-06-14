---
layout: post
title: "Accurate Detection of Inner Ears in Head CTs Using a Deep Volume-to-Volume Regression Network with False Positive Suppression and a Shape-Based Constraint"
date: 2018-06-12 19:19:00
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Detection Relation
author: Dongqing Zhang, Jianing Wang, Jack H. Noble, Benoit M. Dawant
mathjax: true
---

* content
{:toc}

##### Abstract
Cochlear implants (CIs) are neural prosthetics which are used to treat patients with hearing loss. CIs use an array of electrodes which are surgically inserted into the cochlea to stimulate the auditory nerve endings. After surgery, CIs need to be programmed. Studies have shown that the spatial relationship between the intra-cochlear anatomy and electrodes derived from medical images can guide CI programming and lead to significant improvement in hearing outcomes. However, clinical head CT images are usually obtained from scanners of different brands with different protocols. The field of view thus varies greatly and visual inspection is needed to document their content prior to applying algorithms for electrode localization and intra-cochlear anatomy segmentation. In this work, to determine the presence/absence of inner ears and to accurately localize them in head CTs, we use a volume-to-volume convolutional neural network which can be trained end-to-end to map a raw CT volume to probability maps which indicate inner ear positions. We incorporate a false positive suppression strategy in training and apply a shape-based constraint. We achieve a labeling accuracy of 98.59% and a localization error of 2.45mm. The localization error is significantly smaller than a random forest-based approach that has been proposed recently to perform the same task.

##### Abstract (translated by Google)
人工耳蜗（CI）是用于治疗听力丧失的神经假体。 CI使用手术插入耳蜗的电极阵列刺激听神经末梢。手术后，CI需要进行编程。研究表明，人工耳蜗内解剖结构与医学图像衍生的电极之间的空间关系可以指导CI编程，并可显着改善听力结果。然而，临床头部CT图像通常从具有不同协议的不同品牌的扫描仪获得。视野因此变化很大，并且在应用用于电极定位和耳蜗内解剖学分割的算法之前需要视觉检查来记录它们的内容。在这项工作中，为了确定是否存在内耳并将其准确定位在头部CT中，我们使用体积卷积神经网络，该网络可以进行端对端训练以将原始CT体积映射到概率指示内耳位置的地图。我们在训练中引入了假阳性抑制策略并应用了基于形状的约束。我们实现了98.59％的标签准确度和2.45mm的定位误差。本地化误差远远小于最近提出的基于随机森林的方法来执行相同的任务。

##### URL
[http://arxiv.org/abs/1806.04725](http://arxiv.org/abs/1806.04725)

##### PDF
[http://arxiv.org/pdf/1806.04725](http://arxiv.org/pdf/1806.04725)

