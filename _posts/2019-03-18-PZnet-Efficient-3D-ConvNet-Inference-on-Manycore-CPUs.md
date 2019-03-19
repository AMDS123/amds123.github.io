---
layout: post
title: "PZnet: Efficient 3D ConvNet Inference on Manycore CPUs"
date: 2019-03-18 16:07:12
categories: arXiv_CV
tags: arXiv_CV CNN Inference
author: Sergiy Popovych, Davit Buniatyan, Aleksandar Zlateski, Kai Li, H. Sebastian Seung
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional nets have been shown to achieve state-of-the-art accuracy in many biomedical image analysis tasks. Many tasks within biomedical analysis domain involve analyzing volumetric (3D) data acquired by CT, MRI and Microscopy acquisition methods. To deploy convolutional nets in practical working systems, it is important to solve the efficient inference problem. Namely, one should be able to apply an already-trained convolutional network to many large images using limited computational resources. In this paper we present PZnet, a CPU-only engine that can be used to perform inference for a variety of 3D convolutional net architectures. PZNet outperforms MKL-based CPU implementations of PyTorch and Tensorflow by more than 3.5x for the popular U-net architecture. Moreover, for 3D convolutions with low featuremap numbers, cloud CPU inference with PZnet outperfroms cloud GPU inference in terms of cost efficiency.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.07525](http://arxiv.org/abs/1903.07525)

##### PDF
[http://arxiv.org/pdf/1903.07525](http://arxiv.org/pdf/1903.07525)

