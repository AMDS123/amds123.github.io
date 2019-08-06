---
layout: post
title: "Sequentially Aggregated Convolutional Networks"
date: 2019-08-03 12:24:18
categories: arXiv_CV
tags: arXiv_CV Review CNN Image_Classification Optimization Classification
author: Yiwen Huang, Rihui Wu, Pinglai Ou, Ziyong Feng
mathjax: true
---

* content
{:toc}

##### Abstract
Modern deep networks generally implement a certain form of shortcut connections to alleviate optimization difficulties. However, we observe that such network topology alters the nature of deep networks. In many ways these networks behave similarly to aggregated wide networks. We thus exploit the aggregation nature of shortcut connections at a finer architectural level and place them within wide convolutional layers. We end up with a sequentially aggregated convolutional (SeqConv) layer that combines the benefits of both wide and deep representations by aggregating features of various depths in sequence. The proposed SeqConv serves as a drop-in replacement of regular wide convolutional layers and thus could be handily integrated into any backbone network. We apply SeqConv to widely adopted backbones including ResNet and ResNeXt, and conduct experiments for image classification on public benchmark datasets. Our ResNet based network with a model size of ResNet-50 easily surpasses the performance of the 2.35$\times$ larger ResNet-152, while our ResNeXt based model sets a new state-of-the-art accuracy on ImageNet classification for networks with similar model complexity. The code and pretrained models of our work will be publicly released after review.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.10798](http://arxiv.org/abs/1811.10798)

##### PDF
[http://arxiv.org/pdf/1811.10798](http://arxiv.org/pdf/1811.10798)

