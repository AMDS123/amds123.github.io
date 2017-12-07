---
layout: post
title: "Sparse Coding on Stereo Video for Object Detection"
date: 2017-11-30 21:41:55
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse CNN Image_Classification Classification Detection
author: Sheng Y. Lundquist, Melanie Mitchell, Garrett T. Kenyon
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Convolutional Neural Networks (DCNN) require millions of labeled training examples for image classification and object detection tasks, which restrict these models to domains where such datasets are available. In this paper, we explore the use of unsupervised sparse coding applied to stereo-video data to help alleviate the need for large amounts of labeled data. We show that replacing a typical supervised convolutional layer with an unsupervised sparse-coding layer within a DCNN allows for better performance on a car detection task when only a limited number of labeled training examples is available. Furthermore, the network that incorporates sparse coding allows for more consistent performance over varying initializations and ordering of training examples when compared to a fully supervised DCNN. Finally, we compare activations between the unsupervised sparse-coding layer and the supervised convolutional layer, and show that the sparse representation exhibits an encoding that is depth selective, whereas encodings from the convolutional layer do not exhibit such selectivity. These result indicates promise for using unsupervised sparse-coding approaches in real-world computer vision tasks in domains with limited labeled training data.

##### Abstract (translated by Google)
深度卷积神经网络（DCNN）需要数百万个标记的训练样例用于图像分类和对象检测任务，这些模型将这些模型限制在可获得这样的数据集的领域。在本文中，我们探讨了使用无监督稀疏编码应用于立体视频数据，以帮助缓解大量标记数据的需求。我们表明，在DCNN内用无监督的稀疏编码层替换典型的监督卷积层允许在仅有有限数量的标记训练示例可用时在车检测任务上获得更好的性能。此外，与完全监督的DCNN相比，包含稀疏编码的网络允许在变化的初始化和训练示例的排序方面更一致的性能。最后，我们比较了无监督稀疏编码层和有监督卷积层之间的激活，并且显示稀疏表示表现出深度选择性的编码，而来自卷积层的编码不表现出这样的选择性。这些结果表明使用无监督稀疏编码方法在具有有限标记训练数据的域中的真实世界计算机视觉任务中是有希望的。

##### URL
[https://arxiv.org/abs/1705.07144](https://arxiv.org/abs/1705.07144)

##### PDF
[https://arxiv.org/pdf/1705.07144](https://arxiv.org/pdf/1705.07144)

