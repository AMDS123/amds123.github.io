---
layout: post
title: "Unsupervised Deep Feature Transfer for Low Resolution Image Classification"
date: 2019-08-27 04:06:02
categories: arXiv_CV
tags: arXiv_CV Knowledge GAN Image_Classification Classification
author: Yuanwei Wu, Ziming Zhang, Guanghui Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a simple while effective unsupervised deep feature transfer algorithm for low resolution image classification. No fine-tuning on convenet filters is required in our method. We use pre-trained convenet to extract features for both high- and low-resolution images, and then feed them into a two-layer feature transfer network for knowledge transfer. A SVM classifier is learned directly using these transferred low resolution features. Our network can be embedded into the state-of-the-art deep neural networks as a plug-in feature enhancement module. It preserves data structures in feature space for high resolution images, and transfers the distinguishing features from a well-structured source domain (high resolution features space) to a not well-organized target domain (low resolution features space). Extensive experiments on VOC2007 test set show that the proposed method achieves significant improvements over the baseline of using feature extraction.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.10012](http://arxiv.org/abs/1908.10012)

##### PDF
[http://arxiv.org/pdf/1908.10012](http://arxiv.org/pdf/1908.10012)

