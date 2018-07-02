---
layout: post
title: "Neural Machine Translation with Key-Value Memory-Augmented Attention"
date: 2018-06-29 02:06:00
categories: arXiv_CL
tags: arXiv_CL Attention NMT
author: Fandong Meng, Zhaopeng Tu, Yong Cheng, Haiyang Wu, Junjie Zhai, Yuekui Yang, Di Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Although attention-based Neural Machine Translation (NMT) has achieved remarkable progress in recent years, it still suffers from issues of repeating and dropping translations. To alleviate these issues, we propose a novel key-value memory-augmented attention model for NMT, called KVMEMATT. Specifically, we maintain a timely updated keymemory to keep track of attention history and a fixed value-memory to store the representation of source sentence throughout the whole translation process. Via nontrivial transformations and iterative interactions between the two memories, the decoder focuses on more appropriate source word(s) for predicting the next target word at each decoding step, therefore can improve the adequacy of translations. Experimental results on Chinese=&gt;English and WMT17 German&lt;=&gt;English translation tasks demonstrate the superiority of the proposed model.

##### Abstract (translated by Google)
尽管近年来基于注意力的神经机器翻译（Neural Machine Translation，NMT）取得了显着的进步，但仍存在翻译重复和丢失的问题。为缓解这些问题，我们提出了一种新型的NMT关键值记忆增强关注模型，称为KVMEMATT。具体而言，我们保持及时更新的密钥存储器以跟踪注意历史记录和固定值存储器，以在整个翻译过程中存储源句子的表示。通过两个存储器之间的非平凡转换和迭代交互，解码器专注于在每个解码步骤预测下一个目标词的更合适的源词，因此可以提高翻译的充分性。汉语=>英语和WMT17德语=>英语翻译任务的实验结果证明了所提出的模型的优越性。

##### URL
[http://arxiv.org/abs/1806.11249](http://arxiv.org/abs/1806.11249)

##### PDF
[http://arxiv.org/pdf/1806.11249](http://arxiv.org/pdf/1806.11249)

