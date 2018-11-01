---
layout: post
title: "SDFN: Segmentation-based Deep Fusion Network for Thoracic Disease Classification in Chest X-ray Images"
date: 2018-10-30 18:37:10
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Classification
author: Han Liu, Lei Wang, Yandong Nan, Faguang Jin, Jiantao Pu
mathjax: true
---

* content
{:toc}

##### Abstract
This study aims to automatically diagnose thoracic diseases depicted on the chest x-ray (CXR) images using deep convolutional neural networks. The existing methods generally used the entire CXR images for training purposes, but this strategy may suffer from two drawbacks. First, potential misalignment or the existence of irrelevant objects in the entire CXR images may cause unnecessary noise and thus limit the network performance. Second, the relatively low image resolution caused by the resizing operation, which is a common preprocessing procedure for training neural networks, may lead to the loss of image details, making it difficult to detect pathologies with small lesion regions. To address these issues, we present a novel method termed as segmentation-based deep fusion network (SDFN), which leverages the higher-resolution information of local lung regions. Specifically, the local lung regions were identified and cropped by the Lung Region Generator (LRG). Two CNN-based classification models were then used as feature extractors to obtain the discriminative features of the entire CXR images and the cropped lung region images. Lastly, the obtained features were fused by the feature fusion module for disease classification. Evaluated by the NIH benchmark split on the Chest X-ray 14 Dataset, our experimental result demonstrated that the developed method achieved more accurate disease classification compared with the available approaches via the receiver operating characteristic (ROC) analyses. It was also found that the SDFN could localize the lesion regions more precisely as compared to the traditional method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.12959](http://arxiv.org/abs/1810.12959)

##### PDF
[http://arxiv.org/pdf/1810.12959](http://arxiv.org/pdf/1810.12959)

