---
layout: post
title: "Computationally Efficient Deep Neural Network for Computed Tomography Image Reconstruction"
date: 2019-03-04 15:50:20
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Gradient_Descent
author: Dufan Wu, Kyungsang Kim, Quanzheng Li
mathjax: true
---

* content
{:toc}

##### Abstract
Deep-neural-network-based image reconstruction has demonstrated promising performance in medical imaging for under-sampled and low-dose scenarios. However, it requires large amount of memory and extensive time for the training. It is especially challenging to train the reconstruction networks for three-dimensional computed tomography (CT) because of the high resolution of CT images. The purpose of this work is to reduce the memory and time consumption of the training of the reconstruction networks for CT to make it practical for current hardware, while maintaining the quality of the reconstructed images. 
 We unrolled the proximal gradient descent algorithm for iterative image reconstruction to finite iterations and replaced the terms related to the penalty function with trainable convolutional neural networks (CNN). The network was trained greedily iteration by iteration in the image-domain on patches, which requires reasonable amount of memory and time on mainstream graphics processing unit (GPU). To overcome the local-minimum problem caused by greedy learning, we used deep UNet as the CNN and incorporated separable quadratic surrogate with ordered subsets for data fidelity, so that the solution could escape from easy local minimums and achieve better image quality. 
 The proposed method achieved comparable image quality with state-of-the-art neural network for CT image reconstruction on 2D sparse-view and limited-angle problems on the low-dose CT challenge dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.03999](http://arxiv.org/abs/1810.03999)

##### PDF
[http://arxiv.org/pdf/1810.03999](http://arxiv.org/pdf/1810.03999)

