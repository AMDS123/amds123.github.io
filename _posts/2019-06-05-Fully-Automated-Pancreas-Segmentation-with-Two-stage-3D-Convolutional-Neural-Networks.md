---
layout: post
title: "Fully Automated Pancreas Segmentation with Two-stage 3D Convolutional Neural Networks"
date: 2019-06-05 02:48:24
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN CNN
author: Ningning Zhao, Nuo Tong, Dan Ruan, Ke Sheng
mathjax: true
---

* content
{:toc}

##### Abstract
Due to the fact that pancreas is an abdominal organ with very large variations in shape and size, automatic and accurate pancreas segmentation can be challenging for medical image analysis. In this work, we proposed a fully automated two stage framework for pancreas segmentation based on convolutional neural networks (CNN). In the first stage, a U-Net is trained for the down-sampled 3D volume segmentation. Then a candidate region covering the pancreas is extracted from the estimated labels. Motivated by the superior performance reported by renowned region based CNN, in the second stage, another 3D U-Net is trained on the candidate region generated in the first stage. We evaluated the performance of the proposed method on the NIH computed tomography (CT) dataset, and verified its superiority over other state-of-the-art 2D and 3D approaches for pancreas segmentation in terms of dice-sorensen coefficient (DSC) accuracy in testing. The mean DSC of the proposed method is 85.99%.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.01795](http://arxiv.org/abs/1906.01795)

##### PDF
[http://arxiv.org/pdf/1906.01795](http://arxiv.org/pdf/1906.01795)

