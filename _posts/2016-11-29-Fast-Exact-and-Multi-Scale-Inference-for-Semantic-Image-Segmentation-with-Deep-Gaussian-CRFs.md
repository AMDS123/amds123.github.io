---
layout: post
title: "Fast, Exact and Multi-Scale Inference for Semantic Image Segmentation with Deep Gaussian CRFs"
date: 2016-11-29 14:52:20
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Optimization Inference Deep_Learning Prediction
author: Siddhartha Chandra, Iasonas Kokkinos
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we propose a structured prediction technique that combines the virtues of Gaussian Conditional Random Fields (G-CRF) with Deep Learning: (a) our structured prediction task has a unique global optimum that is obtained exactly from the solution of a linear system (b) the gradients of our model parameters are analytically computed using closed form expressions, in contrast to the memory-demanding contemporary deep structured prediction approaches that rely on back-propagation-through-time, (c) our pairwise terms do not have to be simple hand-crafted expressions, as in the line of works building on the DenseCRF, but can rather be `discovered' from data through deep architectures, and (d) out system can trained in an end-to-end manner. Building on standard tools from numerical analysis we develop very efficient algorithms for inference and learning, as well as a customized technique adapted to the semantic segmentation task. This efficiency allows us to explore more sophisticated architectures for structured prediction in deep learning: we introduce multi-resolution architectures to couple information across scales in a joint optimization framework, yielding systematic improvements. We demonstrate the utility of our approach on the challenging VOC PASCAL 2012 image segmentation benchmark, showing substantial improvements over strong baselines. We make all of our code and experiments available at {this https URL}

##### Abstract (translated by Google)
在这项工作中，我们提出了一种结合了高斯条件随机场（G-CRF）与深度学习的优点的结构化预测技术：（a）我们的结构化预测任务具有独特的全局最优性，它是从线性系统（b）我们的模型参数的梯度是用封闭形式的表达式进行分析计算的，与需要内存要求的当代深层结构预测方法相比，（c）我们的配对项没有必要是简单的手工制作的表达，就像在DenseCRF上建立的工作流程一样，而是可以通过深层架构从数据中“发现”出来，并且（d）能够以端到端的方式训练出系统。基于数值分析的标准工具，我们开发了非常有效的推理和学习算法，以及适用于语义分割任务的定制技术。这种效率使我们能够在深度学习中探索更复杂的结构化预测体系结构：我们引入多分辨率体系结构，在联合优化框架中跨越尺度耦合信息，从而产生系统性改进。我们展示了我们的方法在具有挑战性的VOC PASCAL 2012图像分割基准测试中的实用性，显示了强大的基线方面的重大改进。我们将所有的代码和实验提供给{this https URL}

##### URL
[https://arxiv.org/abs/1603.08358](https://arxiv.org/abs/1603.08358)

##### PDF
[https://arxiv.org/pdf/1603.08358](https://arxiv.org/pdf/1603.08358)

