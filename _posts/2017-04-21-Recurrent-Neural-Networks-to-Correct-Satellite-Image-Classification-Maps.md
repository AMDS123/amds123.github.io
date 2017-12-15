---
layout: post
title: "Recurrent Neural Networks to Correct Satellite Image Classification Maps"
date: 2017-04-21 11:08:37
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification RNN Classification
author: Emmanuel Maggiori, Guillaume Charpiat, Yuliya Tarabalka, Pierre Alliez
mathjax: true
---

* content
{:toc}

##### Abstract
While initially devised for image categorization, convolutional neural networks (CNNs) are being increasingly used for the pixelwise semantic labeling of images. However, the proper nature of the most common CNN architectures makes them good at recognizing but poor at localizing objects precisely. This problem is magnified in the context of aerial and satellite image labeling, where a spatially fine object outlining is of paramount importance. Different iterative enhancement algorithms have been presented in the literature to progressively improve the coarse CNN outputs, seeking to sharpen object boundaries around real image edges. However, one must carefully design, choose and tune such algorithms. Instead, our goal is to directly learn the iterative process itself. For this, we formulate a generic iterative enhancement process inspired from partial differential equations, and observe that it can be expressed as a recurrent neural network (RNN). Consequently, we train such a network from manually labeled data for our enhancement task. In a series of experiments we show that our RNN effectively learns an iterative process that significantly improves the quality of satellite image classification maps.

##### Abstract (translated by Google)
虽然最初设计用于图像分类，卷积神经网络（CNN）正被越来越多地用于图像的像素语义标记。但是，最常见的CNN体​​系结构的适当性使得它们能够很好地识别但精确地定位对象。这个问题在航空和卫星图像标记的背景下被放大，其中空间上精细的物体轮廓是最重要的。在文献中已经提出了不同的迭代增强算法，以逐步改进粗CNN输出，试图锐化真实图像边缘周围的对象边界。但是，必须仔细设计，选择和调整这样的算法。相反，我们的目标是直接学习迭代过程本身。为此，我们制定了一个从偏微分方程启发的通用迭代增强过程，并观察到它可以表示为递归神经网络（RNN）。因此，我们从我们的增强任务的手动标记数据训练这样一个网络。在一系列实验中，我们表明，我们的RNN有效地学习了一个迭代过程，显着提高了卫星图像分类图的质量。

##### URL
[https://arxiv.org/abs/1608.03440](https://arxiv.org/abs/1608.03440)

##### PDF
[https://arxiv.org/pdf/1608.03440](https://arxiv.org/pdf/1608.03440)

