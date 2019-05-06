---
layout: post
title: "TEA-DNN: the Quest for Time-Energy-Accuracy Co-optimized Deep Neural Networks"
date: 2018-11-29 11:05:28
categories: arXiv_CV
tags: arXiv_CV Knowledge NAS CNN Image_Classification Optimization Inference Classification Deep_Learning
author: Lile Cai, Anne-Maelle Barneche, Arthur Herbout, Chuan Sheng Foo, Jie Lin, Vijay Ramaseshan Chandrasekhar, Mohamed M. Sabry
mathjax: true
---

* content
{:toc}

##### Abstract
Embedded deep learning platforms have witnessed two simultaneous improvements. First, the accuracy of convolutional neural networks (CNNs) has been significantly improved through the use of automated neural-architecture search (NAS) algorithms to determine CNN structure. Second, there has been increasing interest in developing application-specific platforms for CNNs that provide improved inference performance and energy consumption as compared to GPUs. Embedded deep learning platforms differ in the amount of compute resources and memory-access bandwidth, which would affect performance and energy consumption of CNNs. It is therefore critical to consider the available hardware resources in the network architecture search. To this end, we introduce TEA-DNN, a NAS algorithm targeting multi-objective optimization of execution time, energy consumption, and classification accuracy of CNN workloads on embedded architectures. TEA-DNN leverages energy and execution time measurements on embedded hardware when exploring the Pareto-optimal curves across accuracy, execution time, and energy consumption and does not require additional effort to model the underlying hardware. We apply TEA-DNN for image classification on actual embedded platforms (NVIDIA Jetson TX2 and Intel Movidius Neural Compute Stick). We highlight the Pareto-optimal operating points that emphasize the necessity to explicitly consider hardware characteristics in the search process. To the best of our knowledge, this is the most comprehensive study of Pareto-optimal models across a range of hardware platforms using actual measurements on hardware to obtain objective values.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.12065](https://arxiv.org/abs/1811.12065)

##### PDF
[https://arxiv.org/pdf/1811.12065](https://arxiv.org/pdf/1811.12065)

