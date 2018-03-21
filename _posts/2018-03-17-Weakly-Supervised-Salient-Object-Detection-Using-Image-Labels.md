---
layout: post
title: "Weakly Supervised Salient Object Detection Using Image Labels"
date: 2018-03-17 13:40:00
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection Weakly_Supervised CNN Classification Deep_Learning Detection
author: Guanbin Li, Yuan Xie, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning based salient object detection has recently achieved great success with its performance greatly outperforms any other unsupervised methods. However, annotating per-pixel saliency masks is a tedious and inefficient procedure. In this paper, we note that superior salient object detection can be obtained by iteratively mining and correcting the labeling ambiguity on saliency maps from traditional unsupervised methods. We propose to use the combination of a coarse salient object activation map from the classification network and saliency maps generated from unsupervised methods as pixel-level annotation, and develop a simple yet very effective algorithm to train fully convolutional networks for salient object detection supervised by these noisy annotations. Our algorithm is based on alternately exploiting a graphical model and training a fully convolutional network for model updating. The graphical model corrects the internal labeling ambiguity through spatial consistency and structure preserving while the fully convolutional network helps to correct the cross-image semantic ambiguity and simultaneously update the coarse activation map for next iteration. Experimental results demonstrate that our proposed method greatly outperforms all state-of-the-art unsupervised saliency detection methods and can be comparable to the current best strongly-supervised methods training with thousands of pixel-level saliency map annotations on all public benchmarks.

##### Abstract (translated by Google)
基于深度学习的显着对象检测最近取得了巨大的成功，其性能远远优于其他无监督方法。但是，注释每像素显着性掩码是一个单调乏味且效率低下的过程。在本文中，我们注意到通过迭代挖掘和校正传统无监督方法的显着图上的标注歧义可以获得优越的显着对象检测。我们建议使用分类网络中粗糙的显着物体激活图和非监督方法生成的显着图作为像素级注释的组合，并开发一种简单但非常有效的算法来训练完全卷积网络，以便对这些网络进行显着物体检测嘈杂的注释。我们的算法是基于交替开发图形模型和训练完全卷积网络进行模型更新。图形模型通过空间一致性和结构保留来纠正内部标注歧义，而完全卷积网络有助于纠正跨图像语义歧义并同时更新下一次迭代的粗略激活图。实验结果表明，我们提出的方法大大优于所有最先进的无监督显着性检测方法，并且可以与当前在所有公共基准上使用数千个像素级显着图注释训练的最佳强监督方法相媲美。

##### URL
[https://arxiv.org/abs/1803.06503](https://arxiv.org/abs/1803.06503)

##### PDF
[https://arxiv.org/pdf/1803.06503](https://arxiv.org/pdf/1803.06503)

