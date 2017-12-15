---
layout: post
title: "$k$-Nearest Neighbor Augmented Neural Networks for Text Classification"
date: 2017-08-25 19:04:25
categories: arXiv_CL
tags: arXiv_CL Text_Classification Embedding Transfer_Learning Classification Prediction
author: Zhiguo Wang, Wael Hamza, Linfeng Song
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, many deep-learning based models are proposed for text classification. This kind of models well fits the training set from the statistical point of view. However, it lacks the capacity of utilizing instance-level information from individual instances in the training set. In this work, we propose to enhance neural network models by allowing them to leverage information from $k$-nearest neighbor (kNN) of the input text. Our model employs a neural network that encodes texts into text embeddings. Moreover, we also utilize $k$-nearest neighbor of the input text as an external memory, and utilize it to capture instance-level information from the training set. The final prediction is made based on features from both the neural network encoder and the kNN memory. Experimental results on several standard benchmark datasets show that our model outperforms the baseline model on all the datasets, and it even beats a very deep neural network model (with 29 layers) in several datasets. Our model also shows superior performance when training instances are scarce, and when the training set is severely unbalanced. Our model also leverages techniques such as semi-supervised training and transfer learning quite well.

##### Abstract (translated by Google)
近年来，提出了许多基于深度学习的文本分类模型。从统计的角度来看，这种模型很适合训练集。然而，它缺乏利用训练集中个体实例的实例级信息的能力。在这项工作中，我们建议通过允许他们利用来自输入文本的$ k $  - 最近邻居（kNN）的信息来增强神经网络模型。我们的模型采用了一种将文本编码成文本嵌入的神经网络。而且，我们还利用输入文本的$ k $  - 最近邻居作为外部存储器，并利用它从训练集中捕获实例级信息。最后的预测是基于来自神经网络编码器和kNN存储器的特征进行的。在几个标准基准数据集上的实验结果表明，我们的模型在所有数据集上的表现都优于基线模型，甚至在几个数据集中击败了一个非常深的神经网络模型（有29层）。我们的模型在训练实例很少，训练集严重失衡的情况下也表现出优越的性能。我们的模型还利用半监督训练和转移学习等技巧。

##### URL
[https://arxiv.org/abs/1708.07863](https://arxiv.org/abs/1708.07863)

##### PDF
[https://arxiv.org/pdf/1708.07863](https://arxiv.org/pdf/1708.07863)

