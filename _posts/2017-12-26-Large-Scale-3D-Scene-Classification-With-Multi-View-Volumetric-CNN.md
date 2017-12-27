---
layout: post
title: "Large-Scale 3D Scene Classification With Multi-View Volumetric CNN"
date: 2017-12-26 09:13:12
categories: arXiv_CV
tags: arXiv_CV Salient Face Image_Classification Classification
author: Dror Aiger, Brett Allen, Aleksey Golovinskiy
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a method to classify imagery using a convo- lutional neural network (CNN) on multi-view image pro- jections. The power of our method comes from using pro- jections of multiple images at multiple depth planes near the reconstructed surface. This enables classification of categories whose salient aspect is appearance change un- der different viewpoints, such as water, trees, and other materials with complex reflection/light response proper- ties. Our method does not require boundary labelling in images and works on pixel-level classification with a small (few pixels) context, which simplifies the cre- ation of a training set. We demonstrate this application on large-scale aerial imagery collections, and extend the per-pixel classification to robustly create a consistent 2D classification which can be used to fill the gaps in non- reconstructible water regions. We also apply our method to classify tree regions. In both cases, the training data can quickly be generated using a small number of manually- created polygons on a map. We show that even with a very simple and standard network our CNN outperforms the state-of-the-art image classification, the Inception-V3 model retrained from a large collection of aerial images.

##### Abstract (translated by Google)
我们介绍一种在多视图图像投影中使用一个神经网络（CNN）对图像进行分类的方法。我们的方法的力量来自在重建表面附近的多个深度平面使用多个图像的投影。这样就可以对突出显示外观的类别进行分类，以适应不同的观点，例如水，树木和其他具有复杂反射/光响应特性的材料。我们的方法不需要在图像中进行边界标记，而是使用小（几个像素）的上下文进行像素级分类，这简化了训练集的创建。我们在大规模的航空图像收集中展示了这个应用，并且扩展了每像素分类以强有力地创建一个一致的2D分类，可以用来填补非重建水域的空白。我们也应用我们的方法来分类树区域。在这两种情况下，都可以使用地图上的少量手动创建的多边形快速生成训练数据。我们发现，即使是一个非常简单和标准的网络我们的CNN优于国家的最先进的图像分类，先启-V3模型从收集了大量航拍图像的再培训。

##### URL
[http://arxiv.org/abs/1712.09216](http://arxiv.org/abs/1712.09216)

##### PDF
[http://arxiv.org/pdf/1712.09216](http://arxiv.org/pdf/1712.09216)

