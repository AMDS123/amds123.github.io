---
layout: post
title: "Multilingual Training and Cross-lingual Adaptation on CTC-based Acoustic Model"
date: 2018-01-23 14:35:03
categories: arXiv_SD
tags: arXiv_SD Speech_Recognition Classification Recognition
author: Sibo Tong, Philip N. Garner, Herv&#xe9; Bourlard
mathjax: true
---

* content
{:toc}

##### Abstract
Multilingual models for Automatic Speech Recognition (ASR) are attractive as they have been shown to benefit from more training data, and better lend themselves to adaptation to under-resourced languages. However, initialisation from monolingual context-dependent models leads to an explosion of context-dependent states. Connectionist Temporal Classification (CTC) is a potential solution to this as it performs well with monophone labels. 
 We investigate multilingual CTC in the context of adaptation and regularisation techniques that have been shown to be beneficial in more conventional contexts. The multilingual model is trained to model a universal International Phonetic Alphabet (IPA)-based phone set using the CTC loss function. Learning Hidden Unit Contribution (LHUC) is investigated to perform language adaptive training. In addition, dropout during cross-lingual adaptation is also studied and tested in order to mitigate the overfitting problem. 
 Experiments show that the performance of the universal phoneme-based CTC system can be improved by applying LHUC and it is extensible to new phonemes during cross-lingual adaptation. Updating all the parameters shows consistent improvement on limited data. Applying dropout during adaptation can further improve the system and achieve competitive performance with Deep Neural Network / Hidden Markov Model (DNN/HMM) systems on limited data.

##### Abstract (translated by Google)
自动语音识别（ASR）的多语言模型具有吸引力，因为它们已经被证明可以从更多的训练数据中受益，并且更好地适应资源不足的语言。然而，来自单语环境相关模型的初始化导致情境依赖状态的爆发。连接主义者时间分类（CTC）是一个潜在的解决方案，因为它与单音标签表现良好。
 我们调查多种语言的四氯化碳在适应和正规化技术的背景下，已被证明是在更传统的情况下是有益的。多语言模型经过培训，可以模拟使用CTC丢失功能的国际普通国际音标（IPA）电话机。学习隐性单位贡献（LHUC）进行调查，以进行语言适应性训练。此外，跨语言适应中的辍学也被研究和测试，以减轻过度适应问题。
 实验表明，通用音位CTC系统的性能可以通过应用LHUC来提高，并且可以在跨语言适应期间对新音素进行扩展。更新所有参数显示有限的数据一致的改进。在适应过程中应用压差可以进一步改善系统，并在有限的数据上利用深度神经网络/隐马尔可夫模型（DNN / HMM）系统实现竞争性能。

##### URL
[http://arxiv.org/abs/1711.10025](http://arxiv.org/abs/1711.10025)

##### PDF
[http://arxiv.org/pdf/1711.10025](http://arxiv.org/pdf/1711.10025)

