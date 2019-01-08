---
layout: post
title: "Tencent ML-Images: A Large-Scale Multi-Label Image Database for Visual Representation Learning"
date: 2019-01-07 08:35:15
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Image_Classification Transfer_Learning Semantic_Segmentation Represenation_Learning Classification Deep_Learning Detection
author: Baoyuan Wu, Weidong Chen, Yanbo Fan, Yong Zhang, Jinlong Hou, Junzhou Huang, Wei Liu, Tong Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
In existing visual representation learning tasks, deep convolutional neural networks (CNNs) are often trained on images annotated with single tags, such as ImageNet. However, a single tag cannot describe all important contents of one image, and some useful visual information may be wasted during training. In this work, we propose to train CNNs from images annotated with multiple tags, to enhance the quality of visual representation of the trained CNN model. To this end, we build a large-scale multi-label image database with 18M images and 11K categories, dubbed Tencent ML-Images. We efficiently train the ResNet-101 model with multi-label outputs on Tencent ML-Images, taking 90 hours for 60 epochs, based on a large-scale distributed deep learning framework,i.e.,TFplus. The good quality of the visual representation of the Tencent ML-Images checkpoint is verified through three transfer learning tasks, including single-label image classification on ImageNet and Caltech-256, object detection on PASCAL VOC 2007, and semantic segmentation on PASCAL VOC 2012. The Tencent ML-Images database, the checkpoints of ResNet-101, and all the training codehave been released at https://github.com/Tencent/tencent-ml-images. It is expected to promote other vision tasks in the research and industry community.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.01703](http://arxiv.org/abs/1901.01703)

##### PDF
[http://arxiv.org/pdf/1901.01703](http://arxiv.org/pdf/1901.01703)

