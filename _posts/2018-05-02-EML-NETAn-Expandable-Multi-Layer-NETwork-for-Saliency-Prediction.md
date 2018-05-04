---
layout: post
title: "EML-NET:An Expandable Multi-Layer NETwork for Saliency Prediction"
date: 2018-05-02 22:32:12
categories: arXiv_CV
tags: arXiv_CV Salient Knowledge CNN Prediction
author: Sen Jia
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we apply state-of-the-art Convolutional Neural Network(CNN) architectures for saliency prediction. Our results show that better saliency features can be delivered by a deeper CNN model. However, it is very space-consuming to apply a complex model due to the large size of input images. The space complexity becomes even more problematic when we extract features from multiple convolutional layers or different models. 
 In this paper, we propose a modular saliency system which aims at splitting the whole network into small modules. The main difference in our approach s that the encoder and decoder can be separately trained for the scalability. Furthermore, the encoder can contain more than one CNN model to extract features and the models can have different architectures or pre-trained on different datasets. This parallel design allows us to better utilize the computational space in order to apply more powerful encoder. More importantly, our network can be easily expanded almost without extra spaces, other pre-trained CNN models can be combined for a wider range of visual knowledge. We denote our expandable multi-layer network as EML-NET in this paper. Our method is evaluated on three public saliency benchmarks, SALICON, MIT300 and CAT2000. The proposed EML-NET achieves state-of-the-art results on the metric of Normalized Scanpath Saliency using a modified loss function.

##### Abstract (translated by Google)
在这项工作中，我们应用最先进的卷积神经网络（CNN）架构进行显着性预测。我们的结果表明，更深的CNN模型可以提供更好的显着特征。然而，由于输入图像的大尺寸，应用复杂模型非常耗费空间。当我们从多个卷积层或不同模型中提取特征时，空间复杂性变得更加棘手。
 在本文中，我们提出了一个模块化显着系统，其目的是将整个网络分解成小模块。我们的方法的主要区别是编码器和解码器可以分别进行可扩展性训练。此外，编码器可以包含多个CNN模型来提取特征，并且模型可以具有不同的体系结构或在不同的数据集上预先训练。这种并行设计使我们能够更好地利用计算空间，以便应用更强大的编码器。更重要的是，我们的网络可以很容易地扩展，几乎没有额外的空间，其他预先训练的CNN模型可以结合起来，以获得更广泛的视觉知识。本文将我们的可扩展多层网络表示为EML-NET。我们的方法在三个公共显着性基准SALICON，MIT300和CAT2000上评估。所提出的EML-NET使用修正的损失函数在标准化扫描路径显着性度量上实现了最新的结果。

##### URL
[http://arxiv.org/abs/1805.01047](http://arxiv.org/abs/1805.01047)

##### PDF
[http://arxiv.org/pdf/1805.01047](http://arxiv.org/pdf/1805.01047)

