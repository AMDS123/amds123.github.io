---
layout: post
title: 'Google's Neural Machine Translation System: Bridging the Gap between Human and Machine Translation'
date: 2016-10-08 19:10:41
categories: arXiv_CL
tags: arXiv_CL NMT RNN
author: Yonghui Wu, Mike Schuster, Zhifeng Chen, Quoc V. Le, Mohammad Norouzi, Wolfgang Macherey, Maxim Krikun, Yuan Cao, Qin Gao, Klaus Macherey, Jeff Klingner, Apurva Shah, Melvin Johnson, Xiaobing Liu, Łukasz Kaiser, Stephan Gouws, Yoshikiyo Kato, Taku Kudo, Hideto Kazawa, Keith Stevens, George Kurian, Nishant Patil, Wei Wang, Cliff Young, Jason Smith, Jason Riesa, Alex Rudnick, Oriol Vinyals, Greg Corrado, Macduff Hughes, Jeffrey Dean
---

* content
{:toc}

##### Abstract
Neural Machine Translation (NMT) is an end-to-end learning approach for automated translation, with the potential to overcome many of the weaknesses of conventional phrase-based translation systems. Unfortunately, NMT systems are known to be computationally expensive both in training and in translation inference. Also, most NMT systems have difficulty with rare words. These issues have hindered NMT's use in practical deployments and services, where both accuracy and speed are essential. In this work, we present GNMT, Google's Neural Machine Translation system, which attempts to address many of these issues. Our model consists of a deep LSTM network with 8 encoder and 8 decoder layers using attention and residual connections. To improve parallelism and therefore decrease training time, our attention mechanism connects the bottom layer of the decoder to the top layer of the encoder. To accelerate the final translation speed, we employ low-precision arithmetic during inference computations. To improve handling of rare words, we divide words into a limited set of common sub-word units ("wordpieces") for both input and output. This method provides a good balance between the flexibility of "character"-delimited models and the efficiency of "word"-delimited models, naturally handles translation of rare words, and ultimately improves the overall accuracy of the system. Our beam search technique employs a length-normalization procedure and uses a coverage penalty, which encourages generation of an output sentence that is most likely to cover all the words in the source sentence. On the WMT'14 English-to-French and English-to-German benchmarks, GNMT achieves competitive results to state-of-the-art. Using a human side-by-side evaluation on a set of isolated simple sentences, it reduces translation errors by an average of 60% compared to Google's phrase-based production system.

##### Abstract (translated by Google)
神经机器翻译（NMT）是自动翻译的端到端学习方法，可以克服传统的基于短语的翻译系统的许多缺点。不幸的是，NMT系统在训练和翻译推断上都是昂贵的。而且，大多数NMT系统难以用罕见的词语。这些问题妨碍了NMT在实际部署和服务中的使用，在这些部署和服务中准确性和速度都是必不可少的。在这项工作中，我们介绍GNMT，Google的神经机器翻译系统，它试图解决许多这些问题。我们的模型由一个深度LSTM网络组成，其中8个编码器和8个解码器层使用注意力和剩余连接。为了提高并行性并减少训练时间，我们的注意机制将解码器的底层连接到编码器的顶层。为了加速最终的翻译速度，我们在推理计算中使用低精度算术。为了改进对罕见词的处理，我们将词分成有限的一组共同的子词单位（“词条”），用于输入和输出。这种方法在“字符”限制模型的灵活性和“单词”限制模型的效率之间提供了良好的平衡，自然地处理了罕见字词的翻译，最终提高了系统的整体准确性。我们的波束搜索技术使用长度归一化过程，并使用一个覆盖惩罚，它鼓励生成一个最有可能覆盖源句子中所有单词的输出句子。在WMT'14英文到法文和英文到德文的基准测试中，GNMT达到了最先进的竞争结果。与Google的基于短语的生产系统相比，对一组孤立的简单句子进行人为的并排评估，平均减少了60％的翻译错误。

##### URL
[https://arxiv.org/abs/1609.08144](https://arxiv.org/abs/1609.08144)

