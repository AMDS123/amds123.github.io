---
layout: post
title: "Visual Question Reasoning on General Dependency Tree"
date: 2018-03-31 01:48:27
categories: arXiv_CV
tags: arXiv_CV Salient Adversarial Knowledge QA Attention Relation VQA
author: Qingxing Cao, Xiaodan Liang, Bailing Li, Guanbin Li, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
The collaborative reasoning for understanding each image-question pair is very critical but under-explored for an interpretable Visual Question Answering (VQA) system. Although very recent works also tried the explicit compositional processes to assemble multiple sub-tasks embedded in the questions, their models heavily rely on the annotations or hand-crafted rules to obtain valid reasoning layout, leading to either heavy labor or poor performance on composition reasoning. In this paper, to enable global context reasoning for better aligning image and language domains in diverse and unrestricted cases, we propose a novel reasoning network called Adversarial Composition Modular Network (ACMN). This network comprises of two collaborative modules: i) an adversarial attention module to exploit the local visual evidence for each word parsed from the question; ii) a residual composition module to compose the previously mined evidence. Given a dependency parse tree for each question, the adversarial attention module progressively discovers salient regions of one word by densely combining regions of child word nodes in an adversarial manner. Then residual composition module merges the hidden representations of an arbitrary number of children through sum pooling and residual connection. Our ACMN is thus capable of building an interpretable VQA system that gradually dives the image cues following a question-driven reasoning route and makes global reasoning by incorporating the learned knowledge of all attention modules in a principled manner. Experiments on relational datasets demonstrate the superiority of our ACMN and visualization results show the explainable capability of our reasoning system.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1804.00105](https://arxiv.org/abs/1804.00105)

##### PDF
[https://arxiv.org/pdf/1804.00105](https://arxiv.org/pdf/1804.00105)

