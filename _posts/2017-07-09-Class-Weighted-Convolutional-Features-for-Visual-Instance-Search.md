---
layout: post
title: "Class-Weighted Convolutional Features for Visual Instance Search"
date: 2017-07-09 13:51:45
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Knowledge CNN Image_Classification Classification
author: Albert Jimenez, Jose M. Alvarez, Xavier Giro-i-Nieto
mathjax: true
---

* content
{:toc}

##### Abstract
Image retrieval in realistic scenarios targets large dynamic datasets of unlabeled images. In these cases, training or fine-tuning a model every time new images are added to the database is neither efficient nor scalable. Convolutional neural networks trained for image classification over large datasets have been proven effective feature extractors for image retrieval. The most successful approaches are based on encoding the activations of convolutional layers, as they convey the image spatial information. In this paper, we go beyond this spatial information and propose a local-aware encoding of convolutional features based on semantic information predicted in the target image. To this end, we obtain the most discriminative regions of an image using Class Activation Maps (CAMs). CAMs are based on the knowledge contained in the network and therefore, our approach, has the additional advantage of not requiring external information. In addition, we use CAMs to generate object proposals during an unsupervised re-ranking stage after a first fast search. Our experiments on two public available datasets for instance retrieval, Oxford5k and Paris6k, demonstrate the competitiveness of our approach outperforming the current state-of-the-art when using off-the-shelf models trained on ImageNet. The source code and model used in this paper are publicly available at this http URL

##### Abstract (translated by Google)
实际场景中的图像检索针对未标记图像的大动态数据集。在这些情况下，每次将新图像添加到数据库时对模型进行训练或微调既不高效，也不可扩展。在大型数据集上训练用于图像分类的卷积神经网络已被证明是用于图像检索的有效特征提取器。最成功的方法是基于编码卷积层的激活，因为它们传达图像的空间信息。在本文中，我们超越了这个空间信息，提出了一种基于目标图像中预测的语义信息的卷积特征的局部感知编码。为此，我们使用类激活映射（CAM）获得图像的最具区分性的区域。 CAM基于网络中包含的知识，因此，我们的方法具有不需要外部信息的附加优点。另外，在第一次快速搜索之后，我们使用CAM在无监督的重新排序阶段生成对象提议。我们在两个公开可用的数据集（例如Oxford5k和Paris6k）上进行的实验证明，当使用在ImageNet上训练的现成模型时，我们的方法的竞争力超越了当前最先进的技术。本文使用的源代码和模型可在此http URL公开获得

##### URL
[https://arxiv.org/abs/1707.02581](https://arxiv.org/abs/1707.02581)

##### PDF
[https://arxiv.org/pdf/1707.02581](https://arxiv.org/pdf/1707.02581)

