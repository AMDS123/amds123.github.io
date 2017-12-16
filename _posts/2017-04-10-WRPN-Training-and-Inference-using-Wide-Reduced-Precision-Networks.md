---
layout: post
title: "WRPN: Training and Inference using Wide Reduced-Precision Networks"
date: 2017-04-10 22:54:38
categories: arXiv_CV
tags: arXiv_CV Inference
author: Asit Mishra, Jeffrey J Cook, Eriko Nurvitadhi, Debbie Marr
mathjax: true
---

* content
{:toc}

##### Abstract
For computer vision applications, prior works have shown the efficacy of reducing the numeric precision of model parameters (network weights) in deep neural networks but also that reducing the precision of activations hurts model accuracy much more than reducing the precision of model parameters. We study schemes to train networks from scratch using reduced-precision activations without hurting the model accuracy. We reduce the precision of activation maps (along with model parameters) using a novel quantization scheme and increase the number of filter maps in a layer, and find that this scheme compensates or surpasses the accuracy of the baseline full-precision network. As a result, one can significantly reduce the dynamic memory footprint, memory bandwidth, computational energy and speed up the training and inference process with appropriate hardware support. We call our scheme WRPN - wide reduced-precision networks. We report results using our proposed schemes and show that our results are better than previously reported accuracies on ILSVRC-12 dataset while being computationally less expensive compared to previously reported reduced-precision networks.

##### Abstract (translated by Google)
对于计算机视觉应用，先前的工作已经表明降低深度神经网络中的模型参数（网络权重）的数字精度的功效，而且降低激活的精度损害模型精度的作用远大于降低模型参数的精度。我们研究的方案，使用降低精度激活从头开始训练网络，而不会影响模型精度。我们使用一种新的量化方案降低了激活图的精确度（以及模型参数），并增加了一个图层中滤波器图的数量，发现这个方案补偿或者超过了基线全精度网络的精度。因此，可以大大减少动态内存占用，内存带宽，计算能量，并在适当的硬件支持下加快训练和推理过程。我们称之为WRPN宽范围精简网络。我们使用我们提出的方案报告结果，并表明我们的结果比之前报道的ILSVRC-12数据集的精度要好，而与之前报道的精度较低的网络相比，计算成本更低。

##### URL
[https://arxiv.org/abs/1704.03079](https://arxiv.org/abs/1704.03079)

##### PDF
[https://arxiv.org/pdf/1704.03079](https://arxiv.org/pdf/1704.03079)

