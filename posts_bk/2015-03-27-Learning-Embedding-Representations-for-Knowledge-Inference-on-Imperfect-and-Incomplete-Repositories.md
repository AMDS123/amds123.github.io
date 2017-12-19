---
layout: post
title: "Learning Embedding Representations for Knowledge Inference on Imperfect and Incomplete Repositories"
date: 2015-03-27 17:13:03
categories: arXiv_CL
tags: arXiv_CL Knowledge Embedding Inference Classification Prediction Relation
author: Miao Fan, Qiang Zhou, Thomas Fang Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
This paper considers the problem of knowledge inference on large-scale imperfect repositories with incomplete coverage by means of embedding entities and relations at the first attempt. We propose IIKE (Imperfect and Incomplete Knowledge Embedding), a probabilistic model which measures the probability of each belief, i.e. $\langle h,r,t\rangle$, in large-scale knowledge bases such as NELL and Freebase, and our objective is to learn a better low-dimensional vector representation for each entity ($h$ and $t$) and relation ($r$) in the process of minimizing the loss of fitting the corresponding confidence given by machine learning (NELL) or crowdsouring (Freebase), so that we can use $||{\bf h} + {\bf r} - {\bf t}||$ to assess the plausibility of a belief when conducting inference. We use subsets of those inexact knowledge bases to train our model and test the performances of link prediction and triplet classification on ground truth beliefs, respectively. The results of extensive experiments show that IIKE achieves significant improvement compared with the baseline and state-of-the-art approaches.

##### Abstract (translated by Google)
本文首先尝试通过嵌入实体和关系的方式来考虑不完全覆盖的大规模不完全知识库的知识推理问题。我们提出了IIKE（Imperfect and Incomplete Knowledge Embedding），它是一个概率模型，用来度量每个信念在NELL和Freebase等大规模知识库中的概率，也就是我们的目标是在最小化由机器学习（NELL）或人群覆盖给出的相应置信度的拟合损失的过程中，为每个实体（$ h $和$ t $）和关系（$ r $）学习更好的低维向量表示（Freebase），这样我们可以用$ || {\ bf h} + {\ bf r}  -  {\ bf t} || $来评估推论时信仰的合理性。我们使用这些不精确知识库的子集来训练我们的模型，并分别测试链接预测和三重分类在地面真值信念上的表现。广泛的实验结果表明，与基线和最先进的方法相比，IIKE取得了显着的改善。

##### URL
[https://arxiv.org/abs/1503.08155](https://arxiv.org/abs/1503.08155)

##### PDF
[https://arxiv.org/pdf/1503.08155](https://arxiv.org/pdf/1503.08155)

