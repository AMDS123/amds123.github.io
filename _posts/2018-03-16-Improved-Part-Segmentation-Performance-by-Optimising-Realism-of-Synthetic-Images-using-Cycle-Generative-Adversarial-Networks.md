---
layout: post
title: "Improved Part Segmentation Performance by Optimising Realism of Synthetic Images using Cycle Generative Adversarial Networks"
date: 2018-03-16 16:36:43
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation GAN CNN Relation
author: Ruud Barth, Jochen Hemming, Eldert J. van Henten
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we report on improved part segmentation performance using convolutional neural networks to reduce the dependency on the large amount of manually annotated empirical images. This was achieved by optimising the visual realism of synthetic agricultural images.In Part I, a cycle consistent generative adversarial network was applied to synthetic and empirical images with the objective to generate more realistic synthetic images by translating them to the empirical domain. We first hypothesise and confirm that plant part image features such as color and texture become more similar to the empirical domain after translation of the synthetic images.Results confirm this with an improved mean color distribution correlation with the empirical data prior of 0.62 and post translation of 0.90. Furthermore, the mean image features of contrast, homogeneity, energy and entropy moved closer to the empirical mean, post translation. In Part II, 7 experiments were performed using convolutional neural networks with different combinations of synthetic, synthetic translated to empirical and empirical images. We hypothesised that the translated images can be used for (i) improved learning of empirical images, and (ii) that learning without any fine-tuning with empirical images is improved by bootstrapping with translated images over bootstrapping with synthetic images. Results confirm our second and third hypotheses. First a maximum intersection-over-union performance was achieved of 0.52 when bootstrapping with translated images and fine-tuning with empirical images; an 8% increase compared to only using synthetic images. Second, training without any empirical fine-tuning resulted in an average IOU of 0.31; a 55% performance increase over previous methods that only used synthetic images.

##### Abstract (translated by Google)
在本文中，我们报告了利用卷积神经网络改进的零件分割性能，以减少对大量手动注释的经验图像的依赖。这是通过优化合成农业图像的视觉真实性来实现的。在第I部分中，将周期一致的生成对抗网络应用于合成和经验图像，目的是通过将合成图像转化为经验域来产生更逼真的合成图像。我们首先假设并证实植物部分图像特征如颜色和纹理在合成图像的平移之后变得与经验域更相似。结果证实这与0.62之前的经验数据改进的平均颜色分布相关性和0.90。此外，对比度，均匀性，能量和熵的平均图像特征更接近经验平均值，即翻译后。在第二部分中，使用卷积神经网络进行了7个实验，其中合成的，合成的不同组合转化为经验图像和经验图像。我们假设翻译后的图像可以用于（i）经验图像的改进学习，以及（ii）通过用合成图像自举来引导翻译后的图像，改善了没有经验图像的任何微调的学习。结果证实了我们的第二和第三个假设。首先，当使用翻译图像进行自举并且用经验图像进行微调时，达到0.52的最大交叉点联合性能;与仅使用合成图像相比增加了8％。其次，没有任何经验微调的培训导致平均IOU为0.31;与以前使用合成图像的方法相比，性能提高了55％。

##### URL
[https://arxiv.org/abs/1803.06301](https://arxiv.org/abs/1803.06301)

##### PDF
[https://arxiv.org/pdf/1803.06301](https://arxiv.org/pdf/1803.06301)

