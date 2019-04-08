---
layout: post
title: "Complexity-Weighted Loss and Diverse Reranking for Sentence Simplification"
date: 2019-04-04 19:47:17
categories: arXiv_CL
tags: arXiv_CL Reinforcement_Learning
author: Reno Kriz, João Sedoc, Marianna Apidianaki, Carolina Zheng, Gaurav Kumar, Eleni Miltsakaki, Chris Callison-Burch
mathjax: true
---

* content
{:toc}

##### Abstract
Sentence simplification is the task of rewriting texts so they are easier to understand. Recent research has applied sequence-to-sequence (Seq2Seq) models to this task, focusing largely on training-time improvements via reinforcement learning and memory augmentation. One of the main problems with applying generic Seq2Seq models for simplification is that these models tend to copy directly from the original sentence, resulting in outputs that are relatively long and complex. We aim to alleviate this issue through the use of two main techniques. First, we incorporate content word complexities, as predicted with a leveled word complexity model, into our loss function during training. Second, we generate a large set of diverse candidate simplifications at test time, and rerank these to promote fluency, adequacy, and simplicity. Here, we measure simplicity through a novel sentence complexity model. These extensions allow our models to perform competitively with state-of-the-art systems while generating simpler sentences. We report standard automatic and human evaluation metrics.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1904.02767](https://arxiv.org/abs/1904.02767)

##### PDF
[https://arxiv.org/pdf/1904.02767](https://arxiv.org/pdf/1904.02767)

