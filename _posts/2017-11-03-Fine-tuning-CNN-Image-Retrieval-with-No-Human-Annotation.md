---
layout: post
title: "Fine-tuning CNN Image Retrieval with No Human Annotation"
date: 2017-11-03 21:29:55
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval CNN
author: Filip Radenović, Giorgos Tolias, Ondřej Chum
mathjax: true
---

* content
{:toc}

##### Abstract
Image descriptors based on activations of Convolutional Neural Networks (CNNs) have become dominant in image retrieval due to their discriminative power, compactness of the representation, and the efficiency of search. Training of CNNs, either from scratch or fine-tuning, requires a large amount of annotated data, where high quality of the annotation is often crucial. In this work, we propose to fine-tune CNNs for image retrieval on a large collection of unordered images in a fully automatic manner. Reconstructed 3D models, obtained by the state-of-the-art retrieval and structure-from-motion methods, guide the selection of the training data. We show that both hard positive and hard negative examples, selected by exploiting the geometry and the camera positions available from the 3D models, enhance the performance in particular object retrieval. CNN descriptor whitening discriminatively learned from the same training data outperforms the commonly used PCA whitening. We propose a novel trainable Generalized-Mean (GeM) pooling layer that generalizes max and average pooling and show that it boosts retrieval performance. Applying the proposed method on VGG network achieves state-of-the-art performance on standard benchmarks: Oxford Buildings, Paris, and Holidays datasets.

##### Abstract (translated by Google)
基于卷积神经网络（CNN）激活的图像描述符由于其区分能力，表示的紧凑性和搜索的效率而在图像检索中占据主导地位。 CNN的培训无论是从头开始还是微调，都需要大量的注释数据，高质量的注释往往是至关重要的。在这项工作中，我们建议微调CNN在大量无序图像上以全自动方式进行图像检索。通过最先进的检索和运动结构方法获得的重建三维模型指导了训练数据的选择。我们显示，通过利用三维模型中可用的几何图形和相机位置来选择硬正面和负面的负面例子，可以提高特定对象检索的性能。从相同的训练数据有差别地学习的CNN描述符白化优于常用的PCA白化。我们提出了一种新颖的可训练的广义均值（GeM）汇聚层，它将最大值和平均汇聚概括起来，并显示它提高了检索性能。在VGG网络中应用所提出的方法，在标准基准上达到了最先进的性能：牛津大学，巴黎和假日数据集。

##### URL
[https://arxiv.org/abs/1711.02512](https://arxiv.org/abs/1711.02512)

##### PDF
[https://arxiv.org/pdf/1711.02512](https://arxiv.org/pdf/1711.02512)

