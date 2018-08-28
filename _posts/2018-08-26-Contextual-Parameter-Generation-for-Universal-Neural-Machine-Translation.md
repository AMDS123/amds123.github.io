---
layout: post
title: "Contextual Parameter Generation for Universal Neural Machine Translation"
date: 2018-08-26 01:17:50
categories: arXiv_CL
tags: arXiv_CL Embedding NMT Relation
author: Emmanouil Antonios Platanios, Mrinmaya Sachan, Graham Neubig, Tom Mitchell
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a simple modification to existing neural machine translation (NMT) models that enables using a single universal model to translate between multiple languages while allowing for language specific parameterization, and that can also be used for domain adaptation. Our approach requires no changes to the model architecture of a standard NMT system, but instead introduces a new component, the contextual parameter generator (CPG), that generates the parameters of the system (e.g., weights in a neural network). This parameter generator accepts source and target language embeddings as input, and generates the parameters for the encoder and the decoder, respectively. The rest of the model remains unchanged and is shared across all languages. We show how this simple modification enables the system to use monolingual data for training and also perform zero-shot translation. We further show it is able to surpass state-of-the-art performance for both the IWSLT-15 and IWSLT-17 datasets and that the learned language embeddings are able to uncover interesting relationships between languages.

##### Abstract (translated by Google)
我们提出对现有神经机器翻译（NMT）模型的简单修改，其允许使用单个通用模型在多种语言之间进行转换，同时允许语言特定参数化，并且还可以用于域适应。我们的方法不需要改变标准NMT系统的模型体系结构，而是引入新的组件，即上下文参数生成器（CPG），其生成系统的参数（例如，神经网络中的权重）。该参数生成器接受源语言嵌入和目标语言嵌入作为输入，并分别为编码器和解码器生成参数。模型的其余部分保持不变，并在所有语言中共享。我们展示了这种简单的修改如何使系统能够使用单语数据进行训练并执行零射击翻译。我们进一步表明，它能够超越IWSLT-15和IWSLT-17数据集的最新性能，并且学习的语言嵌入能够发现语言之间的有趣关系。

##### URL
[http://arxiv.org/abs/1808.08493](http://arxiv.org/abs/1808.08493)

##### PDF
[http://arxiv.org/pdf/1808.08493](http://arxiv.org/pdf/1808.08493)

