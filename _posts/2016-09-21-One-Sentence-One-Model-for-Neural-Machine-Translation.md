---
layout: post
title: "One Sentence One Model for Neural Machine Translation"
date: 2016-09-21 10:28:57
categories: arXiv_CL
tags: arXiv_CL NMT
author: Xiaoqing Li, Jiajun Zhang, Chengqing Zong
mathjax: true
---

* content
{:toc}

##### Abstract
Neural machine translation (NMT) becomes a new state-of-the-art and achieves promising translation results using a simple encoder-decoder neural network. This neural network is trained once on the parallel corpus and the fixed network is used to translate all the test sentences. We argue that the general fixed network cannot best fit the specific test sentences. In this paper, we propose the dynamic NMT which learns a general network as usual, and then fine-tunes the network for each test sentence. The fine-tune work is done on a small set of the bilingual training data that is obtained through similarity search according to the test sentence. Extensive experiments demonstrate that this method can significantly improve the translation performance, especially when highly similar sentences are available.

##### Abstract (translated by Google)
神经机器翻译（NMT）成为一个新的最先进的技术，并使用简单的编码器 - 解码器神经网络实现了有前途的翻译结果。这个神经网络在平行语料库上训练一次，固定网络用来翻译所有的测试语句。我们认为一般的固定网络不能最好地适应特定的测试句子。在本文中，我们提出了动态NMT，像通常一样学习一般网络，然后对每个测试句子的网络进行微调。微调工作是根据测试句子通过相似性搜索得到的一小部分双语训练数据进行的。大量的实验表明，这种方法可以显着提高翻译的性能，尤其是当高度相似的句子可用时。

##### URL
[https://arxiv.org/abs/1609.06490](https://arxiv.org/abs/1609.06490)

