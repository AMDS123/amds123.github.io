---
layout: post
title: "Neural Name Translation Improves Neural Machine Translation"
date: 2016-07-07 02:25:57
categories: arXiv_CL
tags: arXiv_CL NMT
author: Xiaoqing Li, Jiajun Zhang, Chengqing Zong
mathjax: true
---

* content
{:toc}

##### Abstract
In order to control computational complexity, neural machine translation (NMT) systems convert all rare words outside the vocabulary into a single unk symbol. Previous solution (Luong et al., 2015) resorts to use multiple numbered unks to learn the correspondence between source and target rare words. However, testing words unseen in the training corpus cannot be handled by this method. And it also suffers from the noisy word alignment. In this paper, we focus on a major type of rare words -- named entity (NE), and propose to translate them with character level sequence to sequence model. The NE translation model is further used to derive high quality NE alignment in the bilingual training corpus. With the integration of NE translation and alignment modules, our NMT system is able to surpass the baseline system by 2.9 BLEU points on the Chinese to English task.

##### Abstract (translated by Google)
为了控制计算复杂性，神经机器翻译（NMT）系统将词汇表以外的所有稀有词汇转换成单一的unk符号。以前的解决方案（Luong et al。，2015）假定使用多个编号的unks来学习源和目标罕见单词之间的对应关系。然而，在训练语料库中看不见的词语不能用这种方法处理。而且还会受到嘈杂的单词对齐的影响。在本文中，我们主要讨论一种罕见的单词 - 实体（NE）的主要类型，并将它们与字符级序列一起转化为序列模型。 NE翻译模型还用于在双语训练语料库中导出高质量的NE对齐。通过NE翻译和对齐模块的整合，我们的NMT系统能够在中英文任务上超过基线系统2.9 BLEU点。

##### URL
[https://arxiv.org/abs/1607.01856](https://arxiv.org/abs/1607.01856)

