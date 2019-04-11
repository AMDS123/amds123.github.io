---
layout: post
title: "Weakly Supervised Learning of Instance Segmentation with Inter-pixel Relations"
date: 2019-04-10 08:02:35
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention Weakly_Supervised Image_Classification Classification Relation
author: Jiwoon Ahn, Sunghyun Cho, Suha Kwak
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a novel approach for learning instance segmentation with image-level class labels as supervision. Our approach generates pseudo instance segmentation labels of training images, which are used to train a fully supervised model. For generating the pseudo labels, we first identify confident seed areas of object classes from attention maps of an image classification model, and propagate them to discover the entire instance areas with accurate boundaries. To this end, we propose IRNet, which estimates rough areas of individual instances and detects boundaries between different object classes. It thus enables to assign instance labels to the seeds and to propagate them within the boundaries so that the entire areas of instances can be estimated accurately. Furthermore, IRNet is trained with inter-pixel relations on the attention maps, thus no extra supervision is required. Our method with IRNet achieves an outstanding performance on the PASCAL VOC 2012 dataset, surpassing not only previous state-of-the-art trained with the same level of supervision, but also some of previous models relying on stronger supervision.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.05044](http://arxiv.org/abs/1904.05044)

##### PDF
[http://arxiv.org/pdf/1904.05044](http://arxiv.org/pdf/1904.05044)

