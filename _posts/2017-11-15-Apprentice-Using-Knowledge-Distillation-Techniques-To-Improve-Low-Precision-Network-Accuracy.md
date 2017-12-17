---
layout: post
title: "Apprentice: Using Knowledge Distillation Techniques To Improve Low-Precision Network Accuracy"
date: 2017-11-15 23:45:59
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Image_Classification Inference Classification Deep_Learning Detection
author: Asit Mishra, Debbie Marr
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning networks have achieved state-of-the-art accuracies on computer vision workloads like image classification and object detection. The performant systems, however, typically involve big models with numerous parameters. Once trained, a challenging aspect for such top performing models is deployment on resource constrained inference systems - the models (often deep networks or wide networks or both) are compute and memory intensive. Low-precision numerics and model compression using knowledge distillation are popular techniques to lower both the compute requirements and memory footprint of these deployed models. In this paper, we study the combination of these two techniques and show that the performance of low-precision networks can be significantly improved by using knowledge distillation techniques. Our approach, Apprentice, achieves state-of-the-art accuracies using ternary precision and 4-bit precision for variants of ResNet architecture on ImageNet dataset. We present three schemes using which one can apply knowledge distillation techniques to various stages of the train-and-deploy pipeline.

##### Abstract (translated by Google)
深度学习网络已经在计算机视觉工作负载（如图像分类和对象检测）方面实现了最先进的精度。然而，高性能系统通常涉及具有多个参数的大型模型。一旦接受培训，这种高性能模型的一个挑战就是部署在资源受限的推理系统上 - 模型（通常是深度网络或广泛的网络或者两者）都是计算和内存密集型的。使用知识蒸馏的低精度数值模型压缩是降低这些已部署模型的计算需求和内存占用空间的流行技术。在本文中，我们研究这两种技术的结合，并且表明通过使用知识蒸馏技术可以显着提高低精度网络的性能。我们的方法Apprentice在ImageNet数据集上使用ResNet体系结构的三种精度和4位精度，实现了最先进的精度。我们提出了三种方案，可以将知识蒸馏技术应用到列车和部署管道的各个阶段。

##### URL
[https://arxiv.org/abs/1711.05852](https://arxiv.org/abs/1711.05852)

##### PDF
[https://arxiv.org/pdf/1711.05852](https://arxiv.org/pdf/1711.05852)

