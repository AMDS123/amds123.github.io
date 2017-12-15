---
layout: post
title: "Integrating Deep Features for Material Recognition"
date: 2016-04-21 10:19:56
categories: arXiv_CV
tags: arXiv_CV CNN Transfer_Learning Recognition
author: Yan Zhang, Mete Ozay, Xing Liu, Takayuki Okatani
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a method for integration of features extracted using deep representations of Convolutional Neural Networks (CNNs) each of which is learned using a different image dataset of objects and materials for material recognition. Given a set of representations of multiple pre-trained CNNs, we first compute activations of features using the representations on the images to select a set of samples which are best represented by the features. Then, we measure the uncertainty of the features by computing the entropy of class distributions for each sample set. Finally, we compute the contribution of each feature to representation of classes for feature selection and integration. We examine the proposed method on three benchmark datasets for material recognition. Experimental results show that the proposed method achieves state-of-the-art performance by integrating deep features. Additionally, we introduce a new material dataset called EFMD by extending Flickr Material Database (FMD). By the employment of the EFMD with transfer learning for updating the learned CNN models, we achieve 84.0%+/-1.8% accuracy on the FMD dataset which is close to human performance that is 84.9%.

##### Abstract (translated by Google)
我们提出了一种方法，使用卷积神经网络（CNN）的深度表示提取的特征进行整合，每个特征使用不同的物体和材料的图像数据集来学习，用于材料识别。给定一组多个预先训练的CNN的表示，我们首先使用图像上的表示来计算特征的激活，以选择由特征最好地表示的一组样本。然后，我们通过计算每个样本集的类分布的熵来度量特征的不确定性。最后，我们计算每个特征对特征选择和积分的类表示的贡献。我们在三个基准数据集上检查所提出的方法以进行材料识别。实验结果表明，该方法通过集成深度特征实现了最新的性能。另外，我们通过扩展Flickr材料数据库（FMD）来引入一个称为EFMD的新材料数据集。通过EFMD的转换学习来更新学习的CNN模型，FMD数据集的准确率达到了84.0％+ /  -  1.8％，与人的表现接近，达到了84.9％。

##### URL
[https://arxiv.org/abs/1511.06522](https://arxiv.org/abs/1511.06522)

##### PDF
[https://arxiv.org/pdf/1511.06522](https://arxiv.org/pdf/1511.06522)

