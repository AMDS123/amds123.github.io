---
layout: post
title: "Surprising Effectiveness of Few-Image Unsupervised Feature Learning"
date: 2019-04-30 10:10:38
categories: arXiv_CV
tags: arXiv_CV GAN CNN Represenation_Learning
author: Yuki M. Asano, Christian Rupprecht, Andrea Vedaldi
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art methods for unsupervised representation learning can train well the first few layers of standard convolutional neural networks, but they are not as good as supervised learning for deeper layers. This is likely due to the generic and relatively simple nature of shallow layers; and yet, these approaches are applied to millions of images, scalability being advertised as their major advantage since unlabelled data is cheap to collect. In this paper we question this practice and ask whether so many images are actually needed to learn the layers for which unsupervised learning works best. Our main result is that a few or even a single image together with strong data augmentation are sufficient to nearly saturate performance. Specifically, we provide an analysis for three different self-supervised feature learning methods (BiGAN, RotNet, DeepCluster) vs number of training images (1, 10, 1000) and show that we can top the accuracy for the first two convolutional layers of common networks using just a single unlabelled training image and obtain competitive results for other layers. We further study and visualize the learned representation as a function of which (single) image is used for training. Our results are also suggestive of which type of information may be captured by shallow layers in deep networks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.13132](http://arxiv.org/abs/1904.13132)

##### PDF
[http://arxiv.org/pdf/1904.13132](http://arxiv.org/pdf/1904.13132)

