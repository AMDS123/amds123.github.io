---
layout: post
title: "Normalization in Training U-Net for 2D Biomedical Semantic Segmentation"
date: 2018-12-06 21:08:02
categories: arXiv_CV
tags: arXiv_CV Review Segmentation CNN Semantic_Segmentation
author: Xiao-Yun Zhou, Guang-Zhong Yang
mathjax: true
---

* content
{:toc}

##### Abstract
2D biomedical semantic segmentation is important for robotic vision in surgery. Segmentation methods based on Deep Convolutional Neural Network (DCNN) can out-perform conventional methods in terms of both accuracy and levels of automation. One common issue in training a DCNN for biomedical semantic segmentation is the internal covariate shift where the training of convolutional kernels is encumbered by the distribution change of input features, hence both the training speed and performance are decreased. Batch Normalization (BN) is the first proposed method for addressing internal covariate shift and is widely used. Instance Normalization (IN) and Layer Normalization (LN) have also been proposed. Group Normalization (GN) is proposed more recently and has not yet been applied to 2D biomedical semantic segmentation. Most DCNNs for biomedical semantic segmentation adopt BN as the normalization method by default, without reviewing its performance. In this paper, four normalization methods - BN, IN, LN and GN are compared in details, specifically for 2D biomedical semantic segmentation. U-Net is adopted as the basic DCNN structure. Three datasets regarding the Right Ventricle (RV), aorta, and Left Ventricle (LV) are used for the validation. The results show that detailed subdivision of the feature map, i.e. GN with a large group number or IN, achieves higher accuracy. This accuracy improvement mainly comes from better model generalization rather than lower losses or a faster training speed.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.03783](http://arxiv.org/abs/1809.03783)

##### PDF
[http://arxiv.org/pdf/1809.03783](http://arxiv.org/pdf/1809.03783)

