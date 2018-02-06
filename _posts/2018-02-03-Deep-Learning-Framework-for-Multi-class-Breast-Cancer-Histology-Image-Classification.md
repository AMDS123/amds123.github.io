---
layout: post
title: "Deep Learning Framework for Multi-class Breast Cancer Histology Image Classification"
date: 2018-02-03 07:13:02
categories: arXiv_CV
tags: arXiv_CV Image_Classification Classification Deep_Learning Prediction Recognition
author: Yeeleng S. Vang, Zhen Chen, Xiaohui Xie
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we present a deep learning framework for multi-class breast cancer image classification as our submission to the International Conference on Image Analysis and Recognition (ICIAR) 2018 Grand Challenge on BreAst Cancer Histology images (BACH). As these histology images are too large to fit into GPU memory, we first propose using Inception V3 to perform patch level classification. The patch level predictions are then passed through an ensemble fusion framework involving majority voting, gradient boosting machine (GBM), and logistic regression to obtain the image level prediction. We improve the sensitivity of the Normal and Benign predicted classes by designing a Dual Path Network (DPN) to be used as a feature extractor where these extracted features are further sent to a second layer of ensemble prediction fusion using GBM, logistic regression, and support vector machine (SVM) to refine predictions. Experimental results demonstrate our framework shows a 12.5$\%$ improvement over the state-of-the-art model.

##### Abstract (translated by Google)
在这项工作中，我们提出了多类乳腺癌图像分类的深度学习框架，作为我们提交给国际图像分析和识别会议（ICIAR）2018年BreAst癌症组织学图像（BACH）的大挑战。由于这些组织学图像太大而不适合GPU内存，我们首先建议使用Inception V3来执行补丁级分类。然后将补丁级别预测通过包括多数投票，梯度提升机器（GBM）和逻辑回归的集成融合框架来获得图像级别预测。我们通过设计一个双路径网络（DPN）来提高Normal和Benign预测类别的灵敏度，用作特征提取器，其中这些提取的特征被进一步发送到使用GBM，逻辑回归和支持的第二层集合预测融合向量机（SVM）来改进预测。实验结果表明，我们的框架显示出比最先进的模型有12.5 $ \％$的改进。

##### URL
[http://arxiv.org/abs/1802.00931](http://arxiv.org/abs/1802.00931)

##### PDF
[http://arxiv.org/pdf/1802.00931](http://arxiv.org/pdf/1802.00931)

