---
layout: post
title: "DyVEDeep: Dynamic Variable Effort Deep Neural Networks"
date: 2017-04-04 18:14:02
categories: arXiv_CV
tags: arXiv_CV Inference Classification Recognition
author: Sanjay Ganapathy, Swagath Venkataramani, Balaraman Ravindran, Anand Raghunathan
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Neural Networks (DNNs) have advanced the state-of-the-art in a variety of machine learning tasks and are deployed in increasing numbers of products and services. However, the computational requirements of training and evaluating large-scale DNNs are growing at a much faster pace than the capabilities of the underlying hardware platforms that they are executed upon. In this work, we propose Dynamic Variable Effort Deep Neural Networks (DyVEDeep) to reduce the computational requirements of DNNs during inference. Previous efforts propose specialized hardware implementations for DNNs, statically prune the network, or compress the weights. Complementary to these approaches, DyVEDeep is a dynamic approach that exploits the heterogeneity in the inputs to DNNs to improve their compute efficiency with comparable classification accuracy. DyVEDeep equips DNNs with dynamic effort mechanisms that, in the course of processing an input, identify how critical a group of computations are to classify the input. DyVEDeep dynamically focuses its compute effort only on the critical computa- tions, while skipping or approximating the rest. We propose 3 effort knobs that operate at different levels of granularity viz. neuron, feature and layer levels. We build DyVEDeep versions for 5 popular image recognition benchmarks - one for CIFAR-10 and four for ImageNet (AlexNet, OverFeat and VGG-16, weight-compressed AlexNet). Across all benchmarks, DyVEDeep achieves 2.1x-2.6x reduction in the number of scalar operations, which translates to 1.8x-2.3x performance improvement over a Caffe-based implementation, with < 0.5% loss in accuracy.

##### Abstract (translated by Google)
深度神经网络（DNN）已经在各种机器学习任务中推进了最先进的技术，并被部署在越来越多的产品和服务中。然而，培训和评估大型DNN的计算要求正在以比它们所执行的底层硬件平台的能力更快的速度增长。在这项工作中，我们提出动态变量努力深度神经网络（DyVEDeep），以减少DNN在推理过程中的计算需求。以前的工作为DNN提出专门的硬件实现，静态修剪网络或压缩权重。作为这些方法的补充，DyVEDeep是一种动态的方法，利用输入到DNN的异质性，以相当的分类准确度来提高计算效率。 DyVEDeep为DNN提供动态工作机制，在处理输入的过程中，确定一组计算对输入进行分类的重要性。 DyVEDeep动态地将其计算工作集中在关键计算上，而跳过或接近其余部分。我们提出了3个努力旋钮，在不同的粒度级别运作。神经元，功能和层次。我们为5个流行的图像识别基准构建了DyVEDeep版本 - 一个用于CIFAR-10，另一个用于ImageNet（AlexNet，OverFeat和VGG-16，重量压缩的AlexNet）。在所有基准测试中，DyVEDeep的标量操作数量减少了2.1x-2.6x，相比基于Caffe的实现，性能提高了1.8x-2.3x，准确度损失<0.5％。

##### URL
[https://arxiv.org/abs/1704.01137](https://arxiv.org/abs/1704.01137)

##### PDF
[https://arxiv.org/pdf/1704.01137](https://arxiv.org/pdf/1704.01137)

