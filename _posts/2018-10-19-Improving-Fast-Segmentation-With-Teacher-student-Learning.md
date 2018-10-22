---
layout: post
title: "Improving Fast Segmentation With Teacher-student Learning"
date: 2018-10-19 12:59:32
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation Inference
author: Jiafeng Xie, Bing Shuai, Jian-Fang Hu, Jingyang Lin, Wei-Shi Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, segmentation neural networks have been significantly improved by demonstrating very promising accuracies on public benchmarks. However, these models are very heavy and generally suffer from low inference speed, which limits their application scenarios in practice. Meanwhile, existing fast segmentation models usually fail to obtain satisfactory segmentation accuracies on public benchmarks. In this paper, we propose a teacher-student learning framework that transfers the knowledge gained by a heavy and better performed segmentation network (i.e. teacher) to guide the learning of fast segmentation networks (i.e. student). Specifically, both zero-order and first-order knowledge depicted in the fine annotated images and unlabeled auxiliary data are transferred to regularize our student learning. The proposed method can improve existing fast segmentation models without incurring extra computational overhead, so it can still process images with the same fast speed. Extensive experiments on the Pascal Context, Cityscape and VOC 2012 datasets demonstrate that the proposed teacher-student learning framework is able to significantly boost the performance of student network.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.08476](http://arxiv.org/abs/1810.08476)

##### PDF
[http://arxiv.org/pdf/1810.08476](http://arxiv.org/pdf/1810.08476)

