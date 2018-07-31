---
layout: post
title: "Training Neural Machine Translation using Word Embedding-based Loss"
date: 2018-07-30 08:11:52
categories: arXiv_CL
tags: arXiv_CL Embedding NMT
author: Katsuki Chousa, Katsuhito Sudoh, Satoshi Nakamura
mathjax: true
---

* content
{:toc}

##### Abstract
In neural machine translation (NMT), the computational cost at the output layer increases with the size of the target-side vocabulary. Using a limited-size vocabulary instead may cause a significant decrease in translation quality. This trade-off is derived from a softmax-based loss function that handles in-dictionary words independently, in which word similarity is not considered. In this paper, we propose a novel NMT loss function that includes word similarity in forms of distances in a word embedding space. The proposed loss function encourages an NMT decoder to generate words close to their references in the embedding space; this helps the decoder to choose similar acceptable words when the actual best candidates are not included in the vocabulary due to its size limitation. In experiments using ASPEC Japanese-to-English and IWSLT17 English-to-French data sets, the proposed method showed improvements against a standard NMT baseline in both datasets; especially with IWSLT17 En-Fr, it achieved up to +1.72 in BLEU and +1.99 in METEOR. When the target-side vocabulary was very limited to 1,000 words, the proposed method demonstrated a substantial gain, +1.72 in METEOR with ASPEC Ja-En.

##### Abstract (translated by Google)
在神经机器翻译（NMT）中，输出层的计算成本随着目标侧词汇的大小而增加。使用有限大小的词汇表可能会导致翻译质量显着下降。这种权衡取决于基于softmax的损失函数，该函数独立地处理字典单词，其中不考虑单词相似性。在本文中，我们提出了一种新的NMT损失函数，其包括在字嵌入空间中的距离形式的单词相似性。所提出的损失函数鼓励NMT解码器在嵌入空间中生成接近其参考的字;这有助于解码器在实际最佳候选者由于其大小限制而未包括在词汇表中时选择类似的可接受单词。在使用ASPEC日语 - 英语和IWSLT17英语 - 法语数据集的实验中，所提出的方法显示了对两个数据集中的标准NMT基线的改进;特别是对于IWSLT17 En-Fr，它在BLEU中达到了+1.72，在METEOR中达到了1.1.99。当目标方词汇量非常限于1,000个单词时，所提出的方法在ASPE Ja-En的METEOR中获得了显着的增益，达到了1.72。

##### URL
[http://arxiv.org/abs/1807.11219](http://arxiv.org/abs/1807.11219)

##### PDF
[http://arxiv.org/pdf/1807.11219](http://arxiv.org/pdf/1807.11219)

