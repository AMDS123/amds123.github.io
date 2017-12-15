---
layout: post
title: "DyNet: The Dynamic Neural Network Toolkit"
date: 2017-01-15 01:53:23
categories: arXiv_SD
tags: arXiv_SD
author: Graham Neubig, Chris Dyer, Yoav Goldberg, Austin Matthews, Waleed Ammar, Antonios Anastasopoulos, Miguel Ballesteros, David Chiang, Daniel Clothiaux, Trevor Cohn, Kevin Duh, Manaal Faruqui, Cynthia Gan, Dan Garrette, Yangfeng Ji, Lingpeng Kong, Adhiguna Kuncoro, Gaurav Kumar, Chaitanya Malaviya, Paul Michel, Yusuke Oda, Matthew Richardson, Naomi Saphra, Swabha Swayamdipta, Pengcheng Yin
mathjax: true
---

* content
{:toc}

##### Abstract
We describe DyNet, a toolkit for implementing neural network models based on dynamic declaration of network structure. In the static declaration strategy that is used in toolkits like Theano, CNTK, and TensorFlow, the user first defines a computation graph (a symbolic representation of the computation), and then examples are fed into an engine that executes this computation and computes its derivatives. In DyNet's dynamic declaration strategy, computation graph construction is mostly transparent, being implicitly constructed by executing procedural code that computes the network outputs, and the user is free to use different network structures for each input. Dynamic declaration thus facilitates the implementation of more complicated network architectures, and DyNet is specifically designed to allow users to implement their models in a way that is idiomatic in their preferred programming language (C++ or Python). One challenge with dynamic declaration is that because the symbolic computation graph is defined anew for every training example, its construction must have low overhead. To achieve this, DyNet has an optimized C++ backend and lightweight graph representation. Experiments show that DyNet's speeds are faster than or comparable with static declaration toolkits, and significantly faster than Chainer, another dynamic declaration toolkit. DyNet is released open-source under the Apache 2.0 license and available at this http URL

##### Abstract (translated by Google)
我们描述DyNet，一个基于网络结构的动态声明实现神经网络模型的工具包。在Theano，CNTK和TensorFlow等工具包中使用的静态声明策略中，用户首先定义一个计算图（计算的符号表示），然后将实例馈送到执行该计算并计算其导数的引擎。在DyNet的动态声明策略中，计算图结构大多是透明的，通过执行计算网络输出的程序代码隐式构造，用户可以自由地为每个输入使用不同的网络结构。因此，动态声明有助于实现更复杂的网络体系结构，而DyNet专门设计为允许用户以他们喜欢的编程语言（C ++或Python）惯用的方式实现他们的模型。动态声明的一个挑战是，因为符号计算图是每个训练样例重新定义的，所以它的构造必须具有低开销。为了达到这个目的，DyNet有一个优化的C ++后端和轻量级的图形表示。实验表明，DyNet的速度比静态声明工具包的速度更快，或者比静态声明工具包可比，并且比另一个动态声明工具包Chainer快得多。 DyNet是在Apache 2.0许可下发布的开放源代码，可在此http URL处获得

##### URL
[https://arxiv.org/abs/1701.03980](https://arxiv.org/abs/1701.03980)

##### PDF
[https://arxiv.org/pdf/1701.03980](https://arxiv.org/pdf/1701.03980)

