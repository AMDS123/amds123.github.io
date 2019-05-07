---
layout: post
title: "Weakly Supervised Object Detection with Pointwise Mutual Information"
date: 2018-01-26 10:46:43
categories: arXiv_CV
tags: arXiv_CV Object_Detection Weakly_Supervised Embedding CNN Classification Prediction Detection
author: Rene Grzeszick, Sebastian Sudholt, Gernot A. Fink
mathjax: true
---

* content
{:toc}

##### Abstract
In this work a novel approach for weakly supervised object detection that incorporates pointwise mutual information is presented. A fully convolutional neural network architecture is applied in which the network learns one filter per object class. The resulting feature map indicates the location of objects in an image, yielding an intuitive representation of a class activation map. While traditionally such networks are learned by a softmax or binary logistic regression (sigmoid cross-entropy loss), a learning approach based on a cosine loss is introduced. A pointwise mutual information layer is incorporated in the network in order to project predictions and ground truth presence labels in a non-categorical embedding space. Thus, the cosine loss can be employed in this non-categorical representation. Besides integrating image level annotations, it is shown how to integrate point-wise annotations using a Spatial Pyramid Pooling layer. The approach is evaluated on the VOC2012 dataset for classification, point localization and weakly supervised bounding box localization. It is shown that the combination of pointwise mutual information and a cosine loss eases the learning process and thus improves the accuracy. The integration of coarse point-wise localizations further improves the results at minimal annotation costs.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1801.08747](https://arxiv.org/abs/1801.08747)

##### PDF
[https://arxiv.org/pdf/1801.08747](https://arxiv.org/pdf/1801.08747)

