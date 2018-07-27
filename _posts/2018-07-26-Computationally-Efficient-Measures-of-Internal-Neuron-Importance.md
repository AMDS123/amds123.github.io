---
layout: post
title: "Computationally Efficient Measures of Internal Neuron Importance"
date: 2018-07-26 03:47:45
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Avanti Shrikumar, Jocelin Su, Anshul Kundaje
mathjax: true
---

* content
{:toc}

##### Abstract
The challenge of assigning importance to individual neurons in a network is of interest when interpreting deep learning models. In recent work, Dhamdhere et al. proposed Total Conductance, a "natural refinement of Integrated Gradients" for attributing importance to internal neurons. Unfortunately, the authors found that calculating conductance in tensorflow required the addition of several custom gradient operators and did not scale well. In this work, we show that the formula for Total Conductance is mathematically equivalent to Path Integrated Gradients computed on a hidden layer in the network. We provide a scalable implementation of Total Conductance using standard tensorflow gradient operators that we call Neuron Integrated Gradients. We compare Neuron Integrated Gradients to DeepLIFT, a pre-existing computationally efficient approach that is applicable to calculating internal neuron importance. We find that DeepLIFT produces strong empirical results and is faster to compute, but because it lacks the theoretical properties of Neuron Integrated Gradients, it may not always be preferred in practice. Colab notebook reproducing results: <a href="http://bit.ly/neuronintegratedgradients">this http URL</a>

##### Abstract (translated by Google)
在解释深度学习模型时，将重要性分配给网络中的个体神经元是有意义的。在最近的工作中，Dhamdhere等人。提出Total Conductance，一种“综合梯度的自然精炼”，用于归因于内部神经元的重要性。不幸的是，作者发现计算张量流中的电导需要添加几个自定义梯度算子，并且不能很好地扩展。在这项工作中，我们表明Total Conductance的公式在数学上等同于在网络中的隐藏层上计算的Path Integrated Gradients。我们使用标准张量流梯度算子提供可扩展的总电导实现，我们将其称为Neuron Integrated Gradients。我们将Neuron Integrated Gradients与DeepLIFT进行比较，DeepLIFT是一种预先存在的计算有效方法，适用于计算内部神经元的重要性。我们发现DeepLIFT产生了强大的经验结果并且计算速度更快，但由于它缺乏Neuron Integrated Gradients的理论属性，因此在实践中可能并不总是优先考虑。 Colab笔记本复制结果：<a href="http://bit.ly/neuronintegratedgradients">此http网址</a>

##### URL
[http://arxiv.org/abs/1807.09946](http://arxiv.org/abs/1807.09946)

##### PDF
[http://arxiv.org/pdf/1807.09946](http://arxiv.org/pdf/1807.09946)

