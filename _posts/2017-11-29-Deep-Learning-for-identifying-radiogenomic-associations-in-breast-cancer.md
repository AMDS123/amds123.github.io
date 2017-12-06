---
layout: post
title: 'Deep Learning for identifying radiogenomic associations in breast cancer'
date: 2017-11-29 20:41:05
categories: arXiv_CV
tags: arXiv_CV Review Deep_Learning
author: Zhe Zhu, Ehab Albadawy, Ashirbani Saha, Jun Zhang, Michael R. Harowicz, Maciej A. Mazurowski
---

* content
{:toc}

##### Abstract
Purpose: To determine whether deep learning models can distinguish between breast cancer molecular subtypes based on dynamic contrast-enhanced magnetic resonance imaging (DCE-MRI). Materials and methods: In this institutional review board-approved single-center study, we analyzed DCE-MR images of 270 patients at our institution. Lesions of interest were identified by radiologists. The task was to automatically determine whether the tumor is of the Luminal A subtype or of another subtype based on the MR image patches representing the tumor. Three different deep learning approaches were used to classify the tumor according to their molecular subtypes: learning from scratch where only tumor patches were used for training, transfer learning where networks pre-trained on natural images were fine-tuned using tumor patches, and off-the-shelf deep features where the features extracted by neural networks trained on natural images were used for classification with a support vector machine. Network architectures utilized in our experiments were GoogleNet, VGG, and CIFAR. We used 10-fold crossvalidation method for validation and area under the receiver operating characteristic (AUC) as the measure of performance. Results: The best AUC performance for distinguishing molecular subtypes was 0.65 (95% CI:[0.57,0.71]) and was achieved by the off-the-shelf deep features approach. The highest AUC performance for training from scratch was 0.58 (95% CI:[0.51,0.64]) and the best AUC performance for transfer learning was 0.60 (95% CI:[0.52,0.65]) respectively. For the off-the-shelf approach, the features extracted from the fully connected layer performed the best. Conclusion: Deep learning may play a role in discovering radiogenomic associations in breast cancer.

##### Abstract (translated by Google)
目的：通过动态对比增强磁共振成像（DCE-MRI）确定深度学习模型是否能区分乳腺癌分子亚型。材料和方法：在这个机构审查委员会批准的单中心研究中，我们分析了我们机构的270名患者的DCE-MR图像。感兴趣的病灶由放射科医师确定。任务是基于代表肿瘤的MR图像片自动确定肿瘤是否是Luminal A亚型或另一个亚型。三种不同的深度学习方法被用来根据其分子亚型对肿瘤进行分类：从零开始学习，只有肿瘤斑块被用于训练，转移学习，使用肿瘤斑块对自然图像预训练的网络进行微调，使用支持向量机对由自然图像训练的神经网络提取的特征进行分类。我们实验中使用的网络架构是GoogleNet，VGG和CIFAR。我们使用10倍交叉验证方法进行验证，并将受试者工作特征（AUC）下的面积作为性能指标。结果：用于区分分子亚型的最佳AUC性能为0.65（95％CI：[0.57,0.71]），并通过现成的深度特征方法获得。从零开始培训的AUC最高表现为0.58（95％CI：[0.51,0.64]），转移学习AUC的最佳表现为0.60（95％CI：[0.52,0.65]）。对于现成的方法，从完全连接层提取的特征表现最好。结论：深入的学习可能在发现乳腺癌的放射性基因组中起作用。

##### URL
[https://arxiv.org/abs/1711.11097](https://arxiv.org/abs/1711.11097)

