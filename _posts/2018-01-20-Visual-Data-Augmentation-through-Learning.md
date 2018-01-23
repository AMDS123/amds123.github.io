---
layout: post
title: "Visual Data Augmentation through Learning"
date: 2018-01-20 12:08:59
categories: arXiv_CV
tags: arXiv_CV Quantitative
author: Grigorios G. Chrysos, Yannis Panagakis, Stefanos Zafeiriou
mathjax: true
---

* content
{:toc}

##### Abstract
The rapid progress in machine learning methods has been empowered by i) huge datasets that have been collected and annotated, ii) improved engineering (e.g. data pre-processing/normalization). The existing datasets typically include several million samples, which constitutes their extension a colossal task. In addition, the state-of-the-art data-driven methods demand a vast amount of data, hence a standard engineering trick employed is artificial data augmentation for instance by adding into the data cropped and (affinely) transformed images. However, this approach does not correspond to any change in the natural 3D scene. We propose instead to perform data augmentation through learning realistic local transformations. We learn a forward and an inverse transformation that maps an image from the high-dimensional space of pixel intensities to a latent space which varies (approximately) linearly with the latent space of a realistically transformed version of the image. Such transformed images can be considered two successive frames in a video. Next, we utilize these transformations to learn a linear model that modifies the latent spaces and then use the inverse transformation to synthesize a new image. We argue that the this procedure produces powerful invariant representations. We perform both qualitative and quantitative experiments that demonstrate our proposed method creates new realistic images.

##### Abstract (translated by Google)
机器学习方法的快速发展已经通过i）已经收集和注释的大量数据集，ii）改进的工程（例如数据预处理/规范化）来赋予权力。现有的数据集通常包含数百万个样本，这构成了他们的扩展任务。此外，最先进的数据驱动方法需要大量的数据，因此所采用的标准工程技巧是例如通过在数据裁剪和（仿射）变换图像中添加仿真数据增强。但是，这种方法并不对应于自然3D场景的任何变化。我们建议通过学习现实的局部变换来执行数据增强。我们学习了一个正向和反向变换，它将图像从像素强度的高维空间映射到与现实变换版本的图像的潜在空间（近似）线性变化的潜在空间。这种变换的图像可以被认为是视频中的两个连续的帧。接下来，我们利用这些转换学习一个线性模型，修改潜在的空间，然后使用逆变换合成一个新的图像。我们认为这个过程产生了强大的不变表示。我们进行定性和定量实验，证明我们提出的方法创造新的现实的图像。

##### URL
[https://arxiv.org/abs/1801.06665](https://arxiv.org/abs/1801.06665)

##### PDF
[https://arxiv.org/pdf/1801.06665](https://arxiv.org/pdf/1801.06665)

