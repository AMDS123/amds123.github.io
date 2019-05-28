---
layout: post
title: "Simple and Effective Curriculum Pointer-Generator Networks for Reading Comprehension over Long Narratives"
date: 2019-05-26 17:56:11
categories: arXiv_AI
tags: arXiv_AI QA Attention
author: Yi Tay, Shuohang Wang, Luu Anh Tuan, Jie Fu, Minh C. Phan, Xingdi Yuan, Jinfeng Rao, Siu Cheung Hui, Aston Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper tackles the problem of reading comprehension over long narratives where documents easily span over thousands of tokens. We propose a curriculum learning (CL) based Pointer-Generator framework for reading/sampling over large documents, enabling diverse training of the neural model based on the notion of alternating contextual difficulty. This can be interpreted as a form of domain randomization and/or generative pretraining during training. To this end, the usage of the Pointer-Generator softens the requirement of having the answer within the context, enabling us to construct diverse training samples for learning. Additionally, we propose a new Introspective Alignment Layer (IAL), which reasons over decomposed alignments using block-based self-attention. We evaluate our proposed method on the NarrativeQA reading comprehension benchmark, achieving state-of-the-art performance, improving existing baselines by $51\%$ relative improvement on BLEU-4 and $17\%$ relative improvement on Rouge-L. Extensive ablations confirm the effectiveness of our proposed IAL and CL components.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.10847](http://arxiv.org/abs/1905.10847)

##### PDF
[http://arxiv.org/pdf/1905.10847](http://arxiv.org/pdf/1905.10847)

