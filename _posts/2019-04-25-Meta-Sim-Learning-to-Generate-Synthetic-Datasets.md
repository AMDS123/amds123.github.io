---
layout: post
title: "Meta-Sim: Learning to Generate Synthetic Datasets"
date: 2019-04-25 23:18:36
categories: arXiv_AI
tags: arXiv_AI Quantitative
author: Amlan Kar, Aayush Prakash, Ming-Yu Liu, Eric Cameracci, Justin Yuan, Matt Rusiniak, David Acuna, Antonio Torralba, Sanja Fidler
mathjax: true
---

* content
{:toc}

##### Abstract
Training models to high-end performance requires availability of large labeled datasets, which are expensive to get. The goal of our work is to automatically synthesize labeled datasets that are relevant for a downstream task. We propose Meta-Sim, which learns a generative model of synthetic scenes, and obtain images as well as its corresponding ground-truth via a graphics engine. We parametrize our dataset generator with a neural network, which learns to modify attributes of scene graphs obtained from probabilistic scene grammars, so as to minimize the distribution gap between its rendered outputs and target data. If the real dataset comes with a small labeled validation set, we additionally aim to optimize a meta-objective, i.e. downstream task performance. Experiments show that the proposed method can greatly improve content generation quality over a human-engineered probabilistic scene grammar, both qualitatively and quantitatively as measured by performance on a downstream task.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.11621](http://arxiv.org/abs/1904.11621)

##### PDF
[http://arxiv.org/pdf/1904.11621](http://arxiv.org/pdf/1904.11621)

