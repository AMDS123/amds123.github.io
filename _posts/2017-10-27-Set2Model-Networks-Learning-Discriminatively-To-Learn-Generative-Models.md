---
layout: post
title: "Set2Model Networks: Learning Discriminatively To Learn Generative Models"
date: 2017-10-27 12:29:53
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Embedding
author: A. Vakhitov, A. Kuzmin, V. Lempitsky
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new "learning-to-learn"-type approach that enables rapid learning of concepts from small-to-medium sized training sets and is primarily designed for web-initialized image retrieval. At the core of our approach is a deep architecture (a Set2Model network) that maps sets of examples to simple generative probabilistic models such as Gaussians or mixtures of Gaussians in the space of high-dimensional descriptors. The parameters of the embedding into the descriptor space are trained in the end-to-end fashion in the meta-learning stage using a set of training learning problems. The main technical novelty of our approach is the derivation of the backprop process through the mixture model fitting, which makes the likelihood of the resulting models differentiable with respect to the positions of the input descriptors. While the meta-learning process for a Set2Model network is discriminative, a trained Set2Model network performs generative learning of generative models in the descriptor space, which facilitates learning in the cases when no negative examples are available, and whenever the concept being learned is polysemous or represented by noisy training sets. Among other experiments, we demonstrate that these properties allow Set2Model networks to pick visual concepts from the raw outputs of Internet image search engines better than a set of strong baselines.

##### Abstract (translated by Google)
我们提出了一种新的“学习学习型”方法，可以从中小型的训练集中快速学习概念，主要是为网络初始化图像检索而设计的。我们方法的核心是一个深层架构（一个Set2Model网络），它将一组示例映射到简单的生成概率模型，如高斯描述符空间中的高斯或高斯混合。嵌入到描述符空间中的参数在元学习阶段以端对端的方式使用一组训练学习问题进行训练。我们方法的主要技术新颖之处在于通过混合模型拟合来推导反向传播过程，这使得所得模型的可能性相对于输入描述符的位置是可区分的。尽管Set2Model网络的元学习过程是有区别的，但是训练有素的Set2Model网络在描述符空间中执行生成模型的生成学习，这有助于在没有负面例子的情况下进行学习，并且每当学习的概念是多义的或以嘈杂的训练集为代表。在其他的实验中，我们证明了这些属性允许Set2Model网络从互联网图像搜索引擎的原始输出中选择视觉概念，而不是一组强基线。

##### URL
[https://arxiv.org/abs/1612.07697](https://arxiv.org/abs/1612.07697)

##### PDF
[https://arxiv.org/pdf/1612.07697](https://arxiv.org/pdf/1612.07697)

