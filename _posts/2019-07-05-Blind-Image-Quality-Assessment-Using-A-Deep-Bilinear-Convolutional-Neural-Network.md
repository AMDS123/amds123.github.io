---
layout: post
title: "Blind Image Quality Assessment Using A Deep Bilinear Convolutional Neural Network"
date: 2019-07-05 03:35:35
categories: arXiv_CV
tags: arXiv_CV QA CNN Image_Classification Classification Prediction Gradient_Descent
author: Weixia Zhang, Kede Ma, Jia Yan, Dexiang Deng, Zhou Wang
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a deep bilinear model for blind image quality assessment (BIQA) that handles both synthetic and authentic distortions. Our model consists of two convolutional neural networks (CNN), each of which specializes in one distortion scenario. For synthetic distortions, we pre-train a CNN to classify image distortion type and level, where we enjoy large-scale training data. For authentic distortions, we adopt a pre-trained CNN for image classification. The features from the two CNNs are pooled bilinearly into a unified representation for final quality prediction. We then fine-tune the entire model on target subject-rated databases using a variant of stochastic gradient descent. Extensive experiments demonstrate that the proposed model achieves superior performance on both synthetic and authentic databases. Furthermore, we verify the generalizability of our method on the Waterloo Exploration Database using the group maximum differentiation competition.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.02665](http://arxiv.org/abs/1907.02665)

##### PDF
[http://arxiv.org/pdf/1907.02665](http://arxiv.org/pdf/1907.02665)

