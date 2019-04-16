---
layout: post
title: "Visual Coreference Resolution in Visual Dialog using Neural Module Networks"
date: 2018-09-06 04:36:22
categories: arXiv_CV
tags: arXiv_CV QA VQA
author: Satwik Kottur, José M. F. Moura, Devi Parikh, Dhruv Batra, Marcus Rohrbach
mathjax: true
---

* content
{:toc}

##### Abstract
Visual dialog entails answering a series of questions grounded in an image, using dialog history as context. In addition to the challenges found in visual question answering (VQA), which can be seen as one-round dialog, visual dialog encompasses several more. We focus on one such problem called visual coreference resolution that involves determining which words, typically noun phrases and pronouns, co-refer to the same entity/object instance in an image. This is crucial, especially for pronouns (e.g., `it'), as the dialog agent must first link it to a previous coreference (e.g., `boat'), and only then can rely on the visual grounding of the coreference `boat' to reason about the pronoun `it'. Prior work (in visual dialog) models visual coreference resolution either (a) implicitly via a memory network over history, or (b) at a coarse level for the entire question; and not explicitly at a phrase level of granularity. In this work, we propose a neural module network architecture for visual dialog by introducing two novel modules - Refer and Exclude - that perform explicit, grounded, coreference resolution at a finer word level. We demonstrate the effectiveness of our model on MNIST Dialog, a visually simple yet coreference-wise complex dataset, by achieving near perfect accuracy, and on VisDial, a large and challenging visual dialog dataset on real images, where our model outperforms other approaches, and is more interpretable, grounded, and consistent qualitatively.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1809.01816](https://arxiv.org/abs/1809.01816)

##### PDF
[https://arxiv.org/pdf/1809.01816](https://arxiv.org/pdf/1809.01816)

