---
layout: post
title: "Towards a Deep Unified Framework for Nuclear Reactor Perturbation Analysis"
date: 2018-07-26 12:34:25
categories: arXiv_AI
tags: arXiv_AI CNN RNN Classification
author: Fabio De Sousa Ribeiro, Francesco Caliva, Dionysios Chionis, Abdelhamid Dokhane, Antonios Mylonakis, Christophe Demaziere, Georgios Leontidis, Stefanos Kollias
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes the first step towards a novel unified framework for the analysis of perturbations occurring in nuclear reactors in both Time and Frequency domain. The identification of type and source of such perturbations is fundamental for monitoring core reactors and guarantee safety even while running at nominal conditions. A 3D Convolutional Neural Network (3D-CNN) was employed to analyse perturbations happening in the frequency domain, such as the alteration of an absorber of variable strength or propagating perturbation. Recurrent neural networks (RNN), specifically Long Short-Term Memory (LSTM) was used to study signal sequences related to perturbations induced in the time domain, including the vibrations of fuel assemblies and the fluctuation of thermalhydraulic parameters at the inlet of the reactor coolant loops. 512-dimensional representations were extracted from the 3D-CNN and LSTM architectures, and used as input to a fused multi-sigmoid classification layer to recognise the perturbation type. If the perturbation is frequency domain related, a separate fully-connected layer utilises said representations to regress the coordinates of its source. The results showed that perturbation type can be recognised with high accuracy in both domains, and frequency domain scenario sources can be localised with high precision.

##### Abstract (translated by Google)
本文提出了一个新的统一框架的第一步，用于分析时域和频域核反应堆中发生的扰动。识别这种扰动的类型和来源是监测核心反应堆的基础，即使在标称条件下运行也能保证安全。使用3D卷积神经网络（3D-CNN）来分析频域中发生的扰动，例如可变强度的吸收体的改变或传播扰动。使用递归神经网络（RNN），特别是长期短期记忆（LSTM）来研究与时域中引起的扰动相关的信号序列，包括燃料组件的振动和反应堆冷却剂入口处的热液参数的波动。循环。从3D-CNN和LSTM架构中提取512维表示，并将其用作融合的多S形分类层的输入以识别扰动类型。如果扰动与频域相关，则单独的完全连接层利用所述表示来回归其源的坐标。结果表明，在两个域中都可以高精度地识别扰动类型，并且可以高精度地定位频域场景源。

##### URL
[http://arxiv.org/abs/1807.10096](http://arxiv.org/abs/1807.10096)

##### PDF
[http://arxiv.org/pdf/1807.10096](http://arxiv.org/pdf/1807.10096)

