---
layout: post
title: "ColorMapGAN: Unsupervised Domain Adaptation for Semantic Segmentation Using Color Mapping Generative Adversarial Networks"
date: 2019-07-30 12:30:32
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation GAN CNN Semantic_Segmentation
author: Onur Tasar, S L Happy, Yuliya Tarabalka, Pierre Alliez
mathjax: true
---

* content
{:toc}

##### Abstract
Due to the various reasons such as atmospheric effects and differences in acquisition, it is often the case that there exists a large difference between spectral bands of satellite images collected from different geographic locations. The large shift between spectral distributions of training and test data causes the current state of the art supervised learning approaches to output poor maps. We present a novel end to end semantic segmentation framework that is robust to such shift. The key component of the proposed framework is Color Mapping Generative Adversarial Networks (ColorMapGAN), which can generate fake training images that are semantically exactly the same as training images, but whose spectral distribution is similar to the distribution of the test images. We then use the fake images and the ground-truth for the training images to fine-tune the already trained classifier. Contrary to the existing Generative Adversarial Networks (GAN), the generator in ColorMapGAN does not have any convolutional or pooling layers. It learns to transform the colors of the training data to the colors of the test data by performing only one element-wise matrix multiplication and one matrix addition operations. Thanks to the architecturally simple but powerful design of ColorMapGAN, the proposed framework outperforms the existing approaches with a large margin in terms of both accuracy and computational complexity.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.12859](http://arxiv.org/abs/1907.12859)

##### PDF
[http://arxiv.org/pdf/1907.12859](http://arxiv.org/pdf/1907.12859)

