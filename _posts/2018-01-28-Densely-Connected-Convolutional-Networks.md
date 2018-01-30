---
layout: post
title: "Densely Connected Convolutional Networks"
date: 2018-01-28 17:12:02
categories: arXiv_CV
tags: arXiv_CV CNN Recognition
author: Gao Huang, Zhuang Liu, Laurens van der Maaten, Kilian Q. Weinberger
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work has shown that convolutional networks can be substantially deeper, more accurate, and efficient to train if they contain shorter connections between layers close to the input and those close to the output. In this paper, we embrace this observation and introduce the Dense Convolutional Network (DenseNet), which connects each layer to every other layer in a feed-forward fashion. Whereas traditional convolutional networks with L layers have L connections - one between each layer and its subsequent layer - our network has L(L+1)/2 direct connections. For each layer, the feature-maps of all preceding layers are used as inputs, and its own feature-maps are used as inputs into all subsequent layers. DenseNets have several compelling advantages: they alleviate the vanishing-gradient problem, strengthen feature propagation, encourage feature reuse, and substantially reduce the number of parameters. We evaluate our proposed architecture on four highly competitive object recognition benchmark tasks (CIFAR-10, CIFAR-100, SVHN, and ImageNet). DenseNets obtain significant improvements over the state-of-the-art on most of them, whilst requiring less computation to achieve high performance. Code and pre-trained models are available at https://github.com/liuzhuang13/DenseNet .

##### Abstract (translated by Google)
最近的工作表明，如果卷积网络包含接近输入的层和接近输出的层之间的较短连接，则卷积网络可以更深，更精确和有效地进行训练。在本文中，我们接受这一观察并引入密集卷积网络（DenseNet），它以前馈的方式将每层连接到每一层。而具有L层的传统卷积网络具有L个连接 - 每个层与其后一个层之间 - 我们的网络具有L（L + 1）/ 2个直接连接。对于每一层，前面所有层的特征映射被用作输入，并且它自己的特征映射被用作所有后续层的输入。 DenseNets有几个引人注目的优点：减轻消失梯度问题，加强特征传播，鼓励特征重用，大幅减少参数数量。我们评估了我们提出的四种高度竞争对象识别基准任务（CIFAR-10，CIFAR-100，SVHN和ImageNet）的架构。 DenseNets对其中大部分技术进行了大量的改进，同时需要较少的计算来实现高性能。代码和预先训练好的模型可以在https://github.com/liuzhuang13/DenseNet上找到。

##### URL
[http://arxiv.org/abs/1608.06993](http://arxiv.org/abs/1608.06993)

##### PDF
[http://arxiv.org/pdf/1608.06993](http://arxiv.org/pdf/1608.06993)

