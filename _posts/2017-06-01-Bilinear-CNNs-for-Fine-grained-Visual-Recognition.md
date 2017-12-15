---
layout: post
title: "Bilinear CNNs for Fine-grained Visual Recognition"
date: 2017-06-01 04:24:01
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification Recognition
author: Tsung-Yu Lin, Aruni RoyChowdhury, Subhransu Maji
mathjax: true
---

* content
{:toc}

##### Abstract
We present a simple and effective architecture for fine-grained visual recognition called Bilinear Convolutional Neural Networks (B-CNNs). These networks represent an image as a pooled outer product of features derived from two CNNs and capture localized feature interactions in a translationally invariant manner. B-CNNs belong to the class of orderless texture representations but unlike prior work they can be trained in an end-to-end manner. Our most accurate model obtains 84.1%, 79.4%, 86.9% and 91.3% per-image accuracy on the Caltech-UCSD birds [67], NABirds [64], FGVC aircraft [42], and Stanford cars [33] dataset respectively and runs at 30 frames-per-second on a NVIDIA Titan X GPU. We then present a systematic analysis of these networks and show that (1) the bilinear features are highly redundant and can be reduced by an order of magnitude in size without significant loss in accuracy, (2) are also effective for other image classification tasks such as texture and scene recognition, and (3) can be trained from scratch on the ImageNet dataset offering consistent improvements over the baseline architecture. Finally, we present visualizations of these models on various datasets using top activations of neural units and gradient-based inversion techniques. The source code for the complete system is available at this http URL

##### Abstract (translated by Google)
我们提出了一种简单有效的称为双线性卷积神经网络（B-CNN）的细粒度视觉识别体系结构。这些网络将图像表示为来自两个CNN的特征的汇集外部产品，并以平移不变的方式捕捉局部特征交互。 B-CNN属于无序纹理表示类，但与以前的工作不同，它们可以以端对端的方式进行训练。我们最精确的模型分别在Caltech-UCSD鸟类[67]，NABirds [64]，FGVC飞机[42]和斯坦福汽车[33]数据集上分别获得了84.1％，79.4％，86.9％和91.3％在NVIDIA Titan X GPU上以每秒30帧的速度运行。然后我们对这些网络进行系统的分析，结果表明：（1）双线性特征是高度冗余的，可以减小一个数量级而不会明显降低精度;（2）对于其他图像分类任务也是有效的作为纹理和场景识别，（3）可以从头开始对ImageNet数据集进行训练，从而在基线架构上提供一致的改进。最后，我们使用神经单元的最高激活和基于梯度的反演技术在各种数据集上呈现这些模型的可视化。整个系统的源代码可以在这个http URL中找到

##### URL
[https://arxiv.org/abs/1504.07889](https://arxiv.org/abs/1504.07889)

##### PDF
[https://arxiv.org/pdf/1504.07889](https://arxiv.org/pdf/1504.07889)

