---
layout: post
title: "Generative learning for deep networks"
date: 2017-09-25 14:43:53
categories: arXiv_CV
tags: arXiv_CV Inference Recognition
author: Boris Flach, Alexander Shekhovtsov, Ondrej Fikar
mathjax: true
---

* content
{:toc}

##### Abstract
Learning, taking into account full distribution of the data, referred to as generative, is not feasible with deep neural networks (DNNs) because they model only the conditional distribution of the outputs given the inputs. Current solutions are either based on joint probability models facing difficult estimation problems or learn two separate networks, mapping inputs to outputs (recognition) and vice-versa (generation). We propose an intermediate approach. First, we show that forward computation in DNNs with logistic sigmoid activations corresponds to a simplified approximate Bayesian inference in a directed probabilistic multi-layer model. This connection allows to interpret DNN as a probabilistic model of the output and all hidden units given the input. Second, we propose that in order for the recognition and generation networks to be more consistent with the joint model of the data, weights of the recognition and generator network should be related by transposition. We demonstrate in a tentative experiment that such a coupled pair can be learned generatively, modelling the full distribution of the data, and has enough capacity to perform well in both recognition and generation.

##### Abstract (translated by Google)
学习，考虑到数据的完整分布，被称为生成的，对深度神经网络（DNNs）来说是不可行的，因为它们只给出输入的输出的条件分布。当前的解决方案要么基于联合概率模型面临困难的估计问题，要么学习两个单独的网络，将输入映射到输出（识别），反之亦然（生成）。我们提出一个中间的方法。首先，我们证明了在具有logistic sigmoid激活的DNNs中的正向计算对应于在有向概率多层模型中的简化的近似贝叶斯推断。这种连接允许将DNN解释为输出的概率模型以及给定输入的所有隐藏单元。其次，为了使识别和生成网络与数据的联合模型更加一致，识别和生成器网络的权重应该通过转置相关联。我们在一个试验性的实验中证明，这种耦合对可以被有效地学习，模拟数据的全部分布，并且有足够的容量在识别和生成中表现良好。

##### URL
[https://arxiv.org/abs/1709.08524](https://arxiv.org/abs/1709.08524)

##### PDF
[https://arxiv.org/pdf/1709.08524](https://arxiv.org/pdf/1709.08524)

