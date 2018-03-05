---
layout: post
title: "Automated Map Reading: Image Based Localisation in 2-D Maps Using Binary Semantic Descriptors"
date: 2018-03-02 10:14:27
categories: arXiv_CV
tags: arXiv_CV
author: Pilailuck Panphattarasap, Andrew Calway
mathjax: true
---

* content
{:toc}

##### Abstract
We describe a novel approach to image based localisation in urban environments using semantic matching between images and a 2-D map. It contrasts with the vast majority of existing approaches which use image to image database matching. We use highly compact binary descriptors to represent semantic features at locations, significantly increasing scalability compared with existing methods and having the potential for greater invariance to variable imaging conditions. The approach is also more akin to human map reading, making it more suited to human-system interaction. The binary descriptors indicate the presence or not of semantic features relating to buildings and road junctions in discrete viewing directions. We use CNN classifiers to detect the features in images and match descriptor estimates with a database of location tagged descriptors derived from the 2-D map. In isolation, the descriptors are not sufficiently discriminative, but when concatenated sequentially along a route, their combination becomes highly distinctive and allows localisation even when using non-perfect classifiers. Performance is further improved by taking into account left or right turns over a route. Experimental results obtained using Google StreetView and OpenStreetMap data show that the approach has considerable potential, achieving localisation accuracy of around 85% using routes corresponding to approximately 200 meters.

##### Abstract (translated by Google)
我们描述了一种在图像和二维地图之间使用语义匹配的城市环境中基于图像的定位的新方法。它与绝大多数使用图像映像数据库匹配的现有方法形成鲜明对比。我们使用高度紧凑的二进制描述符来表示位置处的语义特征，与现有方法相比显着提高了可伸缩性，并且具有对可变成像条件具有更大不变性的潜力。该方法也更类似于人类地图阅读，使其更适合于人类系统交互。二进制描述符指示在不连续的观察方向上是否存在与建筑物和道路交叉点有关的语义特征。我们使用CNN分类器来检测图像中的特征，并将匹配描述符估计与来自二维图的位置标记描述符的数据库匹配。孤立地说，描述符不具有充分的区分性，但是当沿着路径连续地连接时，它们的组合变得非常独特，并且即使在使用非完美分类器时也允许本地化。考虑到路线左转或右转，性能得到进一步改善。使用Google StreetView和OpenStreetMap数据获得的实验结果表明，该方法具有相当大的潜力，使用相当于约200米的路线实现85％左右的定位精度。

##### URL
[http://arxiv.org/abs/1803.00788](http://arxiv.org/abs/1803.00788)

##### PDF
[http://arxiv.org/pdf/1803.00788](http://arxiv.org/pdf/1803.00788)

