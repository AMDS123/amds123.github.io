---
layout: post
title: "Adversarial Learning for Semi-Supervised Semantic Segmentation"
date: 2018-02-22 08:13:20
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation CNN Semantic_Segmentation Prediction
author: Wei-Chih Hung, Yi-Hsuan Tsai, Yan-Ting Liou, Yen-Yu Lin, Ming-Hsuan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a method for semi-supervised semantic segmentation using the adversarial network. While most existing discriminators are trained to classify input images as real or fake on the image level, we design a discriminator in a fully convolutional manner to differentiate the predicted probability maps from the ground truth segmentation distribution with the consideration of the spatial resolution. We show that the proposed discriminator can be used to improve the performance on semantic segmentation by coupling the adversarial loss with the standard cross entropy loss on the segmentation network. In addition, the fully convolutional discriminator enables the semi-supervised learning through discovering the trustworthy regions in prediction results of unlabeled images, providing additional supervisory signals. In contrast to existing methods that utilize weakly-labeled images, our method leverages unlabeled images without any annotation to enhance the segmentation model. Experimental results on both the PASCAL VOC 2012 dataset and the Cityscapes dataset demonstrate the effectiveness of our algorithm.

##### Abstract (translated by Google)
我们提出了一种使用敌对网络进行半监督语义分割的方法。虽然大多数现有的鉴别器被训练来将输入图像分类为图像级别的真实或伪造，但我们设计了一种以完全卷积方式的鉴别器，以将预测概率图与地面真实分割分布区分开来，并考虑了空间分辨率。我们表明，提出的鉴别器可以用来改善语义分割的性能，通过将对抗性损失与分割网络上的标准交叉熵损失相结合。另外，完全卷积鉴别器通过在未标记图像的预测结果中发现可信区域来提供附加监督信号，从而实现半监督学习。与利用弱标记图像的现有方法相比，我们的方法利用未标记的图像而没有任何注释来增强分割模型。 PASCAL VOC 2012数据集和Cityscapes数据集的实验结果都证明了我们算法的有效性。

##### URL
[http://arxiv.org/abs/1802.07934](http://arxiv.org/abs/1802.07934)

##### PDF
[http://arxiv.org/pdf/1802.07934](http://arxiv.org/pdf/1802.07934)

