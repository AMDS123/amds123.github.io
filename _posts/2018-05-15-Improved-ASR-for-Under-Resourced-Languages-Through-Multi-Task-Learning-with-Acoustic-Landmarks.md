---
layout: post
title: "Improved ASR for Under-Resourced Languages Through Multi-Task Learning with Acoustic Landmarks"
date: 2018-05-15 05:46:23
categories: arXiv_CL
tags: arXiv_CL Salient Speech_Recognition Recognition
author: Di He, Boon Pang Lim, Xuesong Yang, Mark Hasegawa-Johnson, Deming Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Furui first demonstrated that the identity of both consonant and vowel can be perceived from the C-V transition; later, Stevens proposed that acoustic landmarks are the primary cues for speech perception, and that steady-state regions are secondary or supplemental. Acoustic landmarks are perceptually salient, even in a language one doesn't speak, and it has been demonstrated that non-speakers of the language can identify features such as the primary articulator of the landmark. These factors suggest a strategy for developing language-independent automatic speech recognition: landmarks can potentially be learned once from a suitably labeled corpus and rapidly applied to many other languages. This paper proposes enhancing the cross-lingual portability of a neural network by using landmarks as the secondary task in multi-task learning (MTL). The network is trained in a well-resourced source language with both phone and landmark labels (English), then adapted to an under-resourced target language with only word labels (Iban). Landmark-tasked MTL reduces source-language phone error rate by 2.9% relative, and reduces target-language word error rate by 1.9%-5.9% depending on the amount of target-language training data. These results suggest that landmark-tasked MTL causes the DNN to learn hidden-node features that are useful for cross-lingual adaptation.

##### Abstract (translated by Google)
古井第一次证明，可以从C-V转变中感知到辅音和元音的身份;后来，史蒂文斯提出声学标志是语音感知的主要线索，稳态区域是次要的或补充的。即使以一种不会说话的语言，声学地标也是显而易见的，并且已经证明，语言的非说话者可以识别诸如地标的主要发声器之类的特征。这些因素表明了开发与语言无关的自动语音识别的策略：地标可以从适当标记的语料库中学习一次，并且可以快速应用于许多其他语言。本文提出了通过将地标作为多任务学习（MTL）中的次要任务来提高神经网络的跨语言可移植性。该网络以资源丰富的源语言进行培训，同时使用电话和地标标签（英语），然后适用于资源不足的目标语言，只有文字标签（Iban）。具有里程碑意义的MTL将源语言手机出错率相对降低了2.9％，并且根据目标语言培训数据的量将目标语言字错误率降低了1.9％-5.9％。这些结果表明，具有里程碑意义的MTL导致DNN学习对跨语言适应有用的隐藏节点特征。

##### URL
[http://arxiv.org/abs/1805.05574](http://arxiv.org/abs/1805.05574)

##### PDF
[http://arxiv.org/pdf/1805.05574](http://arxiv.org/pdf/1805.05574)

