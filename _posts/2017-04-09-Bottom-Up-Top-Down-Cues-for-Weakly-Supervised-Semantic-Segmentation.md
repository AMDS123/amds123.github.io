---
layout: post
title: "Bottom-Up Top-Down Cues for Weakly-Supervised Semantic Segmentation"
date: 2017-04-09 08:32:03
categories: arXiv_CV
tags: arXiv_CV Salient Segmentation Attention CNN Semantic_Segmentation Prediction
author: Qinbin Hou, Puneet Kumar Dokania, Daniela Massiceti, Yunchao Wei, Ming-Ming Cheng, Philip Torr
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the task of learning a classifier for semantic segmentation using weak supervision in the form of image labels which specify the object classes present in the image. Our method uses deep convolutional neural networks (CNNs) and adopts an Expectation-Maximization (EM) based approach. We focus on the following three aspects of EM: (i) initialization; (ii) latent posterior estimation (E-step) and (iii) the parameter update (M-step). We show that saliency and attention maps, our bottom-up and top-down cues respectively, of simple images provide very good cues to learn an initialization for the EM-based algorithm. Intuitively, we show that before trying to learn to segment complex images, it is much easier and highly effective to first learn to segment a set of simple images and then move towards the complex ones. Next, in order to update the parameters, we propose minimizing the combination of the standard softmax loss and the KL divergence between the true latent posterior and the likelihood given by the CNN. We argue that this combination is more robust to wrong predictions made by the expectation step of the EM method. We support this argument with empirical and visual results. Extensive experiments and discussions show that: (i) our method is very simple and intuitive; (ii) requires only image-level labels; and (iii) consistently outperforms other weakly-supervised state-of-the-art methods with a very high margin on the PASCAL VOC 2012 dataset.

##### Abstract (translated by Google)
我们考虑使用指定图像中存在的对象类的图像标签形式的弱监督来学习用于语义分割的分类器的任务。我们的方法使用深度卷积神经网络（CNN）并采用基于期望最大化（EM）的方法。我们重点关注新兴市场的以下三个方面：（i）初始化; （ii）潜在后验估计（E步骤）和（iii）参数更新（M步骤）。我们展示了显着性和注意力映射，分别从简单图像的自下而上和自上而下的提示，为基于EM的算法学习初始化提供了非常好的线索。直观地说，我们表明，在试图学习分割复杂的图像之前，首先要学会分割一组简单的图像，然后转向复杂的图像要容易得多和高效。接下来，为了更新参数，我们建议最小化标准softmax损失和真实潜后值与CNN给定可能性之间的KL散度的组合。我们认为，这种组合对于EM方法的期望步骤所做出的错误预测更有力。我们用经验和视觉的结果来支持这个论点。大量的实验和讨论表明：（i）我们的方法非常简单直观; （ii）仅需要图像级标签;和（iii）在PASCAL VOC 2012数据集中一直优于其他受监管程度较低的最先进的方法，且利用率极高。

##### URL
[https://arxiv.org/abs/1612.02101](https://arxiv.org/abs/1612.02101)

##### PDF
[https://arxiv.org/pdf/1612.02101](https://arxiv.org/pdf/1612.02101)

