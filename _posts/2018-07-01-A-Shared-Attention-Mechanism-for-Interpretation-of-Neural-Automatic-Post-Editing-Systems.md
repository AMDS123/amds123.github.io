---
layout: post
title: "A Shared Attention Mechanism for Interpretation of Neural Automatic Post-Editing Systems"
date: 2018-07-01 00:31:27
categories: arXiv_CL
tags: arXiv_CL Attention
author: Inigo Jauregi Unanue, Ehsan Zare Borzeshi, Massimo Piccardi
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic post-editing (APE) systems aim to correct the systematic errors made by machine translators. In this paper, we propose a neural APE system that encodes the source (src) and machine translated (mt) sentences with two separate encoders, but leverages a shared attention mechanism to better understand how the two inputs contribute to the generation of the post-edited (pe) sentences. Our empirical observations have showed that when the mt is incorrect, the attention shifts weight toward tokens in the src sentence to properly edit the incorrect translation. The model has been trained and evaluated on the official data from the WMT16 and WMT17 APE IT domain English-German shared tasks. Additionally, we have used the extra 500K artificial data provided by the shared task. Our system has been able to reproduce the accuracies of systems trained with the same data, while at the same time providing better interpretability.

##### Abstract (translated by Google)
自动后期编辑（APE）系统旨在纠正机器翻译器所产生的系统错误。在本文中，我们提出了一个神经APE系统，它使用两个独立的编码器对源（src）和机器翻译（mt）句子进行编码，但利用共同的注意机制来更好地理解这两个输入如何有助于后期的生成。编辑（pe）句子。我们的经验观察表明，当mt不正确时，注意力会将权重转移到src句子中的标记，以正确编辑错误的翻译。该模型已经过WMT16和WMT17 APE IT领域英德共享任务的官方数据培训和评估。此外，我们使用了共享任务提供的额外500K人工数据。我们的系统能够再现使用相同数据训练的系统的精度，同时提供更好的可解释性。

##### URL
[http://arxiv.org/abs/1807.00248](http://arxiv.org/abs/1807.00248)

##### PDF
[http://arxiv.org/pdf/1807.00248](http://arxiv.org/pdf/1807.00248)

