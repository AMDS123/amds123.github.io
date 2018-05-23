---
layout: post
title: "A Simple Cache Model for Image Recognition"
date: 2018-05-21 17:50:14
categories: arXiv_CV
tags: arXiv_CV Adversarial Classification Language_Model Recognition
author: A. Emin Orhan
mathjax: true
---

* content
{:toc}

##### Abstract
Training large-scale image recognition models is computationally expensive. This raises the question of whether there might be simple ways to improve the test performance of an already trained model without having to re-train or even fine-tune it with new data. Here, we show that, surprisingly, this is indeed possible. The key observation we make is that the layers of a deep network close to the output layer contain independent, easily extractable class-relevant information that is not contained in the output layer itself. We propose to extract this extra class-relevant information using a simple key-value cache memory to improve the classification performance of the model at test time. Our cache memory is directly inspired by a similar cache model previously proposed for language modeling (Grave et al., 2017). This cache component does not require any training or fine-tuning; it can be applied to any pre-trained model and, by properly setting only two hyper-parameters, leads to significant improvements in its classification performance. Improvements are observed across several architectures and datasets. In the cache component, using features extracted from layers close to the output (but not from the output layer itself) as keys leads to the largest improvements. Concatenating features from multiple layers to form keys can further improve performance over using single-layer features as keys. The cache component also has a regularizing effect, a simple consequence of which is that it substantially increases the robustness of models against adversarial attacks.

##### Abstract (translated by Google)
训练大规模图像识别模型在计算上是昂贵的。这就产生了一个问题：是否可能有简单的方法来改进已经训练过的模型的测试性能，而不必对新数据进行重新训练甚至微调。在这里，我们表现出奇的是，这确实是可能的。我们所做的关键观察是，靠近输出层的深层网络层包含独立的，易于提取的类相关信息，这些信息不包含在输出层本身中。我们建议使用简单的键值缓存来提取这些额外的类相关信息，以提高模型在测试时的分类性能。我们的缓存内存直接受到以前为语言建模提出的类似缓存模型的启发（Grave等，2017）。这个缓存组件不需要任何培训或微调;它可以应用于任何预先训练的模型，并且通过恰当地设置两个超参数，可以显着提高分类性能。在几个体系结构和数据集中观察到了改进。在高速缓存组件中，使用从靠近输出（但不是从输出层本身）层提取的特征作为关键字可以实现最大的改进。连接多个图层的特征以形成密钥可以进一步提高使用单层特征作为密钥的性能。高速缓存组件也具有正则化效果，其简单的结果是它显着提高了模型对敌对攻击的稳健性。

##### URL
[https://arxiv.org/abs/1805.08709](https://arxiv.org/abs/1805.08709)

##### PDF
[https://arxiv.org/pdf/1805.08709](https://arxiv.org/pdf/1805.08709)

