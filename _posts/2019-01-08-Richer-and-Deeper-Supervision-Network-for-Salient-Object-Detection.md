---
layout: post
title: "Richer and Deeper Supervision Network for Salient Object Detection"
date: 2019-01-08 18:02:05
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection CNN Classification Detection
author: Sen Jia, Neil D. B. Bruce
mathjax: true
---

* content
{:toc}

##### Abstract
Recent Salient Object Detection (SOD) systems are mostly based on Convolutional Neural Networks (CNNs). Specifically, Deeply Supervised Saliency (DSS) system has shown it is very useful to add short connections to the network and supervising on the side output. In this work, we propose a new SOD system which aims at designing a more efficient and effective way to pass back global information. Richer and Deeper Supervision (RDS) is applied to better combine features from each side output without demanding much extra computational space. Meanwhile, the backbone network used for SOD is normally pre-trained on the object classification dataset, ImageNet. But the pre-trained model has been trained on cropped images in order to only focus on distinguishing features within the region of the object. But the ignored background information is also significant in the task of SOD. We try to solve this problem by introducing the training data designed for object detection. A coarse global information is learned based on an entire image with its bounding box before training on the SOD dataset. The large-scale of object images can slightly improve the performance of SOD. Our experiment shows the proposed RDS network achieves the state-of-the-art results on five public SOD datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.02425](http://arxiv.org/abs/1901.02425)

##### PDF
[http://arxiv.org/pdf/1901.02425](http://arxiv.org/pdf/1901.02425)

