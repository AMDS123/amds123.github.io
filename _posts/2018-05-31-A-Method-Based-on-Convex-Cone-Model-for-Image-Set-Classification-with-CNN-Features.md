---
layout: post
title: "A Method Based on Convex Cone Model for Image-Set Classification with CNN Features"
date: 2018-05-31 13:47:09
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Naoya Sogi, Taku Nakayama, Kazuhiro Fukui
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a method for image-set classification based on convex cone models, focusing on the effectiveness of convolutional neural network (CNN) features as inputs. CNN features have non-negative values when using the rectified linear unit as an activation function. This naturally leads us to model a set of CNN features by a convex cone and measure the geometric similarity of convex cones for classification. To establish this framework, we sequentially define multiple angles between two convex cones by repeating the alternating least squares method and then define the geometric similarity between the cones using the obtained angles. Moreover, to enhance our method, we introduce a discriminant space, maximizing the between-class variance (gaps) and minimizes the within-class variance of the projected convex cones onto the discriminant space, similar to a Fisher discriminant analysis. Finally, classification is based on the similarity between projected convex cones. The effectiveness of the proposed method was demonstrated experimentally using a private, multi-view hand shape dataset and two public databases.

##### Abstract (translated by Google)
在本文中，我们提出了一种基于凸锥模型的图像集分类方法，着眼于卷积神经网络（CNN）特征作为输入的有效性。将整流线性单元用作激活功能时，CNN功能具有非负值。这自然导致我们用凸锥对一组CNN特征进行建模，并测量凸锥的几何相似性以进行分类。为了建立这个框架，我们通过重复交替最小二乘法依次定义两个凸锥之间的多个角度，然后使用获得的角度定义锥体之间的几何相似度。此外，为了加强我们的方法，我们引入了判别空间，类间方差（间隙）最大化，并将投影凸锥的类内方差最小化到判别空间上，类似于Fisher判别分析。最后，分类基于投影凸锥之间的相似性。所提出的方法的有效性通过使用私人的多视图手形数据集和两个公共数据库的实验证明。

##### URL
[http://arxiv.org/abs/1805.12467](http://arxiv.org/abs/1805.12467)

##### PDF
[http://arxiv.org/pdf/1805.12467](http://arxiv.org/pdf/1805.12467)

