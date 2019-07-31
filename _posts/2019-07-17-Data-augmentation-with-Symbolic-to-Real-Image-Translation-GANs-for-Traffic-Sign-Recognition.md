---
layout: post
title: "Data augmentation with Symbolic-to-Real Image Translation GANs for Traffic Sign Recognition"
date: 2019-07-17 21:52:01
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Image_Classification Classification Recognition
author: Nour Soufi, Matias Valdenegro-Toro
mathjax: true
---

* content
{:toc}

##### Abstract
Traffic sign recognition is an important component of many advanced driving assistance systems, and it is required for full autonomous driving. Computational performance is usually the bottleneck in using large scale neural networks for this purpose. SqueezeNet is a good candidate for efficient image classification of traffic signs, but in our experiments it does not reach high accuracy, and we believe this is due to lack of data, requiring data augmentation. Generative adversarial networks can learn the high dimensional distribution of empirical data, allowing the generation of new data points. In this paper we apply pix2pix GANs architecture to generate new traffic sign images and evaluate the use of these images in data augmentation. We were motivated to use pix2pix to translate symbolic sign images to real ones due to the mode collapse in Conditional GANs. Through our experiments we found that data augmentation using GAN can increase classification accuracy for circular traffic signs from 92.1% to 94.0%, and for triangular traffic signs from 93.8% to 95.3%, producing an overall improvement of 2%. However some traditional augmentation techniques can outperform GAN data augmentation, for example contrast variation in circular traffic signs (95.5%) and displacement on triangular traffic signs (96.7 %). Our negative results shows that while GANs can be naively used for data augmentation, they are not always the best choice, depending on the problem and variability in the data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.12902](http://arxiv.org/abs/1907.12902)

##### PDF
[http://arxiv.org/pdf/1907.12902](http://arxiv.org/pdf/1907.12902)

