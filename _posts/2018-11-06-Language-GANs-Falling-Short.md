---
layout: post
title: "Language GANs Falling Short"
date: 2018-11-06 18:44:11
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN Inference Prediction
author: Massimo Caccia, Lucas Caccia, William Fedus, Hugo Larochelle, Joelle Pineau, Laurent Charlin
mathjax: true
---

* content
{:toc}

##### Abstract
Generating high-quality text with sufficient diversity is essential for a wide range of Natural Language Generation (NLG) tasks. Maximum-Likelihood (MLE) models trained with teacher forcing have constantly been reported as weak baselines, where poor performance is attributed to exposure bias; at inference time, the model is fed its own prediction instead of a ground-truth token, which can lead to accumulating errors and poor samples. This line of reasoning has led to an outbreak of adversarial based approaches for NLG, on the account that GANs do not suffer from exposure bias. In this work, wake make several surprising observations with contradict common beliefs. We first revisit the canonical evaluation framework for NLG, and point out fundamental flaws with quality-only evaluation: we show that one can outperform such metrics using a simple, well-known temperature parameter to artificially reduce the entropy of the model's conditional distributions. Second, we leverage the control over the quality / diversity tradeoff given by this parameter to evaluate models over the whole quality-diversity spectrum, and find MLE models constantly outperform the proposed GAN variants, over the whole quality-diversity space. Our results have several implications: 1) The impact of exposure bias on sample quality is less severe than previously thought, 2) temperature tuning provides a better quality / diversity trade off than adversarial training, while being easier to train, easier to cross-validate, and less computationally expensive.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.02549](https://arxiv.org/abs/1811.02549)

##### PDF
[https://arxiv.org/pdf/1811.02549](https://arxiv.org/pdf/1811.02549)

