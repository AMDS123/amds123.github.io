---
layout: post
title: "LCNN: Low-level Feature Embedded CNN for Salient Object Detection"
date: 2015-08-17 05:45:12
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection CNN Detection
author: Hongyang Li, Huchuan Lu, Zhe Lin, Xiaohui Shen, Brian Price
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel deep neural network framework embedded with low-level features (LCNN) for salient object detection in complex images. We utilise the advantage of convolutional neural networks to automatically learn the high-level features that capture the structured information and semantic context in the image. In order to better adapt a CNN model into the saliency task, we redesign the network architecture based on the small-scale datasets. Several low-level features are extracted, which can effectively capture contrast and spatial information in the salient regions, and incorporated to compensate with the learned high-level features at the output of the last fully connected layer. The concatenated feature vector is further fed into a hinge-loss SVM detector in a joint discriminative learning manner and the final saliency score of each region within the bounding box is obtained by the linear combination of the detector's weights. Experiments on three challenging benchmark (MSRA-5000, PASCAL-S, ECCSD) demonstrate our algorithm to be effective and superior than most low-level oriented state-of-the-arts in terms of P-R curves, F-measure and mean absolute errors.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1508.03928](https://arxiv.org/abs/1508.03928)

##### PDF
[https://arxiv.org/pdf/1508.03928](https://arxiv.org/pdf/1508.03928)

