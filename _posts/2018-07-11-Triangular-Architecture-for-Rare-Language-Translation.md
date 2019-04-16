---
layout: post
title: "Triangular Architecture for Rare Language Translation"
date: 2018-07-11 04:56:06
categories: arXiv_CL
tags: arXiv_CL NMT
author: Shuo Ren, Wenhu Chen, Shujie Liu, Mu Li, Ming Zhou, Shuai Ma
mathjax: true
---

* content
{:toc}

##### Abstract
Neural Machine Translation (NMT) performs poor on the low-resource language pair $(X,Z)$, especially when $Z$ is a rare language. By introducing another rich language $Y$, we propose a novel triangular training architecture (TA-NMT) to leverage bilingual data $(Y,Z)$ (may be small) and $(X,Y)$ (can be rich) to improve the translation performance of low-resource pairs. In this triangular architecture, $Z$ is taken as the intermediate latent variable, and translation models of $Z$ are jointly optimized with a unified bidirectional EM algorithm under the goal of maximizing the translation likelihood of $(X,Y)$. Empirical results demonstrate that our method significantly improves the translation quality of rare languages on MultiUN and IWSLT2012 datasets, and achieves even better performance combining back-translation methods.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1805.04813](https://arxiv.org/abs/1805.04813)

##### PDF
[https://arxiv.org/pdf/1805.04813](https://arxiv.org/pdf/1805.04813)

