---
layout: post
title: "Triangular Architecture for Rare Language Translation"
date: 2018-05-13 03:35:09
categories: arXiv_AI
tags: arXiv_AI NMT
author: Shuo Ren, Wenhu Chen, Shujie Liu, Mu Li, Ming Zhou, Shuai Ma
mathjax: true
---

* content
{:toc}

##### Abstract
Neural Machine Translation (NMT) performs poor on the low-resource language pair $(X,Z)$, especially when $Z$ is a rare language. By introducing another rich language $Y$, we propose a novel triangular training architecture (TA-NMT) to leverage bilingual data $(Y,Z)$ (may be small) and $(X,Y)$ (can be rich) to improve the translation performance of low-resource pairs. In this triangular architecture, $Z$ is taken as the intermediate latent variable, and translation models of $Z$ are jointly optimized with a unified bidirectional EM algorithm under the goal of maximizing the translation likelihood of $(X,Y)$. Empirical results demonstrate that our method significantly improves the translation quality of rare languages on MultiUN and IWSLT2012 datasets, and achieves even better performance combining back-translation methods.

##### Abstract (translated by Google)
神经机器翻译（NMT）在低资源语言对$（X，Z）$上表现不佳，特别是当$ Z $是罕见的语言时。通过引入另一种丰富的语言$ Y $，我们提出了一种新颖的三角形训练架构（TA-NMT），以利用双语数据$（Y，Z）$（可能很小）和$（X，Y）$（可能很丰富）以提高低资源对的翻译表现。在这种三角形结构中，$ Z $被视为中间潜变量，$ Z $的翻译模型在一个统一的双向EM算法下联合优化，目的是使$（X，Y）$的翻译可能性最大化。实证结果表明，我们的方法显着提高了MultiUN和IWSLT2012数据集上罕见语言的翻译质量，并且实现了更好的结合后翻译方法的性能。

##### URL
[https://arxiv.org/abs/1805.04813](https://arxiv.org/abs/1805.04813)

##### PDF
[https://arxiv.org/pdf/1805.04813](https://arxiv.org/pdf/1805.04813)

