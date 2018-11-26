---
layout: post
title: "An Adaptive Approach for Automated Grapevine Phenotyping using VGG-based Convolutional Neural Networks"
date: 2018-11-23 17:05:31
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation GAN CNN Detection
author: Jonatan Grimm, Katja Herzog, Florian Rist, Anna Kicherer, Reinhard T&#xf6;pfer, Volker Steinhage
mathjax: true
---

* content
{:toc}

##### Abstract
In (grapevine) breeding programs and research, periodic phenotyping and multi-year monitoring of different grapevine traits, like growth or yield, is needed especially in the field. This demand imply objective, precise and automated methods using sensors and adaptive software. This work presents a proof-of-concept analyzing RGB images of different growth stages of grapevines with the aim to detect and quantify promising plant organs which are related to yield. The input images are segmented by a Fully Convolutional Neural Network (FCN) into object and background pixels. The objects are plant organs like young shoots, pedicels, flower buds or grapes, which are principally suitable for yield estimation. In the ground truth of the training images, each object is separately annotated as a connected segment of object pixels, which enables end-to-end learning of the object features. Based on the CNN-based segmentation, the number of objects is determined by detecting and counting connected components of object pixels using region labeling. In an evaluation on six different data sets, the system achieves an IoU of up to 87.3% for the segmentation and an F1 score of up to 88.6% for the object detection. The reason for the good results is the combination of a powerful CNN architecture and very precise and accurate image annotations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.09561](http://arxiv.org/abs/1811.09561)

##### PDF
[http://arxiv.org/pdf/1811.09561](http://arxiv.org/pdf/1811.09561)

