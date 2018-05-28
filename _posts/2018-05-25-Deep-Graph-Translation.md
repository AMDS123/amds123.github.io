---
layout: post
title: "Deep Graph Translation"
date: 2018-05-25 04:56:07
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN
author: Xiaojie Guo, Lingfei Wu, Liang Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Inspired by the tremendous success of deep generative models on generating continuous data like image and audio, in the most recent year, few deep graph generative models have been proposed to generate discrete data such as graphs. They are typically unconditioned generative models which has no control on modes of the graphs being generated. Differently, in this paper, we are interested in a new problem named \emph{Deep Graph Translation}: given an input graph, we want to infer a target graph based on their underlying (both global and local) translation mapping. Graph translation could be highly desirable in many applications such as disaster management and rare event forecasting, where the rare and abnormal graph patterns (e.g., traffic congestions and terrorism events) will be inferred prior to their occurrence even without historical data on the abnormal patterns for this graph (e.g., a road network or human contact network). To achieve this, we propose a novel Graph-Translation-Generative Adversarial Networks (GT-GAN) which will generate a graph translator from input to target graphs. GT-GAN consists of a graph translator where we propose new graph convolution and deconvolution layers to learn the global and local translation mapping. A new conditional graph discriminator has also been proposed to classify target graphs by conditioning on input graphs. Extensive experiments on multiple synthetic and real-world datasets demonstrate the effectiveness and scalability of the proposed GT-GAN.

##### Abstract (translated by Google)
受深度生成模型在生成图像和音频等连续数据方面的巨大成功的启发，最近一年，很少有深度图生成模型被提出来生成诸如图的离散数据。它们通常是无条件的生成模型，它无法控制正在生成的图的模式。不同的是，在本文中，我们感兴趣的是一个名为\ emph {Deep Graph Translation}的新问题：给定一个输入图，我们想根据它们的基础（全局和本地）翻译映射来推断目标图。在许多应用中，图形转换可能是非常需要的，例如灾难管理和罕见事件预测，其中罕见和异常的图形模式（例如，交通堵塞和恐怖主义事件）将在其发生之前被推断，即使没有关于异常模式的历史数据该图表（例如，道路网络或人类联系网络）。为此，我们提出了一种新的Graph-Translation-Generative Adversarial Networks（GT-GAN），它将从输入到目标图形生成一个图形转换器。 GT-GAN由一个图形转换器组成，我们提出新的图形卷积和反卷积图层来学习全局和局部转换映射。还提出了一种新的条件图鉴别器，通过对输入图进行调节来对目标图进行分类。对多个合成和现实世界的数据集进行的大量实验证明了所提出的GT-GAN的有效性和可扩展性。

##### URL
[http://arxiv.org/abs/1805.09980](http://arxiv.org/abs/1805.09980)

##### PDF
[http://arxiv.org/pdf/1805.09980](http://arxiv.org/pdf/1805.09980)

