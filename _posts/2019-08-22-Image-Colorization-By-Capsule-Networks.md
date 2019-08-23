---
layout: post
title: "Image Colorization By Capsule Networks"
date: 2019-08-22 11:03:14
categories: arXiv_CV
tags: arXiv_CV Image_Caption Object_Detection Segmentation Image_Classification Classification Detection
author: Gökhan Özbulak
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, a simple topology of Capsule Network (CapsNet) is investigated for the problem of image colorization. The generative and segmentation capabilities of the original CapsNet topology, which is proposed for image classification problem, is leveraged for the colorization of the images by modifying the network as follows:1) The original CapsNet model is adapted to map the grayscale input to the output in the CIE Lab colorspace, 2) The feature detector part of the model is updated by using deeper feature layers inherited from VGG-19 pre-trained model with weights in order to transfer low-level image representation capability to this model, 3) The margin loss function is modified as Mean Squared Error (MSE) loss to minimize the image-to-imagemapping. The resulting CapsNet model is named as Colorizer Capsule Network (ColorCapsNet).The performance of the ColorCapsNet is evaluated on the DIV2K dataset and promising results are obtained to investigate Capsule Networks further for image colorization problem.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.08307](https://arxiv.org/abs/1908.08307)

##### PDF
[https://arxiv.org/pdf/1908.08307](https://arxiv.org/pdf/1908.08307)

