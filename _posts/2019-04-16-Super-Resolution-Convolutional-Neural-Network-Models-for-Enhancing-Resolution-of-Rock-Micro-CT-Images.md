---
layout: post
title: "Super Resolution Convolutional Neural Network Models for Enhancing Resolution of Rock Micro-CT Images"
date: 2019-04-16 05:24:49
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Segmentation CNN
author: Ying Da Wang, Ryan Armstrong, Peyman Mostaghimi
mathjax: true
---

* content
{:toc}

##### Abstract
Single Image Super Resolution (SISR) techniques based on Super Resolution Convolutional Neural Networks (SRCNN) are applied to micro-computed tomography ({\mu}CT) images of sandstone and carbonate rocks. Digital rock imaging is limited by the capability of the scanning device resulting in trade-offs between resolution and field of view, and super resolution methods tested in this study aim to compensate for these limits. SRCNN models SR-Resnet, Enhanced Deep SR (EDSR), and Wide-Activation Deep SR (WDSR) are used on the Digital Rock Super Resolution 1 (DRSRD1) Dataset of 4x downsampled images, comprising of 2000 high resolution (800x800) raw micro-CT images of Bentheimer sandstone and Estaillades carbonate. The trained models are applied to the validation and test data within the dataset and show a 3-5 dB rise in image quality compared to bicubic interpolation, with all tested models performing within a 0.1 dB range. Difference maps indicate that edge sharpness is completely recovered in images within the scope of the trained model, with only high frequency noise related detail loss. We find that aside from generation of high-resolution images, a beneficial side effect of super resolution methods applied to synthetically downgraded images is the removal of image noise while recovering edgewise sharpness which is beneficial for the segmentation process. The model is also tested against real low-resolution images of Bentheimer rock with image augmentation to account for natural noise and blur. The SRCNN method is shown to act as a preconditioner for image segmentation under these circumstances which naturally leads to further future development and training of models that segment an image directly. Image restoration by SRCNN on the rock images is of significantly higher quality than traditional methods and suggests SRCNN methods are a viable processing step in a digital rock workflow.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.07470](http://arxiv.org/abs/1904.07470)

##### PDF
[http://arxiv.org/pdf/1904.07470](http://arxiv.org/pdf/1904.07470)

