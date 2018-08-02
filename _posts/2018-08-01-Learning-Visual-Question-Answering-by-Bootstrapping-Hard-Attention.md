---
layout: post
title: "Learning Visual Question Answering by Bootstrapping Hard Attention"
date: 2018-08-01 12:39:43
categories: arXiv_AI
tags: arXiv_AI Attention VQA
author: Mateusz Malinowski, Carl Doersch, Adam Santoro, Peter Battaglia
mathjax: true
---

* content
{:toc}

##### Abstract
Attention mechanisms in biological perception are thought to select subsets of perceptual information for more sophisticated processing which would be prohibitive to perform on all sensory inputs. In computer vision, however, there has been relatively little exploration of hard attention, where some information is selectively ignored, in spite of the success of soft attention, where information is re-weighted and aggregated, but never filtered out. Here, we introduce a new approach for hard attention and find it achieves very competitive performance on a recently-released visual question answering datasets, equalling and in some cases surpassing similar soft attention architectures while entirely ignoring some features. Even though the hard attention mechanism is thought to be non-differentiable, we found that the feature magnitudes correlate with semantic relevance, and provide a useful signal for our mechanism's attentional selection criterion. Because hard attention selects important features of the input information, it can also be more efficient than analogous soft attention mechanisms. This is especially important for recent approaches that use non-local pairwise operations, whereby computational and memory costs are quadratic in the size of the set of features.

##### Abstract (translated by Google)
生物感知中的注意机制被认为选择感知信息的子集用于更复杂的处理，这对于在所有感觉输入上执行是禁止的。然而，在计算机视觉中，尽管软注意力成功，信息被重新加权和聚合，但从未被过滤掉，所以对硬注意力的探索相对较少，其中一些信息被选择性地忽略。在这里，我们介绍了一种新的方法，以便在最近发布的视觉问题回答数据集上获得非常有竞争力的性能，在某些情况下超过类似的软关注架构，同时完全忽略某些功能。尽管硬注意力机制被认为是不可微分的，但我们发现特征量值与语义相关性相关，并为我们机制的注意力选择标准提供了有用的信号。因为强烈关注选择输入信息的重要特征，所以它也可以比类似的软注意机制更有效。这对于使用非局部成对运算的近期方法尤其重要，其中计算和存储器成本在特征集的大小上是二次的。

##### URL
[https://arxiv.org/abs/1808.00300](https://arxiv.org/abs/1808.00300)

##### PDF
[https://arxiv.org/pdf/1808.00300](https://arxiv.org/pdf/1808.00300)

