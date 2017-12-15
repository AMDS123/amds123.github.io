---
layout: post
title: "Logical Parsing from Natural Language Based on a Neural Translation Model"
date: 2017-05-09 15:35:25
categories: arXiv_CL
tags: arXiv_CL Attention Face
author: Liang Li, Pengyu Li, Yifan Liu, Tao Wan, Zengchang Qin
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic parsing has emerged as a significant and powerful paradigm for natural language interface and question answering systems. Traditional methods of building a semantic parser rely on high-quality lexicons, hand-crafted grammars and linguistic features which are limited by applied domain or representation. In this paper, we propose a general approach to learn from denotations based on Seq2Seq model augmented with attention mechanism. We encode input sequence into vectors and use dynamic programming to infer candidate logical forms. We utilize the fact that similar utterances should have similar logical forms to help reduce the searching space. Under our learning policy, the Seq2Seq model can learn mappings gradually with noises. Curriculum learning is adopted to make the learning smoother. We test our method on the arithmetic domain which shows our model can successfully infer the correct logical forms and learn the word meanings, compositionality and operation orders simultaneously.

##### Abstract (translated by Google)
语义分析已经成为自然语言界面和问答系统的重要而强大的范例。传统的构建语义分析器的方法依赖于高质量的词典，手工制作的语法和受应用领域或表示限制的语言特征。在本文中，我们提出了一种基于Seq2Seq模型和注意机制的一般方法。我们将输入序列编码成矢量，并使用动态编程来推断候选逻辑形式。我们利用类似的话语应该有相似的逻辑形式来帮助减少搜索空间的事实。根据我们的学习策略，Seq2Seq模型可以逐渐学习噪声映射。采用课程学习使学习更顺畅。我们在算术域上测试了我们的方法，这表明我们的模型能够成功推断出正确的逻辑形式，并同时学习单词的意义，合成性和操作顺序。

##### URL
[https://arxiv.org/abs/1705.03389](https://arxiv.org/abs/1705.03389)

##### PDF
[https://arxiv.org/pdf/1705.03389](https://arxiv.org/pdf/1705.03389)

