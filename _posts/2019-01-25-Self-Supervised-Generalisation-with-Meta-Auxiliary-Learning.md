---
layout: post
title: "Self-Supervised Generalisation with Meta Auxiliary Learning"
date: 2019-01-25 15:46:59
categories: arXiv_CV
tags: arXiv_CV NMT
author: Shikun Liu, Andrew J. Davison, Edward Johns
mathjax: true
---

* content
{:toc}

##### Abstract
Learning with auxiliary tasks has been shown to improve the generalisation of a primary task. However, this comes at the cost of manually-labelling additional tasks which may, or may not, be useful for the primary task. We propose a new method which automatically learns labels for an auxiliary task, such that any supervised learning task can be improved without requiring access to additional data. The approach is to train two neural networks: a label-generation network to predict the auxiliary labels, and a multi-task network to train the primary task alongside the auxiliary task. The loss for the label-generation network incorporates the multi-task network's performance, and so this interaction between the two networks can be seen as a form of meta learning. We show that our proposed method, Meta AuXiliary Learning (MAXL), outperforms single-task learning on 7 image datasets by a significant margin, without requiring additional auxiliary labels. We also show that MAXL outperforms several other baselines for generating auxiliary labels, and is even competitive when compared with human-defined auxiliary labels. The self-supervised nature of our method leads to a promising new direction towards automated generalisation. The source code is available at \url{https://github.com/lorenmt/maxl}.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.08933](http://arxiv.org/abs/1901.08933)

##### PDF
[http://arxiv.org/pdf/1901.08933](http://arxiv.org/pdf/1901.08933)

