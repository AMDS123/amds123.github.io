---
layout: post
title: "An Algorithm for Learning Shape and Appearance Models without Annotations"
date: 2018-07-27 16:59:22
categories: arXiv_CV
tags: arXiv_CV Face
author: John Ashburner, Mikael Brudfors, Kevin Bronik, Yael Balbastre
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a framework for automatically learning shape and appearance models for medical (and certain other) images. It is based on the idea that having a more accurate shape and appearance model leads to more accurate image registration, which in turn leads to a more accurate shape and appearance model. This leads naturally to an iterative scheme, which is based on a probabilistic generative model that is fit using Gauss-Newton updates within an EM-like framework. It was developed with the aim of enabling distributed privacy-preserving analysis of brain image data, such that shared information (shape and appearance basis functions) may be passed across sites, whereas latent variables that encode individual images remain secure within each site. These latent variables are proposed as features for privacy-preserving data mining applications. 
 The approach is demonstrated qualitatively on the KDEF dataset of 2D face images, showing that it can align images that traditionally require shape and appearance models trained using manually annotated data (manually defined landmarks etc.). It is applied to MNIST dataset of handwritten digits to show its potential for machine learning applications, particularly when training data is limited. The model is able to handle ``missing data'', which allows it to be cross-validated according to how well it can predict left-out voxels. The suitability of the derived features for classifying individuals into patient groups was assessed by applying it to a dataset of over 1,900 segmented T1-weighted MR images, which included images from the COBRE and ABIDE datasets.

##### Abstract (translated by Google)
本文提出了一个自动学习医学（和某些其他）图像的形状和外观模型的框架。它基于这样的想法：具有更精确的形状和外观模型导致更准确的图像配准，这反过来导致更精确的形状和外观模型。这自然导致迭代方案，其基于概率生成模型，其在EM类框架内使用高斯 - 牛顿更新拟合。它的开发目的是实现对大脑图像数据的分布式隐私保护分析，使得共享信息（形状和外观基础功能）可以跨站点传递，而编码单个图像的潜在变量在每个站点内保持安全。提出这些潜在变量作为保护隐私的数据挖掘应用程序的特征。
 该方法在2D面部图像的KDEF数据集上定性地展示，表明它可以对准传统上需要使用手动注释数据（手动定义的地标等）训练的形状和外观模型的图像。它适用于手写数字的MNIST数据集，以显示其机器学习应用的潜力，特别是在训练数据有限时。该模型能够处理“缺失数据”，这使得它可以根据预测剩余体素的程度进行交叉验证。通过将其应用于超过1,900个分段的T1加权MR图像的数据集来评估导出的特征用于将个体分类到患者组中的适合性，所述MR图像包括来自COBRE和ABIDE数据集的图像。

##### URL
[http://arxiv.org/abs/1807.10731](http://arxiv.org/abs/1807.10731)

##### PDF
[http://arxiv.org/pdf/1807.10731](http://arxiv.org/pdf/1807.10731)

