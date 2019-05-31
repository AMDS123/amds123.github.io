---
layout: post
title: "P3SGD: Patient Privacy Preserving SGD for Regularizing Deep CNNs in Pathological Image Classification"
date: 2019-05-30 07:07:29
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification Quantitative Gradient_Descent
author: Bingzhe Wu, Shiwan Zhao, Guangyu Sun, Xiaolu Zhang, Zhong Su, Caihong Zeng, Zhihong Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, deep convolutional neural networks (CNNs) have achieved great success in pathological image classification. However, due to the limited number of labeled pathological images, there are still two challenges to be addressed: (1) overfitting: the performance of a CNN model is undermined by the overfitting due to its huge amounts of parameters and the insufficiency of labeled training data. (2) privacy leakage: the model trained using a conventional method may involuntarily reveal the private information of the patients in the training dataset. The smaller the dataset, the worse the privacy leakage. To tackle the above two challenges, we introduce a novel stochastic gradient descent (SGD) scheme, named patient privacy preserving SGD (P3SGD), which performs the model update of the SGD in the patient level via a large-step update built upon each patient's data. Specifically, to protect privacy and regularize the CNN model, we propose to inject the well-designed noise into the updates. Moreover, we equip our P3SGD with an elaborated strategy to adaptively control the scale of the injected noise. To validate the effectiveness of P3SGD, we perform extensive experiments on a real-world clinical dataset and quantitatively demonstrate the superior ability of P3SGD in reducing the risk of overfitting. We also provide a rigorous analysis of the privacy cost under differential privacy. Additionally, we find that the models trained with P3SGD are resistant to the model-inversion attack compared with those trained using non-private SGD.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.12883](http://arxiv.org/abs/1905.12883)

##### PDF
[http://arxiv.org/pdf/1905.12883](http://arxiv.org/pdf/1905.12883)

