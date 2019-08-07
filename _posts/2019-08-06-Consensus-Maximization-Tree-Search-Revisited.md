---
layout: post
title: "Consensus Maximization Tree Search Revisited"
date: 2019-08-06 08:54:04
categories: arXiv_CV
tags: arXiv_CV
author: Zhipeng Cai, Tat-Jun Chin, Vladlen Koltun
mathjax: true
---

* content
{:toc}

##### Abstract
Consensus maximization is widely used for robust fitting in computer vision. However, solving it exactly, i.e., finding the globally optimal solution, is intractable. A* tree search, which has been shown to be fixed-parameter tractable, is one of the most efficient exact methods, though it is still limited to small inputs. We make two key contributions towards improving A* tree search. First, we show that the consensus maximization tree structure used previously actually contains paths that connect nodes at both adjacent and non-adjacent levels. Crucially, paths connecting non-adjacent levels are redundant for tree search, but they were not avoided previously. We propose a new acceleration strategy that avoids such redundant paths. In the second contribution, we show that the existing branch pruning technique also deteriorates quickly with the problem dimension. We then propose a new branch pruning technique that is less dimension-sensitive to address this issue. Experiments show that both new techniques can significantly accelerate A* tree search, making it reasonably efficient on inputs that were previously out of reach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.02021](http://arxiv.org/abs/1908.02021)

##### PDF
[http://arxiv.org/pdf/1908.02021](http://arxiv.org/pdf/1908.02021)

