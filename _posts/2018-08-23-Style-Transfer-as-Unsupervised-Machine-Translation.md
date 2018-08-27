---
layout: post
title: "Style Transfer as Unsupervised Machine Translation"
date: 2018-08-23 18:18:32
categories: arXiv_CL
tags: arXiv_CL Style_Transfer Embedding NMT
author: Zhirui Zhang, Shuo Ren, Shujie Liu, Jianyong Wang, Peng Chen, Mu Li, Ming Zhou, Enhong Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Language style transferring rephrases text with specific stylistic attributes while preserving the original attribute-independent content. One main challenge in learning a style transfer system is a lack of parallel data where the source sentence is in one style and the target sentence in another style. With this constraint, in this paper, we adapt unsupervised machine translation methods for the task of automatic style transfer. We first take advantage of style-preference information and word embedding similarity to produce pseudo-parallel data with a statistical machine translation (SMT) framework. Then the iterative back-translation approach is employed to jointly train two neural machine translation (NMT) based transfer systems. To control the noise generated during joint training, a style classifier is introduced to guarantee the accuracy of style transfer and penalize bad candidates in the generated pseudo data. Experiments on benchmark datasets show that our proposed method outperforms previous state-of-the-art models in terms of both accuracy of style transfer and quality of input-output correspondence.

##### Abstract (translated by Google)
语言风格转移使用特定样式属性重新定义文本，同时保留原始属性独立内容。学习风格转移系统的一个主要挑战是缺乏并行数据，其中源句子是一种风格而目标句子是另一种风格。有了这个约束，在本文中，我们采用无监督机器翻译方法来完成自动样式转移的任务。我们首先利用样式偏好信息和单词嵌入相似性来生成具有统计机器翻译（SMT）框架的伪并行数据。然后采用迭代反向翻译方法来联合训练两个基于神经机器翻译（NMT）的传递系统。为了控制联合训练期间产生的噪声，引入了一种风格分类器以保证风格转移的准确性并惩罚生成的伪数据中的不良候选者。基准数据集上的实验表明，我们提出的方法在样式传递的准确性和输入 - 输出对应的质量方面优于先前的最先进模型。

##### URL
[http://arxiv.org/abs/1808.07894](http://arxiv.org/abs/1808.07894)

##### PDF
[http://arxiv.org/pdf/1808.07894](http://arxiv.org/pdf/1808.07894)

