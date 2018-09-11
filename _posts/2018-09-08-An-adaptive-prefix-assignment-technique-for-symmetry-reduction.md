---
layout: post
title: "An adaptive prefix-assignment technique for symmetry reduction"
date: 2018-09-08 10:58:31
categories: arXiv_AI
tags: arXiv_AI Face
author: Tommi Junttila (1), Matti Karppa (1), Petteri Kaski (1), Jukka Kohonen (1) ((1) Aalto University, Department of Computer Science)
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a technique for symmetry reduction that adaptively assigns a prefix of variables in a system of constraints so that the generated prefix-assignments are pairwise nonisomorphic under the action of the symmetry group of the system. The technique is based on McKay's canonical extension framework [J.~Algorithms 26 (1998), no.~2, 306--324]. Among key features of the technique are (i) adaptability---the prefix sequence can be user-prescribed and truncated for compatibility with the group of symmetries; (ii) parallelizability---prefix-assignments can be processed in parallel independently of each other; (iii) versatility---the method is applicable whenever the group of symmetries can be concisely represented as the automorphism group of a vertex-colored graph; and (iv) implementability---the method can be implemented relying on a canonical labeling map for vertex-colored graphs as the only nontrivial subroutine. To demonstrate the practical applicability of our technique, we have prepared an experimental open-source implementation of the technique and carry out a set of experiments that demonstrate ability to reduce symmetry on hard instances. Furthermore, we demonstrate that the implementation effectively parallelizes to compute clusters with multiple nodes via a message-passing interface.

##### Abstract (translated by Google)
本文提出了一种对称约简技术，该技术在约束系统中自适应地赋予变量前缀，使得生成的前缀分配在系统对称组的作用下成对非同构。该技术基于McKay的规范扩展框架[J.~Algorithms 26（1998），no.2~306--324]。该技术的主要特征之一是（i）适应性 - 前缀序列可以由用户规定并截断以与对称组兼容; （ii）可并行性---前缀分配可以彼此独立地并行处理; （iii）通用性 - 只要对称组可以简洁地表示为顶点色图的自同构群，该方法就适用; （iv）可实现性---该方法可以依赖于顶点颜色图的规范标记映射作为唯一的非平凡子例程来实现。为了证明我们的技术的实际适用性，我们准备了该技术的实验性开源实现，并进行了一组实验，证明了降低硬实例对称性的能力。此外，我们证明了实现通过消息传递接口有效地并行化到具有多个节点的计算集群。

##### URL
[http://arxiv.org/abs/1706.08325](http://arxiv.org/abs/1706.08325)

##### PDF
[http://arxiv.org/pdf/1706.08325](http://arxiv.org/pdf/1706.08325)

