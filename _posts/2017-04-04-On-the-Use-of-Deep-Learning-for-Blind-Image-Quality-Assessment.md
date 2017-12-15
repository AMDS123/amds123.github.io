---
layout: post
title: "On the Use of Deep Learning for Blind Image Quality Assessment"
date: 2017-04-04 14:12:38
categories: arXiv_CV
tags: arXiv_CV Image_Caption CNN Deep_Learning Prediction Relation
author: Simone Bianco, Luigi Celona, Paolo Napoletano, Raimondo Schettini
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we investigate the use of deep learning for distortion-generic blind image quality assessment. We report on different design choices, ranging from the use of features extracted from pre-trained Convolutional Neural Networks (CNNs) as a generic image description, to the use of features extracted from a CNN fine-tuned for the image quality task. Our best proposal, named DeepBIQ, estimates the image quality by average pooling the scores predicted on multiple sub-regions of the original image. The score of each sub-region is computed using a Support Vector Regression (SVR) machine taking as input features extracted using a CNN fine-tuned for category-based image quality assessment. Experimental results on the LIVE In the Wild Image Quality Challenge Database and on the LIVE Image Quality Assessment Database show that DeepBIQ outperforms the state-of-the-art methods compared, having a Linear Correlation Coefficient (LCC) with human subjective scores of almost 0.91 and 0.98 respectively. Furthermore, in most of the cases, the quality score predictions of DeepBIQ are closer to the average observer than those of a generic human observer.

##### Abstract (translated by Google)
在这项工作中，我们调查了使用深度学习的失真通用盲图像质量评估。我们报告了不同的设计选择，从使用从预先训练的卷积神经网络（CNN）提取的特征作为通用图像描述，到使用从CNN中提取的特征进行微调以完成图像质量任务。我们最好的建议，名为DeepBIQ，通过平均汇集原始图像的多个子区域上预测的分数来估计图像质量。使用支持向量回归（SVR）机器来计算每个子区域的分数，其中输入特征是使用针对基于类别的图像质量评估进行微调的CNN提取的。野外图像质量挑战数据库和现场图像质量评估数据库的实验结果表明DeepBIQ优于最先进的方法，具有线性相关系数（LCC），人类主观得分几乎为0.91和0.98。此外，在大多数情况下，DeepBIQ的质量得分预测比一般的观察者更接近一般观察者。

##### URL
[https://arxiv.org/abs/1602.05531](https://arxiv.org/abs/1602.05531)

##### PDF
[https://arxiv.org/pdf/1602.05531](https://arxiv.org/pdf/1602.05531)

