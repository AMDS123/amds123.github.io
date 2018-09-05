---
layout: post
title: "Rx-Caffe: Framework for evaluating and training Deep Neural Networks on Resistive Crossbars"
date: 2018-08-31 22:22:53
categories: arXiv_CV
tags: arXiv_CV Knowledge Recognition
author: Shubham Jain, Abhronil Sengupta, Kaushik Roy, Anand Raghunathan
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Neural Networks (DNNs) are widely used to perform machine learning tasks in speech, image, and natural language processing. The high computation and storage demands of DNNs have led to a need for energy-efficient implementations. Resistive crossbar systems have emerged as promising candidates due to their ability to compactly and efficiently realize the primitive DNN operation, viz., vector-matrix multiplication. However, in practice, the functionality of resistive crossbars may deviate considerably from the ideal abstraction due to the device and circuit level non-idealities such as driver resistance, sensing resistance, sneak paths, and interconnect parasitics. Although DNNs are somewhat tolerant to errors in their computations, it is still essential to evaluate the impact of errors introduced due to crossbar non-idealities on DNN accuracy. Unfortunately, device and circuit-level models are not feasible to use in the context of large-scale DNNs with 2.6-15.5 billion synaptic connections. 
 In this work, we present a fast and accurate simulation framework to enable training and evaluation of large-scale DNNs on resistive crossbar based hardware fabrics. We propose a Fast Crossbar Model (FCM) that accurately captures the errors arising due to non-idealities while being five orders of magnitude faster than circuit simulation. We develop Rx-Caffe, an enhanced version of the popular Caffe machine learning software framework to train and evaluate DNNs on crossbars. We use Rx-Caffe to evaluate large-scale image recognition DNNs designed for the ImageNet dataset. Our experiments reveal that crossbar non-idealities can significantly degrade DNN accuracy by 9.6%-32%. To the best of our knowledge, this work is the first evaluation of the accuracy for large-scale DNNs on resistive crossbars and highlights the need for further efforts to address the impact of non-idealities.

##### Abstract (translated by Google)
深度神经网络（DNN）广泛用于在语音，图像和自然语言处理中执行机器学习任务。 DNN的高计算和存储需求导致了对节能实现的需求。电阻性横杆系统已经成为有希望的候选者，因为它们能够紧凑且有效地实现原始DNN操作，即矢量矩阵乘法。然而，在实践中，由于器件和电路级非理想性（例如驱动器电阻，感测电阻，潜行路径和互连寄生效应），电阻性交叉开关的功能可能与理想的抽象相差很大。尽管DNN在某种程度上容忍其计算中的错误，但仍然必须评估由于交叉开关非理想性而引入的错误对DNN准确性的影响。遗憾的是，在具有2.6-15.5亿个突触连接的大规模DNN环境中使用设备和电路级模型是不可行的。
 在这项工作中，我们提供了一个快速而准确的仿真框架，以便在基于电阻横杆的硬件结构上进行大规模DNN的培训和评估。我们提出了一种快速交叉开关模型（FCM），能够准确地捕获由非理想性引起的误差，同时比电路仿真快5个数量级。我们开发了Rx-Caffe，这是一种流行的Caffe机器学习软件框架的增强版本，用于训练和评估横杆上的DNN。我们使用Rx-Caffe来评估为ImageNet数据集设计的大规模图像识别DNN。我们的实验表明，横杆非理想性可以显着降低DNN精度9.6％-32％。据我们所知，这项工作是对电阻横杆上大规模DNN精度的首次评估，并强调需要进一步努力解决非理想性的影响。

##### URL
[http://arxiv.org/abs/1809.00072](http://arxiv.org/abs/1809.00072)

##### PDF
[http://arxiv.org/pdf/1809.00072](http://arxiv.org/pdf/1809.00072)

