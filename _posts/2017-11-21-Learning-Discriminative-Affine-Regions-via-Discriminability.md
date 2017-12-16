---
layout: post
title: "Learning Discriminative Affine Regions via Discriminability"
date: 2017-11-21 09:51:54
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection Gradient_Descent
author: Dmytro Mishkin, Filip Radenovic, Jiri Matas
mathjax: true
---

* content
{:toc}

##### Abstract
We present an accurate method for estimation of the affine shape of local features. The method is trained in a novel way, exploiting the recently proposed HardNet triplet loss. The loss function is driven by patch descriptor differences, avoiding problems with symmetries. Moreover, such training process does not require precisely geometrically aligned patches. The affine shape is represented in a way amenable to learning by stochastic gradient descent. When plugged into a state-of-the-art wide baseline matching algorithm, the performance on standard datasets improves in both the number of challenging pairs matched and the number of inliers. Finally, AffNet with combination of Hessian detector and HardNet descriptor improves bag-of-visual-words based state of the art on Oxford5k and Paris6k by large margin, 4.5 and 4.2 mAP points respectively. The source code and trained networks are available at this https URL

##### Abstract (translated by Google)
我们提出了一个准确的方法来估计仿射形状的局部特征。该方法以新颖的方式进行训练，利用最近提出的HardNet三重损失。损失函数由补丁描述符差异驱动，避免了对称性问题。而且，这样的训练过程不需要精确地几何对齐的贴片。仿射形状以适合于随机梯度下降学习的方式表示。当插入到最先进的宽基线匹配算法中时，标准数据集的性能在匹配的挑战对的数量和内点数量方面均有所提高。最后，结合Hessian检测器和HardNet描述符的AffNet分别在Oxford5k和Paris6k上分别提高了基于视觉词袋的视觉效果，分别为4.5和4.2 mAP点。源代码和经过培训的网络可在此https网址获得

##### URL
[https://arxiv.org/abs/1711.06704](https://arxiv.org/abs/1711.06704)

##### PDF
[https://arxiv.org/pdf/1711.06704](https://arxiv.org/pdf/1711.06704)

