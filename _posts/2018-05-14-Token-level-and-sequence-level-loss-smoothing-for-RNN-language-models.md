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
尽管递归神经网络语言模型的有效性，但它们的最大似然估计受到两个限制。它将所有与地面实况不匹配的句子视为同等差，忽略了输出空间的结构。其次，它遭受“暴露偏差”：在训练令牌期间预测给定地面实况序列，而在测试时，预测以生成的输出序列为条件。为了克服这些限制，我们建立在最近的奖励增强最大似然方法上，即序列级平滑，其鼓励模型根据给定的性能度量来预测接近地面实况的句子。我们将此方法扩展到令牌级丢失平滑，并提出了对序列级平滑方法的改进。我们对两个不同任务（图像标题和机器翻译）的实验表明，令牌级和序列级丢失平滑是互补的，并且显着改善了结果。

##### URL
[https://arxiv.org/abs/1805.05062](https://arxiv.org/abs/1805.05062)

##### PDF
[https://arxiv.org/pdf/1805.05062](https://arxiv.org/pdf/1805.05062)

