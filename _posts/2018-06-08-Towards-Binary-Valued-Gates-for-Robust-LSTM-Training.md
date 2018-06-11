---
layout: post
title: "Towards Binary-Valued Gates for Robust LSTM Training"
date: 2018-06-08 06:57:16
categories: arXiv_CL
tags: arXiv_CL RNN
author: Zhuohan Li, Di He, Fei Tian, Wei Chen, Tao Qin, Liwei Wang, Tie-Yan Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Long Short-Term Memory (LSTM) is one of the most widely used recurrent structures in sequence modeling. It aims to use gates to control information flow (e.g., whether to skip some information or not) in the recurrent computations, although its practical implementation based on soft gates only partially achieves this goal. In this paper, we propose a new way for LSTM training, which pushes the output values of the gates towards 0 or 1. By doing so, we can better control the information flow: the gates are mostly open or closed, instead of in a middle state, which makes the results more interpretable. Empirical studies show that (1) Although it seems that we restrict the model capacity, there is no performance drop: we achieve better or comparable performances due to its better generalization ability; (2) The outputs of gates are not sensitive to their inputs: we can easily compress the LSTM unit in multiple ways, e.g., low-rank approximation and low-precision approximation. The compressed models are even better than the baseline models without compression.

##### Abstract (translated by Google)
长期短期记忆（LSTM）是序列建模中使用最广泛的循环结构之一。它旨在使用门来控制信息流（例如是否跳过一些信息），虽然其基于软门的实际实现仅部分地实现了该目标。在本文中，我们提出了一种LSTM训练的新方法，它将门的输出值向0或1推进。通过这样做，我们可以更好地控制信息流：闸门大部分是打开或关闭的，而不是中间状态，这使得结果更具可解释性。实证研究表明：（1）尽管我们似乎限制了模型容量，但没有性能下降：由于其更好的泛化能力，我们获得了更好或相当的性能; （2）门的输出对其输入不敏感：我们可以用多种方式轻松压缩LSTM单元，例如，低阶逼近和低精度近似。压缩模型甚至比没有压缩的基线模型更好。

##### URL
[http://arxiv.org/abs/1806.02988](http://arxiv.org/abs/1806.02988)

##### PDF
[http://arxiv.org/pdf/1806.02988](http://arxiv.org/pdf/1806.02988)

