---
layout: post
title: "On Tree-Based Neural Sentence Modeling"
date: 2018-08-29 05:32:17
categories: arXiv_CL
tags: arXiv_CL
author: Haoyue Shi, Hao Zhou, Jiaze Chen, Lei Li
mathjax: true
---

* content
{:toc}

##### Abstract
Neural networks with tree-based sentence encoders have shown better results on many downstream tasks. Most of existing tree-based encoders adopt syntactic parsing trees as the explicit structure prior. To study the effectiveness of different tree structures, we replace the parsing trees with trivial trees (i.e., binary balanced tree, left-branching tree and right-branching tree) in the encoders. Though trivial trees contain no syntactic information, those encoders get competitive or even better results on all of the ten downstream tasks we investigated. This surprising result indicates that explicit syntax guidance may not be the main contributor to the superior performances of tree-based neural sentence modeling. Further analysis show that tree modeling gives better results when crucial words are closer to the final representation. Additional experiments give more clues on how to design an effective tree-based encoder. Our code is open-source and available at https://github.com/ExplorerFreda/TreeEnc.

##### Abstract (translated by Google)
具有基于树的句子编码器的神经网络已经在许多下游任务上显示出更好的结果。大多数现有的基于树的编码器采用语法分析树作为显式结构先验。为了研究不同树结构的有效性，我们用编码器中的普通树（即二叉平衡树，左分支树和右分支树）替换解析树。虽然琐碎的树不包含语法信息，但这些编码器在我们调查的所有十个下游任务中都具有竞争力甚至更好的结果。这一令人惊讶的结果表明，明确的语法指导可能不是基于树的神经句建模的优越性能的主要贡献者。进一步的分析表明，当关键词更接近最终表示时，树建模会给出更好的结果。其他实验为如何设计有效的基于树的编码器提供了更多线索。我们的代码是开源的，可从https://github.com/ExplorerFreda/TreeEnc获得。

##### URL
[http://arxiv.org/abs/1808.09644](http://arxiv.org/abs/1808.09644)

##### PDF
[http://arxiv.org/pdf/1808.09644](http://arxiv.org/pdf/1808.09644)

