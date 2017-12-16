---
layout: post
title: "Multi-way Particle Swarm Fusion"
date: 2016-12-05 03:05:21
categories: arXiv_CV
tags: arXiv_CV Inference
author: Chen Liu, Hang Yan, Pushmeet Kohli, Yasutaka Furukawa
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a novel MAP inference framework for Markov Random Field (MRF) in parallel computing environments. The inference framework, dubbed Swarm Fusion, is a natural generalization of the Fusion Move method. Every thread (in a case of multi-threading environments) maintains and updates a solution. At each iteration, a thread can generate arbitrary number of solution proposals and take arbitrary number of concurrent solutions from the other threads to perform multi-way fusion in updating its solution. The framework is general, making popular existing inference techniques such as alpha-expansion, fusion move, parallel alpha-expansion, and hierarchical fusion, its special cases. We have evaluated the effectiveness of our approach against competing methods on three problems of varying difficulties, in particular, the stereo, the optical flow, and the layered depthmap estimation problems.

##### Abstract (translated by Google)
本文提出了一种在并行计算环境下的马尔可夫随机场（MRF）的新型MAP推理框架。称为Swarm Fusion的推理框架是Fusion Move方法的自然推广。每个线程（在多线程环境的情况下）都维护和更新一个解决方案。在每一次迭代中，一个线程可以生成任意数量的解决方案，并且从其他线程采取任意数量的并发解决方案来执行多路融合来更新其解决方案。该框架是一般的，使得现有的推广技术，如alpha扩展，融合移动，并行alpha扩展和分层融合，它的特殊情况。我们已经评估了我们的方法对三种不同难度问题的竞争方法的有效性，特别是立体，光流和分层深度图估计问题。

##### URL
[https://arxiv.org/abs/1612.01234](https://arxiv.org/abs/1612.01234)

##### PDF
[https://arxiv.org/pdf/1612.01234](https://arxiv.org/pdf/1612.01234)

