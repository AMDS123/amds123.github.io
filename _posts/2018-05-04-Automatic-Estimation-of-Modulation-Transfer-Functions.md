---
layout: post
title: "Automatic Estimation of Modulation Transfer Functions"
date: 2018-05-04 17:36:41
categories: arXiv_CV
tags: arXiv_CV CNN
author: Matthias Bauer, Valentin Volchkov, Michael Hirsch, Bernhard Sch&#xf6;lkopf
mathjax: true
---

* content
{:toc}

##### Abstract
The modulation transfer function (MTF) is widely used to characterise the performance of optical systems. Measuring it is costly and it is thus rarely available for a given lens specimen. Instead, MTFs based on simulations or, at best, MTFs measured on other specimens of the same lens are used. Fortunately, images recorded through an optical system contain ample information about its MTF, only that it is confounded with the statistics of the images. This work presents a method to estimate the MTF of camera lens systems directly from photographs, without the need for expensive equipment. We use a custom grid display to accurately measure the point response of lenses to acquire ground truth training data. We then use the same lenses to record natural images and employ a data-driven supervised learning approach using a convolutional neural network to estimate the MTF on small image patches, aggregating the information into MTF charts over the entire field of view. It generalises to unseen lenses and can be applied for single photographs, with the performance improving if multiple photographs are available.

##### Abstract (translated by Google)
调制传递函数（MTF）广泛用于表征光学系统的性能。测量它是昂贵的，因此对于给定的镜片标本很少可用。相反，使用基于模拟的MTF或者最好使用在相同透镜的其他样本上测量的MTF。幸运的是，通过光学系统记录的图像包含有关其MTF的充足信息，只是它与图像的统计数据混淆。这项工作提供了一种直接从照片中估计相机镜头系统MTF的方法，而不需要昂贵的设备。我们使用定制的网格显示来精确测量镜头的点响应以获取地面实况训练数据。然后，我们使用相同的镜头记录自然图像，并采用数据驱动的监督式学习方法，使用卷积神经网络估计小图像片上的MTF，将信息汇总到整个视场中的MTF图表中。它概括为看不见的镜片，可以应用于单张照片，如果有多张照片，性能会得到改善。

##### URL
[http://arxiv.org/abs/1805.01872](http://arxiv.org/abs/1805.01872)

##### PDF
[http://arxiv.org/pdf/1805.01872](http://arxiv.org/pdf/1805.01872)

