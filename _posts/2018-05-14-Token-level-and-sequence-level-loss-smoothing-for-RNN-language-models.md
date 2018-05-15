---
layout: post
title: "Token-level and sequence-level loss smoothing for RNN language models"
date: 2018-05-14 08:37:50
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption RNN Language_Model Prediction
author: Maha Elbayad, Laurent Besacier, Jakob Verbeek
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the effectiveness of recurrent neural network language models, their maximum likelihood estimation suffers from two limitations. It treats all sentences that do not match the ground truth as equally poor, ignoring the structure of the output space. Second, it suffers from "exposure bias": during training tokens are predicted given ground-truth sequences, while at test time prediction is conditioned on generated output sequences. To overcome these limitations we build upon the recent reward augmented maximum likelihood approach \ie sequence-level smoothing that encourages the model to predict sentences close to the ground truth according to a given performance metric. We extend this approach to token-level loss smoothing, and propose improvements to the sequence-level smoothing approach. Our experiments on two different tasks, image captioning and machine translation, show that token-level and sequence-level loss smoothing are complementary, and significantly improve results.

##### Abstract (translated by Google)
尽管经常性神经网络语言模型的有效性，但它们的最大似然估计受到两个限制。它将所有与实际情况不匹配的句子视为同等贫穷，忽略了输出空间的结构。其次，它受到“暴露偏倚”的影响：在给定地面真值序列的过程中预测训练令牌，而在测试时间，预测以生成的输出序列为条件。为了克服这些限制，我们基于最近的奖励增广最大似然方法\即序列级平滑，其鼓励模型根据给定的性能度量来预测接近地面真实性的句子。我们将这种方法扩展到令牌级丢失平滑，并提出了序列级平滑方法的改进。我们在两个不同任务（图像字幕和机器翻译）上的实验表明，令牌级和序列级损失平滑是互补的，并且显着改善结果。

##### URL
[https://arxiv.org/abs/1805.05062](https://arxiv.org/abs/1805.05062)

##### PDF
[https://arxiv.org/pdf/1805.05062](https://arxiv.org/pdf/1805.05062)

