---
layout: post
title: "Differentiable Scheduled Sampling for Credit Assignment"
date: 2017-04-23 20:05:36
categories: arXiv_CL
tags: arXiv_CL Prediction Recognition
author: Kartik Goyal, Chris Dyer, Taylor Berg-Kirkpatrick
mathjax: true
---

* content
{:toc}

##### Abstract
We demonstrate that a continuous relaxation of the argmax operation can be used to create a differentiable approximation to greedy decoding for sequence-to-sequence (seq2seq) models. By incorporating this approximation into the scheduled sampling training procedure (Bengio et al., 2015)--a well-known technique for correcting exposure bias--we introduce a new training objective that is continuous and differentiable everywhere and that can provide informative gradients near points where previous decoding decisions change their value. In addition, by using a related approximation, we demonstrate a similar approach to sampled-based training. Finally, we show that our approach outperforms cross-entropy training and scheduled sampling procedures in two sequence prediction tasks: named entity recognition and machine translation.

##### Abstract (translated by Google)
我们证明了argmax操作的连续松弛可以用来创建一个可微分的逼近来对序列到序列（seq2seq）模型进行贪婪的解码。通过将这个近似纳入预定的抽样训练程序（Bengio等，2015） - 一个众所周知的纠正暴露偏差的技术 - 我们引入了一个新的训练目标，这个训练目标在任何地方都是连续的和可微的，并且可以提供信息梯度先前解码决定改变其值的点。另外，通过使用相关的近似，我们展示了一种类似的抽样训练方法。最后，我们展示了我们的方法在两个序列预测任务中优于交叉熵训练和预定抽样程序：命名实体识别和机器翻译。

##### URL
[https://arxiv.org/abs/1704.06970](https://arxiv.org/abs/1704.06970)

##### PDF
[https://arxiv.org/pdf/1704.06970](https://arxiv.org/pdf/1704.06970)

