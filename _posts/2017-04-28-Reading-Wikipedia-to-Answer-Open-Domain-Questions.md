---
layout: post
title: "Reading Wikipedia to Answer Open-Domain Questions"
date: 2017-04-28 03:53:14
categories: arXiv_SD
tags: arXiv_SD Knowledge QA
author: Danqi Chen, Adam Fisch, Jason Weston, Antoine Bordes
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes to tackle open- domain question answering using Wikipedia as the unique knowledge source: the answer to any factoid question is a text span in a Wikipedia article. This task of machine reading at scale combines the challenges of document retrieval (finding the relevant articles) with that of machine comprehension of text (identifying the answer spans from those articles). Our approach combines a search component based on bigram hashing and TF-IDF matching with a multi-layer recurrent neural network model trained to detect answers in Wikipedia paragraphs. Our experiments on multiple existing QA datasets indicate that (1) both modules are highly competitive with respect to existing counterparts and (2) multitask learning using distant supervision on their combination is an effective complete system on this challenging task.

##### Abstract (translated by Google)
本文提出利用维基百科作为独特的知识来解决开放领域的问题答案：任何事实问题的答案都是维基百科文章中的文本跨度。这种大规模机器阅读的任务将文件检索（找到相关文章）与机器理解文本（识别这些文章的答案）的挑战相结合。我们的方法结合了一个基于二元哈希和TF-IDF匹配的搜索组件和一个多层递归神经网络模型，这个模型被训练用于检测Wikipedia段落中的答案。我们对多个现有QA数据集进行的实验表明：（1）两个模块对现有对象都具有很强的竞争力;（2）多任务学习使用远程监督对他们的组合是一个有效的完整系统。

##### URL
[https://arxiv.org/abs/1704.00051](https://arxiv.org/abs/1704.00051)

##### PDF
[https://arxiv.org/pdf/1704.00051](https://arxiv.org/pdf/1704.00051)

