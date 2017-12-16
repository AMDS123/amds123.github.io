---
layout: post
title: "Modeling the Resource Requirements of Convolutional Neural Networks on Mobile Devices"
date: 2017-09-27 13:36:12
categories: arXiv_CV
tags: arXiv_CV Drone CNN Inference Deep_Learning
author: Zongqing Lu, Swati Rallapalli, Kevin Chan, Thomas La Porta
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (CNNs) have revolutionized the research in computer vision, due to their ability to capture complex patterns, resulting in high inference accuracies. However, the increasingly complex nature of these neural networks means that they are particularly suited for server computers with powerful GPUs. We envision that deep learning applications will be eventually and widely deployed on mobile devices, e.g., smartphones, self-driving cars, and drones. Therefore, in this paper, we aim to understand the resource requirements (time, memory) of CNNs on mobile devices. First, by deploying several popular CNNs on mobile CPUs and GPUs, we measure and analyze the performance and resource usage for every layer of the CNNs. Our findings point out the potential ways of optimizing the performance on mobile devices. Second, we model the resource requirements of the different CNN computations. Finally, based on the measurement, pro ling, and modeling, we build and evaluate our modeling tool, Augur, which takes a CNN configuration (descriptor) as the input and estimates the compute time and resource usage of the CNN, to give insights about whether and how e ciently a CNN can be run on a given mobile platform. In doing so Augur tackles several challenges: (i) how to overcome pro ling and measurement overhead; (ii) how to capture the variance in different mobile platforms with different processors, memory, and cache sizes; and (iii) how to account for the variance in the number, type and size of layers of the different CNN configurations.

##### Abstract (translated by Google)
卷积神经网络（CNN）由于捕捉复杂图案的能力，已经彻底改变了计算机视觉领域的研究，从而导致了高的推断精度。然而，这些神经网络越来越复杂的性质意味着它们特别适合具有强大GPU的服务器计算机。我们预计深度学习应用将最终并广泛地部署在移动设备上，例如智能手机，自驾车和无人驾驶飞机。因此，本文旨在了解CNN在移动设备上的资源需求（时间，内存）。首先，通过在移动CPU和GPU上部署几个流行的CNN，我们测量和分析CNN的每一层的性能和资源使用情况。我们的研究结果指出了优化移动设备性能的潜在方法。其次，我们对不同CNN计算的资源需求进行建模。最后，在测量，建模和建模的基础上，我们建立并评估了我们的建模工具Augur，它以CNN配置（描述符）为输入，估算CNN的计算时间和资源使用情况，在给定的移动平台上是否以及如何高效地运行CNN。在这样做时，Augur解决了几个挑战：（i）如何克服测量和测量开销; （ii）如何捕捉具有不同处理器，内存和高速缓存大小的不同移动平台中的差异; （iii）如何说明不同CNN配置的层数，类型和大小的变化。

##### URL
[https://arxiv.org/abs/1709.09503](https://arxiv.org/abs/1709.09503)

##### PDF
[https://arxiv.org/pdf/1709.09503](https://arxiv.org/pdf/1709.09503)

