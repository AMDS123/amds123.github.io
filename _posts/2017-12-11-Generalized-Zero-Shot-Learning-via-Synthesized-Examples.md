---
layout: post
title: "Generalized Zero-Shot Learning via Synthesized Examples"
date: 2017-12-11 16:44:12
categories: arXiv_CV
tags: arXiv_CV Classification
author: Gundeep Arora, Vinay Kumar Verma, Ashish Mishra, Piyush Rai
mathjax: true
---

* content
{:toc}

##### Abstract
We present a generative framework for generalized zero-shot learning where the training and test classes are not necessarily disjoint. Built upon a variational autoencoder based architecture, consisting of a probabilistic encoder and a probabilistic conditional decoder, our model can generate novel exemplars from seen/unseen classes, given their respective class attributes. These exemplars can subsequently be used to train any off-the-shelf classification model. One of the key aspects of our encoder-decoder architecture is a feedback-driven mechanism in which a discriminator (a multivariate regressor) learns to map the generated exemplars to the corresponding class attribute vectors, leading to an improved generator. Our model's ability to generate and leverage examples from unseen classes to train the classification model naturally helps to mitigate the bias towards predicting seen classes in generalized zero-shot learning settings. Through a comprehensive set of experiments, we show that our model outperforms several state-of-the-art methods, on several benchmark datasets, for both standard as well as generalized zero-shot learning.

##### Abstract (translated by Google)
我们提出了一个广义零炮制学习的生成框架，其中训练和测试类不一定是不相交的。建立在由概率编码器和概率条件解码器组成的基于变化自编码器的体系结构上，我们的模型可以从看到/看不见的类生成新的示例，给出它们各自的类属性。随后可以使用这些示例来训练任何现成的分类模型。我们的编码器 - 解码器体系结构的关键方面之一是反馈驱动的机制，其中鉴别器（多变量回归器）学习将生成的范例映射到对应的类属性向量，导致改进的生成器。我们的模型能够生成和利用看不见的类的例子来训练分类模型，这自然有助于减轻在广义零点学习设置中预测可见类的偏见。通过一系列全面的实验，我们证明了我们的模型在几个基准数据集上，比标准以及广义零点学习，都优于几种最新的方法。

##### URL
[http://arxiv.org/abs/1712.03878](http://arxiv.org/abs/1712.03878)

##### PDF
[http://arxiv.org/pdf/1712.03878](http://arxiv.org/pdf/1712.03878)

