---
layout: post
title: "Structured Receptive Fields in CNNs"
date: 2016-05-13 11:56:08
categories: arXiv_CV
tags: arXiv_CV Classification
author: Jörn-Henrik Jacobsen, Jan van Gemert, Zhongyu Lou, Arnold W. M. Smeulders
mathjax: true
---

* content
{:toc}

##### Abstract
Learning powerful feature representations with CNNs is hard when training data are limited. Pre-training is one way to overcome this, but it requires large datasets sufficiently similar to the target domain. Another option is to design priors into the model, which can range from tuned hyperparameters to fully engineered representations like Scattering Networks. We combine these ideas into structured receptive field networks, a model which has a fixed filter basis and yet retains the flexibility of CNNs. This flexibility is achieved by expressing receptive fields in CNNs as a weighted sum over a fixed basis which is similar in spirit to Scattering Networks. The key difference is that we learn arbitrary effective filter sets from the basis rather than modeling the filters. This approach explicitly connects classical multiscale image analysis with general CNNs. With structured receptive field networks, we improve considerably over unstructured CNNs for small and medium dataset scenarios as well as over Scattering for large datasets. We validate our findings on ILSVRC2012, Cifar-10, Cifar-100 and MNIST. As a realistic small dataset example, we show state-of-the-art classification results on popular 3D MRI brain-disease datasets where pre-training is difficult due to a lack of large public datasets in a similar domain.

##### Abstract (translated by Google)
在训练数据有限的情况下，用CNN学习强大的特征表示是困难的。预训练是克服这一问题的一种方法，但是它需要与目标领域足够相似的大型数据集。另一种选择是在模型中设计先验模型，其范围可以从调整的超参数到完全设计的表示（如散射网络）。我们将这些想法结合到结构化的接受性现场网络中，这个模型具有固定的滤波器基础，并保留了CNN的灵活性。这种灵活性是通过将CNN中的接受域表示为在固定基础上的加权总和来实现的，这与精神上与散布网络类似。关键的区别在于，我们从基础上学习任意有效的滤波器组，而不是对滤波器进行建模。这种方法明确地将经典的多尺度图像分析与一般的CNN连接起来。利用结构化的接受现场网络，我们相对于非结构化的CNN，针对中小型数据集情况以及针对大型数据集的散乱情况，大大改进。我们验证了我们在ILSVRC2012，Cifar-10，Cifar-100和MNIST上的发现。作为一个现实的小型数据集的例子，我们展示了流行的3D MRI脑病数据集的最先进的分类结果，由于在类似的领域缺乏大型的公共数据集，预训练是困难的。

##### URL
[https://arxiv.org/abs/1605.02971](https://arxiv.org/abs/1605.02971)

##### PDF
[https://arxiv.org/pdf/1605.02971](https://arxiv.org/pdf/1605.02971)

