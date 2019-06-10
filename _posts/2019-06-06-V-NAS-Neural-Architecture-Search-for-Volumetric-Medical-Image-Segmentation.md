---
layout: post
title: "V-NAS: Neural Architecture Search for Volumetric Medical Image Segmentation"
date: 2019-06-06 21:07:40
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN NAS CNN Deep_Learning
author: Zhuotun Zhu, Chenxi Liu, Dong Yang, Alan Yuille, Daguang Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning algorithms, in particular 2D and 3D fully convolutional neural networks (FCNs), have rapidly become the mainstream methodology for volumetric medical image segmentation. However, 2D convolutions cannot fully leverage the rich spatial information along the third axis, while 3D convolutions suffer from the demanding computation and high GPU memory consumption. In this paper, we propose to automatically search the network architecture tailoring to volumetric medical image segmentation problem. Concretely, we formulate the structure learning as differentiable neural architecture search, and let the network itself choose between 2D, 3D or Pseudo-3D (P3D) convolutions at each layer. We evaluate our method on 3 public datasets, i.e., the NIH Pancreas dataset, the Lung and Pancreas dataset from the Medical Segmentation Decathlon (MSD) Challenge. Our method, named V-NAS, consistently outperforms other state-of-the-arts on the segmentation task of both normal organ (NIH Pancreas) and abnormal organs (MSD Lung tumors and MSD Pancreas tumors), which shows the power of chosen architecture. Moreover, the searched architecture on one dataset can be well generalized to other datasets, which demonstrates the robustness and practical use of our proposed method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.02817](http://arxiv.org/abs/1906.02817)

##### PDF
[http://arxiv.org/pdf/1906.02817](http://arxiv.org/pdf/1906.02817)

