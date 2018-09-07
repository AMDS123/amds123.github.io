---
layout: post
title: "Narrating a Knowledge Base"
date: 2018-09-06 02:56:58
categories: arXiv_CL
tags: arXiv_CL Knowledge Attention
author: Qingyun Wang, Xiaoman Pan, Lifu Huang, Boliang Zhang, Zhiying Jiang, Heng Ji, Kevin Knight
mathjax: true
---

* content
{:toc}

##### Abstract
We aim to automatically generate natural language narratives about an input structured knowledge base (KB). We build our generation framework based on a pointer network which can copy facts from the input KB, and add two attention mechanisms: (i) slot-aware attention to capture the association between a slot type and its corresponding slot value; and (ii) a new table position self-attention to capture the inter-dependencies among related slots. For evaluation, besides standard metrics including BLEU, METEOR, and ROUGE, we also propose a \textit{KB reconstruction} based metric by extracting a KB from the generation output and comparing it with the input KB. We also create a new data set which includes 106,216 pairs of structured KBs and their corresponding natural language descriptions for two distinct entity types. Experiments show that our approach significantly outperforms state-of-the-art methods. The reconstructed KB achieves 68.8% - 72.6% F-score.

##### Abstract (translated by Google)
我们的目标是自动生成关于输入结构化知识库（KB）的自然语言叙述。我们基于指针网络构建我们的生成框架，该指针网络可以从输入KB复制事实，并添加两个注意机制：（i）插槽感知注意捕获插槽类型与其对应的插槽值之间的关联; （ii）新表位置自我注意以捕获相关时隙之间的相互依赖性。为了评估，除了标准指标（包括BLEU，METEOR和ROUGE）之外，我们还通过从生成输出中提取KB并将其与输入KB进行比较来提出基于\ textit {KB rebuore}的度量。我们还创建了一个新的数据集，其中包括106,216对结构化KB及其对应的两种不同实体类型的自然语言描述。实验表明，我们的方法明显优于最先进的方法。重建的KB达到68.8％-72.6％的F-得分。

##### URL
[http://arxiv.org/abs/1809.01797](http://arxiv.org/abs/1809.01797)

##### PDF
[http://arxiv.org/pdf/1809.01797](http://arxiv.org/pdf/1809.01797)

