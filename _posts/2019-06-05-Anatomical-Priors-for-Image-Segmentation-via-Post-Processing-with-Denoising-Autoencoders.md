---
layout: post
title: "Anatomical Priors for Image Segmentation via Post-Processing with Denoising Autoencoders"
date: 2019-06-05 22:41:11
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Agostina J. Larrazabal, Cesar Martinez, Enzo Ferrante
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural networks (CNN) proved to be highly accurate to perform anatomical segmentation of medical images. However, some of the most popular CNN architectures for image segmentation still rely on post-processing strategies (e.g. Conditional Random Fields) to incorporate connectivity constraints into the resulting masks. These post-processing steps are based on the assumption that objects are usually continuous and therefore nearby pixels should be assigned the same object label. Even if it is a valid assumption in general, these methods do not offer a straightforward way to incorporate more complex priors like convexity or arbitrary shape restrictions. In this work we propose Post-DAE, a post-processing method based on denoising autoencoders (DAE) trained using only segmentation masks. We learn a low-dimensional space of anatomically plausible segmentations, and use it as a post-processing step to impose shape constraints on the resulting masks obtained with arbitrary segmentation methods. Our approach is independent of image modality and intensity information since it employs only segmentation masks for training. This enables the use of anatomical segmentations that do not need to be paired with intensity images, making the approach very flexible. Our experimental results on anatomical segmentation of X-ray images show that Post-DAE can improve the quality of noisy and incorrect segmentation masks obtained with a variety of standard methods, by bringing them back to a feasible space, with almost no extra computational time.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.02343](http://arxiv.org/abs/1906.02343)

##### PDF
[http://arxiv.org/pdf/1906.02343](http://arxiv.org/pdf/1906.02343)

