---
layout: post
title: "A Mention-Ranking Model for Abstract Anaphora Resolution"
date: 2017-07-21 12:12:04
categories: arXiv_CL
tags: arXiv_CL Represenation_Learning RNN Relation
author: Ana Marasović, Leo Born, Juri Opitz, Anette Frank
mathjax: true
---

* content
{:toc}

##### Abstract
Resolving abstract anaphora is an important, but difficult task for text understanding. Yet, with recent advances in representation learning this task becomes a more tangible aim. A central property of abstract anaphora is that it establishes a relation between the anaphor embedded in the anaphoric sentence and its (typically non-nominal) antecedent. We propose a mention-ranking model that learns how abstract anaphors relate to their antecedents with an LSTM-Siamese Net. We overcome the lack of training data by generating artificial anaphoric sentence--antecedent pairs. Our model outperforms state-of-the-art results on shell noun resolution. We also report first benchmark results on an abstract anaphora subset of the ARRAU corpus. This corpus presents a greater challenge due to a mixture of nominal and pronominal anaphors and a greater range of confounders. We found model variants that outperform the baselines for nominal anaphors, without training on individual anaphor data, but still lag behind for pronominal anaphors. Our model selects syntactically plausible candidates and -- if disregarding syntax -- discriminates candidates using deeper features.

##### Abstract (translated by Google)
解决抽象回指对于理解文本来说是一个重要而又困难的任务。然而，随着最近代表学习的进展，这个任务变成了一个更为切实的目标。抽象回指的一个中心属性是它在嵌入在照应句中的照应与其（通常是非名义的）前件之间建立了一种关系。我们提出一个提名排名模型，了解LSTM-Siamese网络中抽象的隐喻与其前因之间的关系。我们通过生成人为的照应语句 - 先行对来克服缺乏训练数据。我们的模型在shell名词解析方面胜过了最先进的结果。我们还报告ARRAU语料库抽象回指子集的第一个基准结果。这个语料库由于混合了名词性和代词性的隐喻以及更多的混杂因素而提出了更大的挑战。我们发现模型变体超过名义隐喻的基线，没有单独的数据的训练，但仍然落后于代词的隐喻。我们的模型选择句法上合理的候选人，如果忽视语法，则使用更深的特征来区分候选人。

##### URL
[https://arxiv.org/abs/1706.02256](https://arxiv.org/abs/1706.02256)

##### PDF
[https://arxiv.org/pdf/1706.02256](https://arxiv.org/pdf/1706.02256)

