---
layout: post
title: "Fully Automatic Segmentation of Sublingual Veins from Retrained U-Net Model for Few Near Infrared Images"
date: 2018-12-22 08:27:45
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation Deep_Learning
author: Tingxiao Yang, Yuichiro Yoshimura, Akira Morita, Takao Namiki, Toshiya Nakaguchi
mathjax: true
---

* content
{:toc}

##### Abstract
Sublingual vein is commonly used to diagnose the health status. The width of main sublingual veins gives information of the blood circulation. Therefore, it is necessary to segment the main sublingual veins from the tongue automatically. In general, the dataset in the medical field is small, which is a challenge for training the deep learning model. In order to train the model with a small data set, the proposed method for automatically segmenting the sublingual veins is to re-train U-net model with different sets of the limited number of labels for the same training images. With pre-knowledge of the segmentation, the loss of the trained model will be convergence easier. To improve the performance of the segmentation further, a novel strategy of data augmentation was utilized. The operation for masking output of the model with the input was randomly switched on or switched off in each training step. This approach will force the model to learn the contrast invariance and avoid overfitting. Images of dataset were taken with the developed device using eight near infrared LEDs. The final segmentation results were evaluated on the validation dataset by the IoU metric.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.09477](http://arxiv.org/abs/1812.09477)

##### PDF
[http://arxiv.org/pdf/1812.09477](http://arxiv.org/pdf/1812.09477)

