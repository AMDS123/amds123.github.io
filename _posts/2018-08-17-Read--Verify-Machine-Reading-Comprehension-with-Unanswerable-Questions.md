---
layout: post
title: "Read + Verify: Machine Reading Comprehension with Unanswerable Questions"
date: 2018-08-17 05:18:52
categories: arXiv_CL
tags: arXiv_CL Detection
author: Minghao Hu, Furu wei, Yuxing Peng, Zhen Huang, Nan Yang, Ming Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
Machine reading comprehension with unanswerable questions aims to abstain from answering when no answer can be inferred. Previous works using an additional no-answer option attempt to extract answers and detect unanswerable questions simultaneously, but they have struggled to produce high-quality answers and often misclassify questions. In this paper, we propose a novel read-then-verify system that combines a base neural reader with a sentence-level answer verifier trained to further validate if the predicted answer is entailed by input snippets. Moreover, we augment the base reader with two auxiliary losses to better handle answer extraction and no-answer detection respectively, and investigate three different architectures for the answer verifier. Our experiments on the SQuAD 2.0 dataset show that our system can achieve a score of 74.8 F1 on the development set, outperforming the previous best published model by more than 7 points.

##### Abstract (translated by Google)
具有无法回答的问题的机器阅读理解旨在在无法推断出答案时避免回答。以前的工作使用额外的无应答选项尝试同时提取答案并检测无法回答的问题，但他们一直在努力产生高质量的答案并经常错误地分类问题。在本文中，我们提出了一种新颖的读取 - 验证系统，该系统将基础神经读取器与经过训练的句子级答案验证器相结合，以进一步验证输入片段是否包含预测答案。此外，我们用两个辅助损耗增加了基本读取器，以便更好地分别处理答案提取和无应答检测，并为答案验证器研究三种不同的体系结构。我们在SQUAD 2.0数据集上的实验表明，我们的系统在开发集上可以达到74.8 F1的分数，优于之前的最佳发布模型超过7分。

##### URL
[http://arxiv.org/abs/1808.05759](http://arxiv.org/abs/1808.05759)

##### PDF
[http://arxiv.org/pdf/1808.05759](http://arxiv.org/pdf/1808.05759)

