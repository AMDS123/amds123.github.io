---
layout: post
title: "Data augmentation using learned transformations for one-shot medical image segmentation"
date: 2019-04-06 21:49:38
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Amy Zhao, Guha Balakrishnan, Fr&#xe9;do Durand, John V. Guttag, Adrian V. Dalca
mathjax: true
---

* content
{:toc}

##### Abstract
Image segmentation is an important task in many medical applications. Methods based on convolutional neural networks attain state-of-the-art accuracy; however, they typically rely on supervised training with large labeled datasets. Labeling medical images requires significant expertise and time, and typical hand-tuned approaches for data augmentation fail to capture the complex variations in such images. 
 We present an automated data augmentation method for synthesizing labeled medical images. We demonstrate our method on the task of segmenting magnetic resonance imaging (MRI) brain scans. Our method requires only a single segmented scan, and leverages other unlabeled scans in a semi-supervised approach. We learn a model of transformations from the images, and use the model along with the labeled example to synthesize additional labeled examples. Each transformation is comprised of a spatial deformation field and an intensity change, enabling the synthesis of complex effects such as variations in anatomy and image acquisition procedures. We show that training a supervised segmenter with these new examples provides significant improvements over state-of-the-art methods for one-shot biomedical image segmentation. Our code is available at https://github.com/xamyzhao/brainstorm.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.09383](http://arxiv.org/abs/1902.09383)

##### PDF
[http://arxiv.org/pdf/1902.09383](http://arxiv.org/pdf/1902.09383)

