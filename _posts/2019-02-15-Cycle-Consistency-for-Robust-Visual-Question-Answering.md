---
layout: post
title: "Cycle-Consistency for Robust Visual Question Answering"
date: 2019-02-15 02:07:18
categories: arXiv_CV
tags: arXiv_CV QA VQA
author: Meet Shah, Xinlei Chen, Marcus Rohrbach, Devi Parikh
mathjax: true
---

* content
{:toc}

##### Abstract
Despite significant progress in Visual Question Answering over the years, robustness of today's VQA models leave much to be desired. We introduce a new evaluation protocol and associated dataset (VQA-Rephrasings) and show that state-of-the-art VQA models are notoriously brittle to linguistic variations in questions. VQA-Rephrasings contains 3 human-provided rephrasings for 40k questions spanning 40k images from the VQA v2.0 validation dataset. As a step towards improving robustness of VQA models, we propose a model-agnostic framework that exploits cycle consistency. Specifically, we train a model to not only answer a question, but also generate a question conditioned on the answer, such that the answer predicted for the generated question is the same as the ground truth answer to the original question. Without the use of additional annotations, we show that our approach is significantly more robust to linguistic variations than state-of-the-art VQA models, when evaluated on the VQA-Rephrasings dataset. In addition, our approach outperforms state-of-the-art approaches on the standard VQA and Visual Question Generation tasks on the challenging VQA v2.0 dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.05660](http://arxiv.org/abs/1902.05660)

##### PDF
[http://arxiv.org/pdf/1902.05660](http://arxiv.org/pdf/1902.05660)

