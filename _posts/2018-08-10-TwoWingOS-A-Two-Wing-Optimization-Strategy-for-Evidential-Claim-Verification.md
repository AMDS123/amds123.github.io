---
layout: post
title: "TwoWingOS: A Two-Wing Optimization Strategy for Evidential Claim Verification"
date: 2018-08-10 09:27:44
categories: arXiv_CL
tags: arXiv_CL Optimization
author: Wenpeng Yin, Dan Roth
mathjax: true
---

* content
{:toc}

##### Abstract
Determining whether a given claim is supported by evidence is a fundamental NLP problem that is best modeled as Textual Entailment. However, given a large collection of text, finding evidence that could support or refute a given claim is a challenge in itself, amplified by the fact that different evidence might be needed to support or refute a claim. Nevertheless, most prior work decouples evidence identification from determining the truth value of the claim given the evidence. 
 We propose to consider these two aspects jointly. We develop TwoWingOS (two-wing optimization strategy), a system that, while identifying appropriate evidence for a claim, also determines whether or not the claim is supported by the evidence. Given the claim, TwoWingOS attempts to identify a subset of the evidence candidates; given the predicted evidence, it then attempts to determine the truth value of the corresponding claim. We treat this challenge as coupled optimization problems, training a joint model for it. TwoWingOS offers two advantages: (i) Unlike pipeline systems, it facilitates flexible-size evidence set, and (ii) Joint training improves both the claim entailment and the evidence identification. Experiments on a benchmark dataset show state-of-the-art performance. Code: https://github.com/yinwenpeng/FEVER

##### Abstract (translated by Google)
确定某个声明是否得到证据支持是一个基本的NLP问题，最好建模为文本蕴涵。然而，鉴于大量文本，找到可以支持或驳斥某项主张的证据本身就是一项挑战，因为可能需要不同的证据来支持或驳斥索赔。尽管如此，大多数先前的工作将证据识别与证据确定证据的真值确定在一起。
 我们建议联合考虑这两个方面。我们开发了TwoWingOS（双翼优化策略），该系统在确定索赔的适当证据的同时，还确定证据是否支持索赔。鉴于索赔，TwoWingOS试图确定候选证据的一个子集;鉴于预测的证据，它然后试图确定相应的索赔的真值。我们将此挑战视为耦合优化问题，为其培训联合模型。 TwoWingOS提供两个优点：（i）与管道系统不同，它有助于灵活大小的证据集，以及（ii）联合培训改进了索赔要求和证据识别。基准数据集上的实验显示了最先进的性能。代码：https：//github.com/yinwenpeng/FEVER

##### URL
[http://arxiv.org/abs/1808.03465](http://arxiv.org/abs/1808.03465)

##### PDF
[http://arxiv.org/pdf/1808.03465](http://arxiv.org/pdf/1808.03465)

