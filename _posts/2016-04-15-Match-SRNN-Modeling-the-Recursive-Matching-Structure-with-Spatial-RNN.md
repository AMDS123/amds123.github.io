---
layout: post
title: "Match-SRNN: Modeling the Recursive Matching Structure with Spatial RNN"
date: 2016-04-15 07:23:53
categories: arXiv_SD
tags: arXiv_SD RNN Deep_Learning
author: Shengxian Wan, Yanyan Lan, Jun Xu, Jiafeng Guo, Liang Pang, Xueqi Cheng
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic matching, which aims to determine the matching degree between two texts, is a fundamental problem for many NLP applications. Recently, deep learning approach has been applied to this problem and significant improvements have been achieved. In this paper, we propose to view the generation of the global interaction between two texts as a recursive process: i.e. the interaction of two texts at each position is a composition of the interactions between their prefixes as well as the word level interaction at the current position. Based on this idea, we propose a novel deep architecture, namely Match-SRNN, to model the recursive matching structure. Firstly, a tensor is constructed to capture the word level interactions. Then a spatial RNN is applied to integrate the local interactions recursively, with importance determined by four types of gates. Finally, the matching score is calculated based on the global interaction. We show that, after degenerated to the exact matching scenario, Match-SRNN can approximate the dynamic programming process of longest common subsequence. Thus, there exists a clear interpretation for Match-SRNN. Our experiments on two semantic matching tasks showed the effectiveness of Match-SRNN, and its ability of visualizing the learned matching structure.

##### Abstract (translated by Google)
旨在确定两个文本之间匹配程度的语义匹配是许多NLP应用程序的基本问题。最近，深度学习方法已经应用于这个问题，并取得了显着的改善。在本文中，我们建议将两个文本之间的全局交互作为一个递归过程进行查看：即每个位置上两个文本的交互是它们前缀之间交互的组合，以及当前的字级交互位置。基于这个思想，我们提出了一种新颖的深层架构，即Match-SRNN来对递归匹配结构进行建模。首先构造一个张量来捕捉单词级别的交互。然后应用空间RNN递归地整合局部交互，重要性由四种类型的门决定。最后，匹配分数是基于全局交互计算的。我们证明，在退化到完全匹配的情景之后，Match-SRNN可以近似最长公共子序列的动态规划过程。因此，Match-SRNN有一个明确的解释。我们对两个语义匹配任务的实验表明了Match-SRNN的有效性，以及对学习匹配结构进行可视化的能力。

##### URL
[https://arxiv.org/abs/1604.04378](https://arxiv.org/abs/1604.04378)

##### PDF
[https://arxiv.org/pdf/1604.04378](https://arxiv.org/pdf/1604.04378)

