---
layout: post
title: "Data augmentation using learned transforms for one-shot medical image segmentation"
date: 2019-02-25 15:49:47
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Amy Zhao, Guha Balakrishnan, Fr&#xe9;do Durand, John V. Guttag, Adrian V. Dalca
mathjax: true
---

* content
{:toc}

##### Abstract
Biomedical image segmentation is an important task in many medical applications. Segmentation methods based on convolutional neural networks attain state-of-the-art accuracy; however, they typically rely on supervised training with large labeled datasets. Labeling datasets of medical images requires significant expertise and time, and is infeasible at large scales. To tackle the lack of labeled data, researchers use techniques such as hand-engineered preprocessing steps, hand-tuned architectures, and data augmentation. However, these techniques involve costly engineering efforts, and are typically dataset-specific. 
 We present an automated data augmentation method for medical images. We demonstrate our method on the task of segmenting magnetic resonance imaging (MRI) brain scans, focusing on the one-shot segmentation scenario -- a practical challenge in many medical applications. Our method requires only a single segmented scan, and leverages other unlabeled scans in a semi-supervised approach. We learn a model of transforms from the images, and use the model along with the labeled example to synthesize additional labeled training examples for supervised segmentation. Each transform is comprised of a spatial deformation field and an intensity change, enabling the synthesis of complex effects such as variations in anatomy and image acquisition procedures. Augmenting the training of a supervised segmenter with these new examples provides significant improvements over state-of-the-art methods for one-shot biomedical image segmentation. Our code is available at https://github.com/xamyzhao/brainstorm.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.09383](http://arxiv.org/abs/1902.09383)

##### PDF
[http://arxiv.org/pdf/1902.09383](http://arxiv.org/pdf/1902.09383)

