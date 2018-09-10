---
layout: post
title: "Predicting Lung Nodule Malignancies by Combining Deep Convolutional Neural Network and Handcrafted Features"
date: 2018-09-07 07:43:17
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Shulong Li, Panpan Xu, Bin Li, Liyuan Chen, Zhiguo Zhou, Hongxia Hao, Yingying Duan, Michael Folkert, Jianhua Ma, Steve Jiang, Jing Wang
mathjax: true
---

* content
{:toc}

##### Abstract
To predict lung nodule malignancy with a high sensitivity and specificity, we propose a fusion algorithm that combines handcrafted features (HF) into the features learned at the output layer of a 3D deep convolutional neural network (CNN). First, we extracted twenty-nine handcrafted features, including nine intensity features, eight geometric features, and twelve texture features based on grey-level co-occurrence matrix (GLCM) averaged from thirteen directions. We then trained 3D CNNs modified from three state-of-the-art 2D CNN architectures (AlexNet, VGG-16 Net and Multi-crop Net) to extract the CNN features learned at the output layer. For each 3D CNN, the CNN features combined with the 29 handcrafted features were used as the input for the support vector machine (SVM) coupled with the sequential forward feature selection (SFS) method to select the optimal feature subset and construct the classifiers. The fusion algorithm takes full advantage of the handcrafted features and the highest level CNN features learned at the output layer. It can overcome the disadvantage of the handcrafted features that may not fully reflect the unique characteristics of a particular lesion by combining the intrinsic CNN features. Meanwhile, it also alleviates the requirement of a large scale annotated dataset for the CNNs based on the complementary of handcrafted features. The patient cohort includes 431 malignant nodules and 795 benign nodules extracted from the LIDC/IDRI database. For each investigated CNN architecture, the proposed fusion algorithm achieved the highest AUC, accuracy, sensitivity, and specificity scores among all competitive classification models.

##### Abstract (translated by Google)
为了以高灵敏度和特异性预测肺结节恶性肿瘤，我们提出了一种融合算法，该算法将手工特征（HF）结合到在3D深度卷积神经网络（CNN）的输出层学习的特征中。首先，我们提取了29个手工制作的特征，包括9个强度特征，8个几何特征和12个基于从13个方向平均的灰度共生矩阵（GLCM）的纹理特征。然后，我们训练了从三种最先进的2D CNN架构（AlexNet，VGG-16 Net和Multi-crop Net）修改的3D CNN，以提取在输出层学习的CNN特征。对于每个3D CNN，将CNN特征与29个手工制作的特征组合用作支持向量机（SVM）的输入，其与顺序前向特征选择（SFS）方法相结合以选择最佳特征子集并构造分类器。融合算法充分利用了手工制作的功能和在输出层学到的最高级CNN功能。它可以通过组合内在CNN特征来克服可能无法完全反映特定病变的独特特征的手工特征的缺点。同时，它还减轻了基于手工特征互补的CNN大规模注释数据集的需求。患者队列包括从LIDC / IDRI数据库中提取的431个恶性结节和795个良性结节。对于每个研究的CNN架构，所提出的融合算法在所有竞争分类模型中实现了最高的AUC，准确度，灵敏度和特异性分数。

##### URL
[http://arxiv.org/abs/1809.02333](http://arxiv.org/abs/1809.02333)

##### PDF
[http://arxiv.org/pdf/1809.02333](http://arxiv.org/pdf/1809.02333)

