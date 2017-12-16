---
layout: post
title: "Genetic CNN"
date: 2017-03-04 19:44:16
categories: arXiv_CV
tags: arXiv_CV CNN Recognition
author: Lingxi Xie, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
The deep Convolutional Neural Network (CNN) is the state-of-the-art solution for large-scale visual recognition. Following basic principles such as increasing the depth and constructing highway connections, researchers have manually designed a lot of fixed network structures and verified their effectiveness. In this paper, we discuss the possibility of learning deep network structures automatically. Note that the number of possible network structures increases exponentially with the number of layers in the network, which inspires us to adopt the genetic algorithm to efficiently traverse this large search space. We first propose an encoding method to represent each network structure in a fixed-length binary string, and initialize the genetic algorithm by generating a set of randomized individuals. In each generation, we define standard genetic operations, e.g., selection, mutation and crossover, to eliminate weak individuals and then generate more competitive ones. The competitiveness of each individual is defined as its recognition accuracy, which is obtained via training the network from scratch and evaluating it on a validation set. We run the genetic process on two small datasets, i.e., MNIST and CIFAR10, demonstrating its ability to evolve and find high-quality structures which are little studied before. These structures are also transferrable to the large-scale ILSVRC2012 dataset.

##### Abstract (translated by Google)
深度卷积神经网络（CNN）是用于大规模视觉识别的最先进的解决方案。研究人员根据增加深度和建设高速公路连接等基本原则手动设计了大量的固定网络结构并验证了其有效性。在本文中，我们讨论自动学习深层网络结构的可能性。请注意，可能的网络结构的数量随着网络层数的增加呈指数增长，这激励我们采用遗传算法来高效地遍历这个大的搜索空间。我们首先提出一种用固定长度的二进制串表示每个网络结构的编码方法，并通过生成一组随机化的个体来初始化遗传算法。在每一代，我们定义标准的遗传操作，例如选择，变异和交叉，消除弱个体，然后生成更具竞争力的个体。每个人的竞争力被定义为其识别准确性，这是通过从头开始训练网络并在验证集上进行评估而获得的。我们在两个小数据集（即MNIST和CIFAR10）上运行遗传过程，展示了它的进化能力，并找到以前很少研究的高质量结构。这些结构也可以转移到大规模的ILSVRC2012数据集。

##### URL
[https://arxiv.org/abs/1703.01513](https://arxiv.org/abs/1703.01513)

##### PDF
[https://arxiv.org/pdf/1703.01513](https://arxiv.org/pdf/1703.01513)

