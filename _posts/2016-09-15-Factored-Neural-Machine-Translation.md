---
layout: post
title: "Factored Neural Machine Translation"
date: 2016-09-15 13:15:01
categories: arXiv_CL
tags: arXiv_CL Attention NMT
author: Mercedes García-Martínez, Loïc Barrault, Fethi Bougares
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new approach for neural machine translation (NMT) using the morphological and grammatical decomposition of the words (factors) in the output side of the neural network. This architecture addresses two main problems occurring in MT, namely dealing with a large target language vocabulary and the out of vocabulary (OOV) words. By the means of factors, we are able to handle larger vocabulary and reduce the training time (for systems with equivalent target language vocabulary size). In addition, we can produce new words that are not in the vocabulary. We use a morphological analyser to get a factored representation of each word (lemmas, Part of Speech tag, tense, person, gender and number). We have extended the NMT approach with attention mechanism in order to have two different outputs, one for the lemmas and the other for the rest of the factors. The final translation is built using some \textit{a priori} linguistic information. We compare our extension with a word-based NMT system. The experiments, performed on the IWSLT'15 dataset translating from English to French, show that while the performance do not always increase, the system can manage a much larger vocabulary and consistently reduce the OOV rate. We observe up to 2% BLEU point improvement in a simulated out of domain translation setup.

##### Abstract (translated by Google)
我们提出了一种神经机器翻译（NMT）的新方法，使用神经网络输出侧的词（因子）的形态和语法分解。这个架构解决了MT中出现的两个主要问题，即处理大的目标语言词汇和词汇（OOV）词汇。通过因素手段，我们能够处理更大的词汇量和减少训练时间（对于具有相同目标语言词汇量的系统）。另外，我们可以产生不在词汇表中的新单词。我们使用形态学分析器来获得每个单词（引理，词性标记，时态，人物，性别和数量）的因式分解。我们将NMT方法扩展到注意机制，以便产生两个不同的结果，一个用于引理，另一个用于其他因素。最后的翻译是使用一些\ textit {先验的}语言信息来建立的。我们将我们的扩展与基于单词的NMT系统进行比较。 IWSLT'15数据集从英语翻译成法语的实验表明，虽然表现并不总是增加，但系统可以管理更大的词汇量并持续降低OOV率。我们观察到，在模拟的域转换设置中，BLEU点的改进达到了2％。

##### URL
[https://arxiv.org/abs/1609.04621](https://arxiv.org/abs/1609.04621)

##### PDF
[https://arxiv.org/pdf/1609.04621](https://arxiv.org/pdf/1609.04621)

