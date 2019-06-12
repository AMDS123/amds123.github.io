---
layout: post
title: "Data-Free Quantization through Weight Equalization and Bias Correction"
date: 2019-06-11 17:47:51
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Semantic_Segmentation Inference Deep_Learning Detection
author: Markus Nagel, Mart van Baalen, Tijmen Blankevoort, Max Welling
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a data-free quantization method for deep neural networks that does not require fine-tuning or hyperparameter selection. It achieves near-original model performance on common computer vision architectures and tasks. 8-bit fixed-point quantization is essential for efficient inference in modern deep learning hardware architectures. However, quantizing models to run in 8-bit is a non-trivial task, frequently leading to either significant performance reduction or engineering time spent on training a network to be amenable to quantization. Our approach relies on equalizing the weight ranges in the network by making use of a scale-equivariance property of activation functions. In addition the method corrects biases in the error that are introduced during quantization. This improves quantization accuracy performance, and can be applied ubiquitously to almost any model with a straight-forward API call. For common architectures, such as the MobileNet family, we achieve state-of-the-art quantized model performance. We further show that the method also extends to other computer vision architectures and tasks such as semantic segmentation and object detection.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.04721](http://arxiv.org/abs/1906.04721)

##### PDF
[http://arxiv.org/pdf/1906.04721](http://arxiv.org/pdf/1906.04721)

