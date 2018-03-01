---
layout: post
title: "Brain Tumor Segmentation and Radiomics Survival Prediction: Contribution to the BRATS 2017 Challenge"
date: 2018-02-28 16:19:45
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Prediction Quantitative Relation
author: Fabian Isensee, Philipp Kickingereder, Wolfgang Wick, Martin Bendszus, Klaus H. Maier-Hein
mathjax: true
---

* content
{:toc}

##### Abstract
Quantitative analysis of brain tumors is critical for clinical decision making. While manual segmentation is tedious, time consuming and subjective, this task is at the same time very challenging to solve for automatic segmentation methods. In this paper we present our most recent effort on developing a robust segmentation algorithm in the form of a convolutional neural network. Our network architecture was inspired by the popular U-Net and has been carefully modified to maximize brain tumor segmentation performance. We use a dice loss function to cope with class imbalances and use extensive data augmentation to successfully prevent overfitting. Our method beats the current state of the art on BraTS 2015, is one of the leading methods on the BraTS 2017 validation set (dice scores of 0.896, 0.797 and 0.732 for whole tumor, tumor core and enhancing tumor, respectively) and achieves very good Dice scores on the test set (0.858 for whole, 0.775 for core and 0.647 for enhancing tumor). We furthermore take part in the survival prediction subchallenge by training an ensemble of a random forest regressor and multilayer perceptrons on shape features describing the tumor subregions. Our approach achieves 52.6% accuracy, a Spearman correlation coefficient of 0.496 and a mean square error of 209607 on the test set.

##### Abstract (translated by Google)
脑肿瘤的定量分析对临床决策至关重要。虽然手动分割乏味，耗时且主观，但此任务同时对于自动分割方法的解决非常具有挑战性。在本文中，我们介绍了我们最新的工作，以卷积神经网络的形式开发了一个健壮的分割算法。我们的网络架构受到了流行的U-Net的启发，并且经过仔细修改以最大限度地提高脑肿瘤分割性能。我们使用骰子丢失功能来应对类别失衡，并使用大量数据增强来成功防止过度拟合。我们的方法胜过BraTS 2015的现有技术，是BraTS 2017验证集的主要方法之一（全肿瘤，肿瘤核心和增强肿瘤分别为0.896,0.797和0.732的骰子分数），并且达到非常好的效果骰子在测试集上的得分（整体0.858，核心0.775和增强肿瘤0.647）。我们还通过训练随机森林回归器的集合和多层感知器来描述肿瘤分区的形状特征，从而参与生存预测子挑战。我们的方法达到了52.6％的准确性，Spearman相关系数为0.496，测试集上的均方误差为209607。

##### URL
[http://arxiv.org/abs/1802.10508](http://arxiv.org/abs/1802.10508)

##### PDF
[http://arxiv.org/pdf/1802.10508](http://arxiv.org/pdf/1802.10508)

