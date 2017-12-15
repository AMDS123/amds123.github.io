---
layout: post
title: "Tree-Structured Neural Machine for Linguistics-Aware Sentence Generation"
date: 2017-11-21 05:31:23
categories: arXiv_CL
tags: arXiv_CL
author: Ganbin Zhou, Ping Luo, Rongyu Cao, Yijun Xiao, Fen Lin, Bo Chen, Qing He
mathjax: true
---

* content
{:toc}

##### Abstract
Different from other sequential data, sentences in natural language are structured by linguistic grammars. Previous generative conversational models with chain-structured decoder ignore this structure in human language and might generate plausible responses with less satisfactory relevance and fluency. In this study, we aim to incorporate the results from linguistic analysis into the process of sentence generation for high-quality conversation generation. Specifically, we use a dependency parser to transform each response sentence into a dependency tree and construct a training corpus of sentence-tree pairs. A tree-structured decoder is developed to learn the mapping from a sentence to its tree, where different types of hidden states are used to depict the local dependencies from an internal tree node to its children. For training acceleration, we propose a tree canonicalization method, which transforms trees into equivalent ternary trees. Then, with a proposed tree-structured search method, the model is able to generate the most probable responses in the form of dependency trees, which are finally flattened into sequences as the system output. Experimental results demonstrate that the proposed X2Tree framework outperforms baseline methods over 11.15% increase of acceptance ratio.

##### Abstract (translated by Google)
与其他顺序数据不同，自然语言的句子是由语言文法构成的。先前的链式结构解码器的生成对话模型忽略了人类语言中的这种结构，并且可能产生似乎不太令人满意的相关性和流畅性的似是而非的反应。在这项研究中，我们的目标是将语言分析的结果纳入高质量会话生成的句子生成过程。具体而言，我们使用依赖解析器将每个响应句变换为依赖树，构造句子树对的训练语料库。开发了一个树形结构的解码器来学习从一个句子到它的树的映射，其中不同类型的隐藏状态被用来描述从一个内部树节点到它的子节点的本地依赖。为了加速训练，我们提出了一种树形标准化方法，将树木转化为等价的三元树。然后，利用所提出的树形结构搜索方法，该模型能够以依赖树的形式产生最可能的响应，最终将其平滑化为序列作为系统输出。实验结果表明，所提出的X2Tree框架比基准方法优于超过11.15％的接受率。

##### URL
[https://arxiv.org/abs/1705.00321](https://arxiv.org/abs/1705.00321)

##### PDF
[https://arxiv.org/pdf/1705.00321](https://arxiv.org/pdf/1705.00321)

