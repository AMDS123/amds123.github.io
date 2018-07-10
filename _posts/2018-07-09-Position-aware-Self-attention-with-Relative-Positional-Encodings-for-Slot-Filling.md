---
layout: post
title: "Position-aware Self-attention with Relative Positional Encodings for Slot Filling"
date: 2018-07-09 11:34:13
categories: arXiv_AI
tags: arXiv_AI Relation_Extraction Attention CNN Relation
author: Ivan Bilan, Benjamin Roth
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes how to apply self-attention with relative positional encodings to the task of relation extraction. We propose to use the self-attention encoder layer together with an additional position-aware attention layer that takes into account positions of the query and the object in the sentence. The self-attention encoder also uses a custom implementation of relative positional encodings which allow each word in the sentence to take into account its left and right context. The evaluation of the model is done on the TACRED dataset. The proposed model relies only on attention (no recurrent or convolutional layers are used), while improving performance w.r.t. the previous state of the art.

##### Abstract (translated by Google)
本文描述了如何将相对位置编码的自我关注应用于关系提取任务。我们建议将自我关注编码器层与另外的位置感知关注层一起使用，该关注层考虑查询的位置和句子中的对象。自我关注编码器还使用相对位置编码的自定义实现，其允许句子中的每个单词考虑其左右上下文。模型的评估在TACRED数据集上完成。所提出的模型仅依赖于注意力（不使用重复或卷积层），同时改善性能w.r.t.先前的技术水平。

##### URL
[http://arxiv.org/abs/1807.03052](http://arxiv.org/abs/1807.03052)

##### PDF
[http://arxiv.org/pdf/1807.03052](http://arxiv.org/pdf/1807.03052)

