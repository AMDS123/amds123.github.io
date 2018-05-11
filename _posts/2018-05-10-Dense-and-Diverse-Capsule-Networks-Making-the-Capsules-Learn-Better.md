---
layout: post
title: "Dense and Diverse Capsule Networks: Making the Capsules Learn Better"
date: 2018-05-10 14:29:17
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification Deep_Learning Recognition
author: Sai Samarth R Phaye, Apoorva Sikka, Abhinav Dhall, Deepti Bathula
mathjax: true
---

* content
{:toc}

##### Abstract
Past few years have witnessed exponential growth of interest in deep learning methodologies with rapidly improving accuracies and reduced computational complexity. In particular, architectures using Convolutional Neural Networks (CNNs) have produced state-of-the-art performances for image classification and object recognition tasks. Recently, Capsule Networks (CapsNet) achieved significant increase in performance by addressing an inherent limitation of CNNs in encoding pose and deformation. Inspired by such advancement, we asked ourselves, can we do better? We propose Dense Capsule Networks (DCNet) and Diverse Capsule Networks (DCNet++). The two proposed frameworks customize the CapsNet by replacing the standard convolutional layers with densely connected convolutions. This helps in incorporating feature maps learned by different layers in forming the primary capsules. DCNet, essentially adds a deeper convolution network, which leads to learning of discriminative feature maps. Additionally, DCNet++ uses a hierarchical architecture to learn capsules that represent spatial information in a fine-to-coarser manner, which makes it more efficient for learning complex data. Experiments on image classification task using benchmark datasets demonstrate the efficacy of the proposed architectures. DCNet achieves state-of-the-art performance (99.75%) on MNIST dataset with twenty fold decrease in total training iterations, over the conventional CapsNet. Furthermore, DCNet++ performs better than CapsNet on SVHN dataset (96.90%), and outperforms the ensemble of seven CapsNet models on CIFAR-10 by 0.31% with seven fold decrease in number of parameters.

##### Abstract (translated by Google)
过去几年，深度学习方法的兴趣呈指数级增长，精确度迅速提高，计算复杂度降低。具体而言，使用卷积神经网络（CNN）的体系结构已经为图像分类和目标识别任务提供了最先进的性能。最近，Capsule Networks（CapsNet）通过解决CNN在编码姿势和变形方面固有的局限性，实现了显着的性能提升。受这种进步的启发，我们问自己，我们能做得更好吗？我们提出密集胶囊网络（DCNet）和多种胶囊网络（DCNet ++）。这两个提议的框架通过用密集连接的卷积替换标准卷积层来定制CapsNet。这有助于合并由不同层学习的特征图形成主胶囊。 DCNet基本上增加了一个更深的卷积网络，这导致了对差别特征映射的学习。此外，DCNet ++使用分层体系结构来学习以精细到粗糙的方式表示空间信息的胶囊，这使得它更有效地学习复杂数据。使用基准数据集进行的图像分类任务实验证明了所提出的体系结构的功效。 DCNet在MNIST数据集上实现了最先进的性能（99.75％），与传统的CapsNet相比，总训练迭代减少了20倍。此外，DCNet ++在SVHN数据集上的性能优于CapsNet（96.90％），并且在CIFAR-10上的七个CapsNet模型的集合优于0.31％，参数数量减少了七倍。

##### URL
[http://arxiv.org/abs/1805.04001](http://arxiv.org/abs/1805.04001)

##### PDF
[http://arxiv.org/pdf/1805.04001](http://arxiv.org/pdf/1805.04001)

