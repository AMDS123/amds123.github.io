---
layout: post
title: "Source-Critical Reinforcement Learning for Transferring Spoken Language Understanding to a New Language"
date: 2018-08-19 05:49:46
categories: arXiv_CL
tags: arXiv_CL Reinforcement_Learning Classification
author: He Bai, Yu Zhou, Jiajun Zhang, Liang Zhao, Mei-Yuh Hwang, Chengqing Zon
mathjax: true
---

* content
{:toc}

##### Abstract
To deploy a spoken language understanding (SLU) model to a new language, language transferring is desired to avoid the trouble of acquiring and labeling a new big SLU corpus. Translating the original SLU corpus into the target language is an attractive strategy. However, SLU corpora consist of plenty of semantic labels (slots), which general-purpose translators cannot handle well, not to mention additional culture differences. This paper focuses on the language transferring task given a tiny in-domain parallel SLU corpus. The in-domain parallel corpus can be used as the first adaptation on the general translator. But more importantly, we show how to use reinforcement learning (RL) to further finetune the adapted translator, where translated sentences with more proper slot tags receive higher rewards. We evaluate our approach on Chinese to English language transferring for SLU systems. The experimental results show that the generated English SLU corpus via adaptation and reinforcement learning gives us over 97% in the slot F1 score and over 84% accuracy in domain classification. It demonstrates the effectiveness of the proposed language transferring method. Compared with naive translation, our proposed method improves domain classification accuracy by relatively 22%, and the slot filling F1 score by relatively more than 71%.

##### Abstract (translated by Google)
为了将口语理解（SLU）模型部署到新语言，期望语言转移以避免获取和标记新的大SLU语料库的麻烦。将原始SLU语料库翻译成目标语言是一种有吸引力的策略。然而，SLU语料库由大量语义标签（插槽）组成，通用翻译者无法很好地处理，更不用说其他文化差异了。本文重点介绍了一个微小的域内并行SLU语料库的语言转移任务。域内并行语料库可以用作一般翻译器上的第一个适应。但更重要的是，我们展示了如何使用强化学习（RL）来进一步微调适应的翻译，其中具有更合适的插槽标签的翻译句子获得更高的奖励。我们评估了我们针对SLU系统进行中英文语言转换的方法。实验结果表明，通过自适应和强化学习生成的英语SLU语料库给出了超过97％的时隙F1得分和超过84％的域分类准确度。它证明了所提出的语言转移方法的有效性。与朴素翻译相比，我们提出的方法将领域分类准确率提高了22％，而填充F1分数的得分相对超过71％。

##### URL
[http://arxiv.org/abs/1808.06167](http://arxiv.org/abs/1808.06167)

##### PDF
[http://arxiv.org/pdf/1808.06167](http://arxiv.org/pdf/1808.06167)

