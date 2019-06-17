---
layout: post
title: "A Partially Reversible U-Net for Memory-Efficient Volumetric Image Segmentation"
date: 2019-06-14 12:04:46
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Image_Classification Classification
author: Robin Brügger, Christian F. Baumgartner, Ender Konukoglu
mathjax: true
---

* content
{:toc}

##### Abstract
One of the key drawbacks of 3D convolutional neural networks for segmentation is their memory footprint, which necessitates compromises in the network architecture in order to fit into a given memory budget. Motivated by the RevNet for image classification, we propose a partially reversible U-Net architecture that reduces memory consumption substantially. The reversible architecture allows us to exactly recover each layer's outputs from the subsequent layer's ones, eliminating the need to store activations for backpropagation. This alleviates the biggest memory bottleneck and enables very deep (theoretically infinitely deep) 3D architectures. On the BraTS challenge dataset, we demonstrate substantial memory savings. We further show that the freed memory can be used for processing the whole field-of-view (FOV) instead of patches. Increasing network depth led to higher segmentation accuracy while growing the memory footprint only by a very small fraction, thanks to the partially reversible architecture.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.06148](https://arxiv.org/abs/1906.06148)

##### PDF
[https://arxiv.org/pdf/1906.06148](https://arxiv.org/pdf/1906.06148)

