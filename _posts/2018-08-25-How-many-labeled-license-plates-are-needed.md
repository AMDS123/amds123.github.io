---
layout: post
title: "How many labeled license plates are needed?"
date: 2018-08-25 11:11:42
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Deep_Learning Recognition
author: Changhao Wu, Shugong Xu, Guocong Song, Shunqing Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Training a good deep learning model often requires a lot of annotated data. As a large amount of labeled data is typically difficult to collect and even more difficult to annotate, data augmentation and data generation are widely used in the process of training deep neural networks. However, there is no clear common understanding on how much labeled data is needed to get satisfactory performance. In this paper, we try to address such a question using vehicle license plate character recognition as an example application. We apply computer graphic scripts and Generative Adversarial Networks to generate and augment a large number of annotated, synthesized license plate images with realistic colors, fonts, and character composition from a small number of real, manually labeled license plate images. Generated and augmented data are mixed and used as training data for the license plate recognition network modified from DenseNet. The experimental results show that the model trained from the generated mixed training data has good generalization ability, and the proposed approach achieves a new state-of-the-art accuracy on Dataset-1 and AOLP, even with a very limited number of original real license plates. In addition, the accuracy improvement caused by data generation becomes more significant when the number of labeled images is reduced. Data augmentation also plays a more significant role when the number of labeled images is increased.

##### Abstract (translated by Google)
培养良好的深度学习模型通常需要大量注释数据。由于大量标记数据通常难以收集并且甚至更难以注释，因此数据增强和数据生成被广泛用于训练深度神经网络的过程中。但是，对于获得满意性能需要多少标记数据，没有明确的共识。在本文中，我们尝试使用车牌字符识别作为示例应用来解决这样的问题。我们应用计算机图形脚本和生成对抗网络来生成和增加大量带注释的合成车牌图像，其中包含来自少量真实手动标记的车牌图像的逼真颜色，字体和字符组合。生成和增强的数据被混合并用作从DenseNet修改的车牌识别网络的训练数据。实验结果表明，从生成的混合训练数据训练的模型具有良好的泛化能力，并且所提出的方法在Dataset-1和AOLP上实现了新的最新精度，即使原始实际数量非常有限。车牌。另外，当标记图像的数量减少时，由数据生成引起的精度提高变得更加显着。当标记图像的数量增加时，数据增加也起着更重要的作用。

##### URL
[http://arxiv.org/abs/1808.08410](http://arxiv.org/abs/1808.08410)

##### PDF
[http://arxiv.org/pdf/1808.08410](http://arxiv.org/pdf/1808.08410)

