---
layout: post
title: "Neural Image Compression and Explanation"
date: 2019-08-09 15:39:20
categories: arXiv_CV
tags: arXiv_CV Salient Sparse Drone CNN Image_Classification Classification Deep_Learning Prediction
author: Xiang Li, Shihao Ji
mathjax: true
---

* content
{:toc}

##### Abstract
Explaining the prediction of deep neural networks (DNNs) and semantic image compression are two active research areas of deep learning with a numerous of applications in decision-critical systems, such as surveillance cameras, drones and self-driving cars, where interpretable decision is critical and storage/network bandwidth is limited. In this paper, we propose a novel end-to-end Neural Image Compression and Explanation (NICE) framework that learns to (1) explain the prediction of convolutional neural networks (CNNs), and (2) subsequently compress the input images for efficient storage or transmission. Specifically, NICE generates a sparse mask over an input image by attaching a stochastic binary gate to each pixel of the image, whose parameters are learned through the interaction with the CNN classifier to be explained. The generated mask is able to capture the saliency of each pixel measured by its influence to the final prediction of CNN; it can also be used to produce a mixed-resolution image, where important pixels maintain their original high resolution and insignificant background pixels are subsampled to a low resolution. The produced images achieve a high compression rate (e.g., about 0.6x of original image file size), while retaining a similar classification accuracy. Extensive experiments across multiple image classification benchmarks demonstrate the superior performance of NICE compared to the state-of-the-art methods in terms of explanation quality and image compression rate.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.08988](http://arxiv.org/abs/1908.08988)

##### PDF
[http://arxiv.org/pdf/1908.08988](http://arxiv.org/pdf/1908.08988)

