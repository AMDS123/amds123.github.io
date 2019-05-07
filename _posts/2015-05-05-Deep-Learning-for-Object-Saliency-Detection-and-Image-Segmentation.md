---
layout: post
title: "Deep Learning for Object Saliency Detection and Image Segmentation"
date: 2015-05-05 20:03:07
categories: arXiv_CV
tags: arXiv_CV Salient Segmentation CNN Deep_Learning Detection Gradient_Descent
author: Hengyue Pan, Bo Wang, Hui Jiang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose several novel deep learning methods for object saliency detection based on the powerful convolutional neural networks. In our approach, we use a gradient descent method to iteratively modify an input image based on the pixel-wise gradients to reduce a cost function measuring the class-specific objectness of the image. The pixel-wise gradients can be efficiently computed using the back-propagation algorithm. The discrepancy between the modified image and the original one may be used as a saliency map for the image. Moreover, we have further proposed several new training methods to learn saliency-specific convolutional nets for object saliency detection, in order to leverage the available pixel-wise segmentation information. Our methods are extremely computationally efficient (processing 20-40 images per second in one GPU). In this work, we use the computed saliency maps for image segmentation. Experimental results on two benchmark tasks, namely Microsoft COCO and Pascal VOC 2012, have shown that our proposed methods can generate high-quality salience maps, clearly outperforming many existing methods. In particular, our approaches excel in handling many difficult images, which contain complex background, highly-variable salient objects, multiple objects, and/or very small salient objects.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1505.01173](https://arxiv.org/abs/1505.01173)

##### PDF
[https://arxiv.org/pdf/1505.01173](https://arxiv.org/pdf/1505.01173)

