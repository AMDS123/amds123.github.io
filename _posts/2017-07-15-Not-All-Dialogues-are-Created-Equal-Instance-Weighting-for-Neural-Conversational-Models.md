---
layout: post
title: "Not All Dialogues are Created Equal: Instance Weighting for Neural Conversational Models"
date: 2017-07-15 17:27:13
categories: arXiv_CL
tags: arXiv_CL Segmentation
author: Pierre Lison, Serge Bibauw
mathjax: true
---

* content
{:toc}

##### Abstract
Neural conversational models require substantial amounts of dialogue data for their parameter estimation and are therefore usually learned on large corpora such as chat forums or movie subtitles. These corpora are, however, often challenging to work with, notably due to their frequent lack of turn segmentation and the presence of multiple references external to the dialogue itself. This paper shows that these challenges can be mitigated by adding a weighting model into the architecture. The weighting model, which is itself estimated from dialogue data, associates each training example to a numerical weight that reflects its intrinsic quality for dialogue modelling. At training time, these sample weights are included into the empirical loss to be minimised. Evaluation results on retrieval-based models trained on movie and TV subtitles demonstrate that the inclusion of such a weighting model improves the model performance on unsupervised metrics.

##### Abstract (translated by Google)
神经交谈模型需要大量的对话数据用于参数估计，因此通常在诸如聊天论坛或电影字幕的大型语料库上学习。然而，这些语料库经常面临挑战，特别是由于它们经常缺乏轮流分割以及在对话本身之外存在多个参考。本文表明，通过在体系结构中添加权重模型可以缓解这些挑战。由对话数据本身估计的加权模型将每个训练示例与反映其对话建模的内在质量的数字权重相关联。在训练时间，这些样本权重被包含在最小化的经验损失中。在电影和电视字幕上训练的基于检索的模型的评估结果表明，包含这样的加权模型提高了无监督度量的模型性能。

##### URL
[https://arxiv.org/abs/1704.08966](https://arxiv.org/abs/1704.08966)

##### PDF
[https://arxiv.org/pdf/1704.08966](https://arxiv.org/pdf/1704.08966)

