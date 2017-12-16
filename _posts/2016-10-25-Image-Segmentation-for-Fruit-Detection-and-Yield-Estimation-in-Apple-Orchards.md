---
layout: post
title: "Image Segmentation for Fruit Detection and Yield Estimation in Apple Orchards"
date: 2016-10-25 23:38:02
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Detection Relation
author: Suchet Bargoti, James Underwood
mathjax: true
---

* content
{:toc}

##### Abstract
Ground vehicles equipped with monocular vision systems are a valuable source of high resolution image data for precision agriculture applications in orchards. This paper presents an image processing framework for fruit detection and counting using orchard image data. A general purpose image segmentation approach is used, including two feature learning algorithms; multi-scale Multi-Layered Perceptrons (MLP) and Convolutional Neural Networks (CNN). These networks were extended by including contextual information about how the image data was captured (metadata), which correlates with some of the appearance variations and/or class distributions observed in the data. The pixel-wise fruit segmentation output is processed using the Watershed Segmentation (WS) and Circular Hough Transform (CHT) algorithms to detect and count individual fruits. Experiments were conducted in a commercial apple orchard near Melbourne, Australia. The results show an improvement in fruit segmentation performance with the inclusion of metadata on the previously benchmarked MLP network. We extend this work with CNNs, bringing agrovision closer to the state-of-the-art in computer vision, where although metadata had negligible influence, the best pixel-wise F1-score of $0.791$ was achieved. The WS algorithm produced the best apple detection and counting results, with a detection F1-score of $0.858$. As a final step, image fruit counts were accumulated over multiple rows at the orchard and compared against the post-harvest fruit counts that were obtained from a grading and counting machine. The count estimates using CNN and WS resulted in the best performance for this dataset, with a squared correlation coefficient of $r^2=0.826$.

##### Abstract (translated by Google)
配备单目视觉系统的地面车辆是果园精准农业应用的高分辨率图像数据的宝贵来源。本文提出了一种利用果园图像数据进行水果检测和计数的图像处理框架。采用通用图像分割方法，包括两种特征学习算法;多尺度多层感知器（MLP）和卷积神经网络（CNN）。这些网络通过包括关于如何捕获图像数据的上下文信息（元数据）来扩展，这与数据中观察到的一些外观变化和/或类分布相关。使用分水岭分割（WS）和圆形霍夫变换（CHT）算法来处理像素水果分割输出以检测和计数单个果实。实验在澳大利亚墨尔本附近的一个商业苹果园进行。结果表明，在以前基准的MLP网络中包含元数据后，水果分割性能得到了改善。我们将这一工作扩展到CNN，使农业视野更接近计算机视觉领域的最新水平，虽然元数据的影响可以忽略不计，但获得了0.791美元的最佳像素级F1分数。 WS算法产生了最好的苹果检测和计数结果，检测F1得分为0.858 $。作为最后一步，图像果实计数在果园的多行上累积，并与从分级和计数机器获得的收获后果实数量进行比较。使用CNN和WS的计数估计结果对于该数据集来说性能最好，平方相关系数为$ r ^ 2 = 0.826 $。

##### URL
[https://arxiv.org/abs/1610.08120](https://arxiv.org/abs/1610.08120)

##### PDF
[https://arxiv.org/pdf/1610.08120](https://arxiv.org/pdf/1610.08120)

