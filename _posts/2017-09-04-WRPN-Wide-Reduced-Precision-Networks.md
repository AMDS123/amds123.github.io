---
layout: post
title: "WRPN: Wide Reduced-Precision Networks"
date: 2017-09-04 19:56:48
categories: arXiv_CV
tags: arXiv_CV Inference
author: Asit Mishra, Eriko Nurvitadhi, Jeffrey J Cook, Debbie Marr
mathjax: true
---

* content
{:toc}

##### Abstract
For computer vision applications, prior works have shown the efficacy of reducing numeric precision of model parameters (network weights) in deep neural networks. Activation maps, however, occupy a large memory footprint during both the training and inference step when using mini-batches of inputs. One way to reduce this large memory footprint is to reduce the precision of activations. However, past works have shown that reducing the precision of activations hurts model accuracy. We study schemes to train networks from scratch using reduced-precision activations without hurting accuracy. We reduce the precision of activation maps (along with model parameters) and increase the number of filter maps in a layer, and find that this scheme matches or surpasses the accuracy of the baseline full-precision network. As a result, one can significantly improve the execution efficiency (e.g. reduce dynamic memory footprint, memory bandwidth and computational energy) and speed up the training and inference process with appropriate hardware support. We call our scheme WRPN - wide reduced-precision networks. We report results and show that WRPN scheme is better than previously reported accuracies on ILSVRC-12 dataset while being computationally less expensive compared to previously reported reduced-precision networks.

##### Abstract (translated by Google)
对于计算机视觉应用，先前的工作已经显示了在深度神经网络中降低模型参数（网络权重）的数字精度的功效。然而，激活图在使用小批量输入时在训练和推理步骤中占用大量的记忆足迹。减少这种大内存占用的一种方法是降低激活的精度。然而，过去的工作表明，降低激活的精度会损害模型的准确性。我们研究的方案来从头开始使用降低精度激活来训练网络，而不会影响准确性。我们降低了激活图的精确度（以及模型参数），增加了一个图层中的滤波器图的数量，发现这个方案匹配或者超过了基线全精度网络的精度。因此，可以显着提高执行效率（例如，减少动态存储器占用空间，存储器带宽和计算能量），并在适当的硬件支持下加快训练和推理过程。我们称之为WRPN宽范围精简网络。我们报告结果，并显示WRPN方案比先前报道的ILSVRC-12数据集的精度更好，而与之前报道的精度更低的网络相比，计算更便宜。

##### URL
[https://arxiv.org/abs/1709.01134](https://arxiv.org/abs/1709.01134)

##### PDF
[https://arxiv.org/pdf/1709.01134](https://arxiv.org/pdf/1709.01134)

