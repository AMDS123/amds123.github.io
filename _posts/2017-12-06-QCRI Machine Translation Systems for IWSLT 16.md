---
layout: post
title: 'QCRI Machine Translation Systems for IWSLT 16'
date: 2017-12-06 03:19:28
categories: arXiv_CL
tags: arXiv_CL NMT
author: Nadir Durrani, Fahim Dalvi, Hassan Sajjad, Stephan Vogel
---

* content
{:toc}

##### Abstract
This paper describes QCRI's machine translation systems for the IWSLT 2016 evaluation campaign. We participated in the Arabic->English and English->Arabic tracks. We built both Phrase-based and Neural machine translation models, in an effort to probe whether the newly emerged NMT framework surpasses the traditional phrase-based systems in Arabic-English language pairs. We trained a very strong phrase-based system including, a big language model, the Operation Sequence Model, Neural Network Joint Model and Class-based models along with different domain adaptation techniques such as MML filtering, mixture modeling and using fine tuning over NNJM model. However, a Neural MT system, trained by stacking data from different genres through fine-tuning, and applying ensemble over 8 models, beat our very strong phrase-based system by a significant 2 BLEU points margin in Arabic->English direction. We did not obtain similar gains in the other direction but were still able to outperform the phrase-based system. We also applied system combination on phrase-based and NMT outputs.

##### Abstract (translated by Google)
本文介绍了适用于IWSLT 2016评估活动的QCRI机器翻译系统。我们参加了阿拉伯语 - >英语和英语 - >阿拉伯语的曲目。我们建立了基于短语的机器翻译模型和神经机器翻译模型，试图探讨新出现的NMT框架是否超越了阿拉伯语 - 英语对的传统短语系统。我们训练了一个非常强大的基于短语的系统，包括大语言模型，操作序列模型，神经网络联合模型和基于类的模型，以及不同的领域适应技术，如MML滤波，混合建模和在NNJM模型上使用微调。然而，神经MT系统通过微调叠加不同类型的数据进行训练，并将整个系统应用于8个模型，在阿拉伯语 - >英语方向上，以强大的2 BLEU点边缘击败了我们非常强大的基于短语的系统。我们没有在另一个方面获得类似的收益，但仍然能够胜过基于短语的系统。我们还在短语和NMT输出上应用了系统组合。

##### URL
[https://arxiv.org/abs/1701.03924](https://arxiv.org/abs/1701.03924)

