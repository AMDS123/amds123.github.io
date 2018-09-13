---
layout: post
title: "Discovering Low-Precision Networks Close to Full-Precision Networks for Efficient Embedded Inference"
date: 2018-09-11 22:51:55
categories: arXiv_CV
tags: arXiv_CV Inference Classification Gradient_Descent
author: Jeffrey L. McKinstry, Steven K. Esser, Rathinakumar Appuswamy, Deepika Bablani, John V. Arthur, Izzet B. Yildiz, Dharmendra S. Modha
mathjax: true
---

* content
{:toc}

##### Abstract
To realize the promise of ubiquitous embedded deep network inference, it is essential to seek limits of energy and area efficiency. To this end, low-precision networks offer tremendous promise because both energy and area scale down quadratically with the reduction in precision. Here, for the first time, we demonstrate ResNet-18, ResNet-34, ResNet-50, ResNet-152, Inception-v3, densenet-161, and VGG-16bn networks on the ImageNet classification benchmark that, at 8-bit precision exceed the accuracy of the full-precision baseline networks after one epoch of finetuning, thereby leveraging the availability of pretrained models. We also demonstrate for the first time ResNet-18, ResNet-34, and ResNet-50 4-bit models that match the accuracy of the full-precision baseline networks. Surprisingly, the weights of the low-precision networks are very close (in cosine similarity) to the weights of the corresponding baseline networks, making training from scratch unnecessary. 
 The number of iterations required by stochastic gradient descent to achieve a given training error is related to the square of (a) the distance of the initial solution from the final plus (b) the maximum variance of the gradient estimates. By drawing inspiration from this observation, we (a) reduce solution distance by starting with pretrained fp32 precision baseline networks and fine-tuning, and (b) combat noise introduced by quantizing weights and activations during training, by using larger batches along with matched learning rate annealing. Together, these two techniques offer a promising heuristic to discover low-precision networks, if they exist, close to fp32 precision baseline networks.

##### Abstract (translated by Google)
为了实现无处不在的嵌入式深度网络推理的承诺，寻求能量和面积效率的限制是至关重要的。为此，低精度网络提供了巨大的希望，因为能量和面积都会随着精度的降低而逐渐缩小。在这里，我们首次在ImageNet分类基准测试中展示ResNet-18，ResNet-34，ResNet-50，ResNet-152，Inception-v3，densenet-161和VGG-160bn网络，以8位精度在一个微调时期之后超过全精度基线网络的准确度，从而利用预训练模型的可用性。我们还首次演示了ResNet-18，ResNet-34和ResNet-50 4位模型，它们与全精度基线网络的精度相匹配。令人惊讶的是，低精度网络的权重与相应基线网络的权重非常接近（余弦相似性），从而无需进行从头开始的训练。
 随机梯度下降以实现给定训练误差所需的迭代次数与（a）初始解与最终解的距离加上的平方相关（b）梯度估计的最大方差。通过从这一观察中汲取灵感，我们（a）通过从预训练的fp32精确基线网络和微调开始减少解决距离，以及（b）通过在训练期间量化权重和激活引入的战斗噪声，通过使用更大的批次以及匹配的学习速率退火。总之，这两种技术提供了一种有前途的启发式技术，可以发现低精度网络（如果存在的话），接近fp32精确基线网络。

##### URL
[http://arxiv.org/abs/1809.04191](http://arxiv.org/abs/1809.04191)

##### PDF
[http://arxiv.org/pdf/1809.04191](http://arxiv.org/pdf/1809.04191)

