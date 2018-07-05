---
layout: post
title: "TextSnake: A Flexible Representation for Detecting Text of Arbitrary Shapes"
date: 2018-07-04 12:37:07
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Shangbang Long, Jiaqiang Ruan, Wenjie Zhang, Xin He, Wenhao Wu, Cong Yao
mathjax: true
---

* content
{:toc}

##### Abstract
Driven by deep neural networks and large scale datasets, scene text detection methods have progressed substantially over the past years, continuously refreshing the performance records on various standard benchmarks. However, limited by the representations (axis-aligned rectangles, rotated rectangles or quadrangles) adopted to describe text, existing methods may fall short when dealing with much more free-form text instances, such as curved text, which are actually very common in real-world scenarios. To tackle this problem, we propose a more flexible representation for scene text, termed as TextSnake, which is able to effectively represent text instances in horizontal, oriented and curved forms. In TextSnake, a text instance is described as a sequence of ordered, overlapping disks centered at symmetric axes, each of which is associated with potentially variable radius and orientation. Such geometry attributes are estimated via a Fully Convolutional Network (FCN) model. In experiments, the text detector based on TextSnake achieves state-of-the-art or comparable performance on Total-Text and SCUT-CTW1500, the two newly published benchmarks with special emphasis on curved text in natural images, as well as the widely-used datasets ICDAR 2015 and MSRA-TD500. Specifically, TextSnake outperforms the baseline on Total-Text by more than 40% in F-measure.

##### Abstract (translated by Google)
在深度神经网络和大规模数据集的推动下，场景文本检测方法在过去几年中取得了长足进步，不断刷新各种标准基准的性能记录。但是，受到用于描述文本的表示（轴对齐矩形，旋转矩形或四边形）的限制，现有方法在处理更多自由格式文本实例时可能会失败，例如弯曲文本，这在实际中非常常见。 - 世界场景。为了解决这个问题，我们提出了一种更灵活的场景文本表示，称为TextSnake，它能够有效地表示水平，定向和弯曲形式的文本实例。在TextSnake中，文本实例被描述为以对称轴为中心的有序重叠磁盘序列，每个磁盘与可能变化的半径和方向相关联。通过完全卷积网络（FCN）模型估计这种几何属性。在实验中，基于TextSnake的文本检测器在Total-Text和SCUT-CTW1500上实现了最先进或相当的性能，这是两个新发布的基准，特别强调自然图像中的弯曲文本，以及广泛的使用的数据集ICDAR 2015和MSRA-TD500。具体来说，TextSnake在F-measure中的总文本基线优于40％。

##### URL
[http://arxiv.org/abs/1807.01544](http://arxiv.org/abs/1807.01544)

##### PDF
[http://arxiv.org/pdf/1807.01544](http://arxiv.org/pdf/1807.01544)

