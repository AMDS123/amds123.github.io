---
layout: post
title: "Recurrent Neural Machine Translation"
date: 2016-07-29 08:35:10
categories: arXiv_CL
tags: arXiv_CL Attention NMT RNN
author: Biao Zhang, Deyi Xiong, Jinsong Su
mathjax: true
---

* content
{:toc}

##### Abstract
The vanilla attention-based neural machine translation has achieved promising performance because of its capability in leveraging varying-length source annotations. However, this model still suffers from failures in long sentence translation, for its incapability in capturing long-term dependencies. In this paper, we propose a novel recurrent neural machine translation (RNMT), which not only preserves the ability to model varying-length source annotations but also better captures long-term dependencies. Instead of the conventional attention mechanism, RNMT employs a recurrent neural network to extract the context vector, where the target-side previous hidden state serves as its initial state, and the source annotations serve as its inputs. We refer to this new component as contexter. As the encoder, contexter and decoder in our model are all derivable recurrent neural networks, our model can still be trained end-to-end on large-scale corpus via stochastic algorithms. Experiments on Chinese-English translation tasks demonstrate the superiority of our model to attention-based neural machine translation, especially on long sentences. Besides, further analysis of the contexter revels that our model can implicitly reflect the alignment to source sentence.

##### Abstract (translated by Google)
基于香草注意的神经机器翻译由于其能够利用不同长度的源注释而获得了有前途的性能。然而，这种模式仍然在长句翻译方面失败，因为它无法捕捉长期的依赖关系。在本文中，我们提出了一种新颖的递归神经机器翻译（RNMT），它不仅保留了对不同长度的源注释进行建模的能力，而且更好地捕获了长期的依赖关系。 RNMT不是传统的注意机制，而是采用递归神经网络来提取上下文向量，其中目标侧以前的隐藏状态作为其初始状态，源注释作为其输入。我们把这个新的组件称为情况。作为编码器，我们模型中的编码器和解码器都是可推导的递归神经网络，我们的模型仍然可以通过随机算法在大规模语料库上进行端对端的训练。对汉英翻译任务的实验证明了我们的模型对基于注意的神经机器翻译的优越性，特别是在长句中。此外，我们的模型可以隐含地反映出源句的对应关系，进一步分析了这一争议的狂欢。

##### URL
[https://arxiv.org/abs/1607.08725](https://arxiv.org/abs/1607.08725)

##### PDF
[https://arxiv.org/pdf/1607.08725](https://arxiv.org/pdf/1607.08725)

