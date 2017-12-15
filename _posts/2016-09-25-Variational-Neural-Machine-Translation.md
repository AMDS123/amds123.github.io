---
layout: post
title: "Variational Neural Machine Translation"
date: 2016-09-25 23:37:14
categories: arXiv_CL
tags: arXiv_CL Inference
author: Biao Zhang, Deyi Xiong, Jinsong Su, Hong Duan, Min Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Models of neural machine translation are often from a discriminative family of encoderdecoders that learn a conditional distribution of a target sentence given a source sentence. In this paper, we propose a variational model to learn this conditional distribution for neural machine translation: a variational encoderdecoder model that can be trained end-to-end. Different from the vanilla encoder-decoder model that generates target translations from hidden representations of source sentences alone, the variational model introduces a continuous latent variable to explicitly model underlying semantics of source sentences and to guide the generation of target translations. In order to perform efficient posterior inference and large-scale training, we build a neural posterior approximator conditioned on both the source and the target sides, and equip it with a reparameterization technique to estimate the variational lower bound. Experiments on both Chinese-English and English- German translation tasks show that the proposed variational neural machine translation achieves significant improvements over the vanilla neural machine translation baselines.

##### Abstract (translated by Google)
神经机器翻译的模型通常来自一个有区别的编码器解码器家族，它学习给定源句子的目标句子的条件分布。在本文中，我们提出了一个变分模型来学习神经机器翻译的条件分布：一个可以进行端到端训练的变分编码器解码器模型。与单纯从源句子的隐藏表示生成目标翻译的香草编码器 - 解码器模型不同，变分模型引入了连续的潜变量来显式地模拟源语句的基本语义并指导目标翻译的生成。为了进行高效的后验推理和大规模的训练，我们建立了一个在源和目标两侧都有条件的神经后验逼近器，并配备了重新参数化技术来估计变分下界。中英文和英文 - 德文翻译任务的实验表明，所提出的变分神经机器翻译在香草神经机器翻译基线方面实现了显着的改进。

##### URL
[https://arxiv.org/abs/1605.07869](https://arxiv.org/abs/1605.07869)

##### PDF
[https://arxiv.org/pdf/1605.07869](https://arxiv.org/pdf/1605.07869)

