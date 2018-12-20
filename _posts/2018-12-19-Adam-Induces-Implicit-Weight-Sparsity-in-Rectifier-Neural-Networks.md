---
layout: post
title: "Adam Induces Implicit Weight Sparsity in Rectifier Neural Networks"
date: 2018-12-19 17:59:08
categories: arXiv_CV
tags: arXiv_CV Speech_Recognition Deep_Learning Recognition
author: Atsushi Yaguchi, Taiji Suzuki, Wataru Asano, Shuhei Nitta, Yukinobu Sakata, Akiyuki Tanizawa
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, deep neural networks (DNNs) have been applied to various machine leaning tasks, including image recognition, speech recognition, and machine translation. However, large DNN models are needed to achieve state-of-the-art performance, exceeding the capabilities of edge devices. Model reduction is thus needed for practical use. In this paper, we point out that deep learning automatically induces group sparsity of weights, in which all weights connected to an output channel (node) are zero, when training DNNs under the following three conditions: (1) rectified-linear-unit (ReLU) activations, (2) an $L_2$-regularized objective function, and (3) the Adam optimizer. Next, we analyze this behavior both theoretically and experimentally, and propose a simple model reduction method: eliminate the zero weights after training the DNN. In experiments on MNIST and CIFAR-10 datasets, we demonstrate the sparsity with various training setups. Finally, we show that our method can efficiently reduce the model size and performs well relative to methods that use a sparsity-inducing regularizer.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.08119](http://arxiv.org/abs/1812.08119)

##### PDF
[http://arxiv.org/pdf/1812.08119](http://arxiv.org/pdf/1812.08119)

