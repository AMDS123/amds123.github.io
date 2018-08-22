---
layout: post
title: "Class2Str: End to End Latent Hierarchy Learning"
date: 2018-08-20 19:58:35
categories: arXiv_AI
tags: arXiv_AI CNN Image_Classification Classification
author: Soham Saha, Girish Varma, C.V.Jawahar
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks for image classification typically consists of a convolutional feature extractor followed by a fully connected classifier network. The predicted and the ground truth labels are represented as one hot vectors. Such a representation assumes that all classes are equally dissimilar. However, classes have visual similarities and often form a hierarchy. Learning this latent hierarchy explicitly in the architecture could provide invaluable insights. We propose an alternate architecture to the classifier network called the Latent Hierarchy (LH) Classifier and an end to end learned Class2Str mapping which discovers a latent hierarchy of the classes. We show that for some of the best performing architectures on CIFAR and Imagenet datasets, the proposed replacement and training by LH classifier recovers the accuracy, with a fraction of the number of parameters in the classifier part. Compared to the previous work of HDCNN, which also learns a 2 level hierarchy, we are able to learn a hierarchy at an arbitrary number of levels as well as obtain an accuracy improvement on the Imagenet classification task over them. We also verify that many visually similar classes are grouped together, under the learnt hierarchy.

##### Abstract (translated by Google)
用于图像分类的深度神经网络通常由卷积特征提取器和完全连接的分类器网络组成。预测的和地面真实标签被表示为一个热矢量。这种表示假定所有类别都是不同的。但是，类具有视觉上的相似性，并且通常形成层次结构。在架构中明确地学习这个潜在的层次结构可以提供宝贵的见解。我们提出了一种称为Latent Hierarchy（LH）分类器的分类器网络的替代架构，以及端到端学习的Class2Str映射，它发现了类的潜在层次结构。我们展示了对于CIFAR和Imagenet数据集上的一些性能最佳的体系结构，LH分类器的建议替换和训练恢复了准确性，分类器部分中的参数数量的一小部分。与HDCNN的先前工作（也学习2级层次结构）相比，我们能够在任意数量的级别上学习层次结构，并获得对它们的Imagenet分类任务的准确性改进。我们还验证在学习的层次结构下，许多视觉上相似的类被组合在一起。

##### URL
[http://arxiv.org/abs/1808.06675](http://arxiv.org/abs/1808.06675)

##### PDF
[http://arxiv.org/pdf/1808.06675](http://arxiv.org/pdf/1808.06675)

