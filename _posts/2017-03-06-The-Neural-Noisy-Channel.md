---
layout: post
title: "The Neural Noisy Channel"
date: 2017-03-06 12:37:12
categories: arXiv_CL
tags: arXiv_CL RNN
author: Lei Yu, Phil Blunsom, Chris Dyer, Edward Grefenstette, Tomas Kocisky
mathjax: true
---

* content
{:toc}

##### Abstract
We formulate sequence to sequence transduction as a noisy channel decoding problem and use recurrent neural networks to parameterise the source and channel models. Unlike direct models which can suffer from explaining-away effects during training, noisy channel models must produce outputs that explain their inputs, and their component models can be trained with not only paired training samples but also unpaired samples from the marginal output distribution. Using a latent variable to control how much of the conditioning sequence the channel model needs to read in order to generate a subsequent symbol, we obtain a tractable and effective beam search decoder. Experimental results on abstractive sentence summarisation, morphological inflection, and machine translation show that noisy channel models outperform direct models, and that they significantly benefit from increased amounts of unpaired output data that direct models cannot easily use.

##### Abstract (translated by Google)
我们将序列转换为噪声信道解码问题，并使用递归神经网络对源信道模型进行参数化。与直接模型在训练过程中可能遭受解释效应的影响不同，噪声信道模型必须产生解释其输入的输出，并且其成分模型不仅可以训练成对训练样本，还可以训练来自边缘输出分布的不成对样本。使用潜变量来控制信道模型需要读取多少调节序列以便生成后续符号，我们获得易处理和有效的波束搜索解码器。在抽象句汇总，形态变形和机器翻译的实验结果表明，噪声信道模型优于直接模型，并且显着受益于直接模型不容易使用的不成对输出数据量的增加。

##### URL
[https://arxiv.org/abs/1611.02554](https://arxiv.org/abs/1611.02554)

##### PDF
[https://arxiv.org/pdf/1611.02554](https://arxiv.org/pdf/1611.02554)

