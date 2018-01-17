---
layout: post
title: "Variational Recurrent Neural Machine Translation"
date: 2018-01-16 05:18:06
categories: arXiv_CL
tags: arXiv_CL NMT Inference RNN
author: Jinsong Su, Shan Wu, Deyi Xiong, Yaojie Lu, Xianpei Han, Biao Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Partially inspired by successful applications of variational recurrent neural networks, we propose a novel variational recurrent neural machine translation (VRNMT) model in this paper. Different from the variational NMT, VRNMT introduces a series of latent random variables to model the translation procedure of a sentence in a generative way, instead of a single latent variable. Specifically, the latent random variables are included into the hidden states of the NMT decoder with elements from the variational autoencoder. In this way, these variables are recurrently generated, which enables them to further capture strong and complex dependencies among the output translations at different timesteps. In order to deal with the challenges in performing efficient posterior inference and large-scale training during the incorporation of latent variables, we build a neural posterior approximator, and equip it with a reparameterization technique to estimate the variational lower bound. Experiments on Chinese-English and English-German translation tasks demonstrate that the proposed model achieves significant improvements over both the conventional and variational NMT models.

##### Abstract (translated by Google)
部分受变分循环神经网络成功应用的启发，本文提出了一种新的变分递归神经机器翻译（VRNMT）模型。与变分NMT不同，VRNMT引入了一系列潜在的随机变量，以生成的方式对句子的翻译过程进行建模，而不是单一的潜变量。具体而言，潜在的随机变量被包括在具有来自变分自编码器的元素的NMT解码器的隐藏状态中。通过这种方式，这些变量是循环生成的，这使得它们能够以不同的时间步进一步捕获输出翻译之间的强而复杂的依赖关系。为了解决潜在变量合并中进行高效后验推理和大规模训练所面临的挑战，我们构建了一个神经后验逼近器，并配备了重新参数化技术来估计变分下界。汉英和英德翻译任务的实验表明，所提出的模型在传统NMT模型和变分NMT模型上都取得了显着的改进。

##### URL
[http://arxiv.org/abs/1801.05119](http://arxiv.org/abs/1801.05119)

##### PDF
[http://arxiv.org/pdf/1801.05119](http://arxiv.org/pdf/1801.05119)

