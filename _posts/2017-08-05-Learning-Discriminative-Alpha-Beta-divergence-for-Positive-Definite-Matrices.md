---
layout: post
title: "Learning Discriminative Alpha-Beta-divergence for Positive Definite Matrices"
date: 2017-08-05 09:38:20
categories: arXiv_CV
tags: arXiv_CV Embedding Optimization
author: Anoop Cherian, Panagiotis Stanitsas, Mehrtash Harandi, Vassilios Morellas, Nikolaos Papanikolopoulos
mathjax: true
---

* content
{:toc}

##### Abstract
Symmetric positive definite (SPD) matrices are useful for capturing second-order statistics of visual data. To compare two SPD matrices, several measures are available, such as the affine-invariant Riemannian metric, Jeffreys divergence, Jensen-Bregman logdet divergence, etc.; however, their behaviors may be application dependent, raising the need of manual selection to achieve the best possible performance. Further and as a result of their overwhelming complexity for large-scale problems, computing pairwise similarities by clever embedding of SPD matrices is often preferred to direct use of the aforementioned measures. In this paper, we propose a discriminative metric learning framework, Information Divergence and Dictionary Learning (IDDL), that not only learns application specific measures on SPD matrices automatically, but also embeds them as vectors using a learned dictionary. To learn the similarity measures (which could potentially be distinct for every dictionary atom), we use the recently introduced alpha-beta-logdet divergence, which is known to unify the measures listed above. We propose a novel IDDL objective, that learns the parameters of the divergence and the dictionary atoms jointly in a discriminative setup and is solved efficiently using Riemannian optimization. We showcase extensive experiments on eight computer vision datasets, demonstrating state-of-the-art performances.

##### Abstract (translated by Google)
对称正定（SPD）矩阵可用于捕获视觉数据的二阶统计量。为了比较两个SPD矩阵，可以采用仿射不变的黎曼度量，Jeffreys散度，Jensen-Bregman logdet散度等几种方法。然而，他们的行为可能依赖于应用程序，提高了手动选择的需求，以达到最佳性能。此外，由于其对于大规模问题的压倒性的复杂性，通过智能嵌入SPD矩阵来计算成对相似性通常是优选的，以指导使用上述措施。在本文中，我们提出了一个歧视性度量学习框架，即信息发散和字典学习（IDDL），它不仅自动学习SPD矩阵的特定应用措施，而且还使用学习的字典将它们作为向量嵌入。为了学习相似性度量（对于每个字典原子，这些相似性度量可能是不同的），我们使用最近引入的alpha-beta-logdet散度，这是众所周知的统一上面列出的度量。我们提出了一个新颖的IDDL目标，它可以在一个判别的设置中共同学习发散和字典原子的参数，并用黎曼优化有效地解决。我们展示了8个计算机视觉数据集的广泛实验，展示了最先进的表演。

##### URL
[https://arxiv.org/abs/1708.01741](https://arxiv.org/abs/1708.01741)

##### PDF
[https://arxiv.org/pdf/1708.01741](https://arxiv.org/pdf/1708.01741)

