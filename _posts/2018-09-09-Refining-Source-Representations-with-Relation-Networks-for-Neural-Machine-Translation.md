---
layout: post
title: "Refining Source Representations with Relation Networks for Neural Machine Translation"
date: 2018-09-09 16:26:43
categories: arXiv_AI
tags: arXiv_AI Knowledge Attention Relation
author: Wen Zhang, Jiawei Hu, Yang Feng, Qun Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Although neural machine translation with the encoder-decoder framework has achieved great success recently, it still suffers drawbacks of forgetting distant information, which is an inherent disadvantage of recurrent neural network structure, and disregarding relationship between source words during encoding step. Whereas in practice, the former information and relationship are often useful in current step. We target on solving these problems and thus introduce relation networks to learn better representations of the source. The relation networks are able to facilitate memorization capability of recurrent neural network via associating source words with each other, this would also help retain their relationships. Then the source representations and all the relations are fed into the attention component together while decoding, with the main encoder-decoder framework unchanged. Experiments on several datasets show that our method can improve the translation performance significantly over the conventional encoder-decoder model and even outperform the approach involving supervised syntactic knowledge.

##### Abstract (translated by Google)
虽然最近使用编码器 - 解码器框架的神经机器翻译取得了巨大的成功，但它仍然存在遗忘远程信息的缺点，这是回归神经网络结构的固有缺点，并且在编码步骤期间忽略了源词之间的关系。而在实践中，以前的信息和关系在当前步骤中通常是有用的。我们的目标是解决这些问题，从而引入关系网络来学习更好的源代表。关系网络能够通过将源词相互关联来促进递归神经网络的记忆能力，这也有助于保持它们之间的关系。然后在解码时将源表示和所有关系一起馈送到关注组件，主编码器 - 解码器框架保持不变。对几个数据集的实验表明，与传统的编码器 - 解码器模型相比，我们的方法可以显着提高翻译性能，甚至优于涉及监督语法知识的方法。

##### URL
[http://arxiv.org/abs/1805.11154](http://arxiv.org/abs/1805.11154)

##### PDF
[http://arxiv.org/pdf/1805.11154](http://arxiv.org/pdf/1805.11154)

