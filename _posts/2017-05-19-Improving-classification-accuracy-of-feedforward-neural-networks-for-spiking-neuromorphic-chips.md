---
layout: post
title: "Improving classification accuracy of feedforward neural networks for spiking neuromorphic chips"
date: 2017-05-19 12:59:14
categories: arXiv_CV
tags: arXiv_CV Classification
author: Antonio Jimeno Yepes, Jianbin Tang, Benjamin Scott Mashford
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Neural Networks (DNN) achieve human level performance in many image analytics tasks but DNNs are mostly deployed to GPU platforms that consume a considerable amount of power. New hardware platforms using lower precision arithmetic achieve drastic reductions in power consumption. More recently, brain-inspired spiking neuromorphic chips have achieved even lower power consumption, on the order of milliwatts, while still offering real-time processing. However, for deploying DNNs to energy efficient neuromorphic chips the incompatibility between continuous neurons and synaptic weights of traditional DNNs, discrete spiking neurons and synapses of neuromorphic chips need to be overcome. Previous work has achieved this by training a network to learn continuous probabilities, before it is deployed to a neuromorphic architecture, such as IBM TrueNorth Neurosynaptic System, by random sampling these probabilities. The main contribution of this paper is a new learning algorithm that learns a TrueNorth configuration ready for deployment. We achieve this by training directly a binary hardware crossbar that accommodates the TrueNorth axon configuration constrains and we propose a different neuron model. Results of our approach trained on electroencephalogram (EEG) data show a significant improvement with previous work (76% vs 86% accuracy) while maintaining state of the art performance on the MNIST handwritten data set.

##### Abstract (translated by Google)
深度神经网络（DNN）在许多图像分析任务中实现人类级别的性能，但是DNN主要被部署到消耗相当大量功率的GPU平台。使用较低精度算术的新硬件平台可大幅降低功耗。最近，大脑启发的尖峰神经形态芯片已经实现了更低的功耗，毫瓦数量级，同时仍然提供实时处理。然而，为了将DNN部署到能量有效的神经形态芯片，需要克服连续神经元和传统DNN的突触权重，离散尖峰神经元和神经形态芯片的突触之间的不相容性。之前的工作已经通过训练网络来学习连续概率，然后通过对这些概率进行随机采样，将其部署到神经形态体系结构（如IBM TrueNorth神经突触系统）之前。本文的主要贡献是一个学习TrueNorth配置准备部署的新的学习算法。我们通过直接训练一个适应TrueNorth轴突配置约束的二进制硬件交叉开关来实现这一点，并且我们提出了一个不同的神经元模型。我们的脑电图（EEG）数据训练方法的结果显示，与以前的工作（76％比86％的准确性）有显着的改善，同时保持MNIST手写数据集的最新性能。

##### URL
[https://arxiv.org/abs/1705.07755](https://arxiv.org/abs/1705.07755)

##### PDF
[https://arxiv.org/pdf/1705.07755](https://arxiv.org/pdf/1705.07755)

