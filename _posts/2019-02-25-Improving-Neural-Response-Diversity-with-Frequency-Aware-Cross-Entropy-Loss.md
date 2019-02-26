---
layout: post
title: "Improving Neural Response Diversity with Frequency-Aware Cross-Entropy Loss"
date: 2019-02-25 10:53:29
categories: arXiv_CL
tags: arXiv_CL Face
author: Shaojie Jiang, Pengjie Ren, Christof Monz, Maarten de Rijke
mathjax: true
---

* content
{:toc}

##### Abstract
Sequence-to-Sequence (Seq2Seq) models have achieved encouraging performance on the dialogue response generation task. However, existing Seq2Seq-based response generation methods suffer from a low-diversity problem: they frequently generate generic responses, which make the conversation less interesting. In this paper, we address the low-diversity problem by investigating its connection with model over-confidence reflected in predicted distributions. Specifically, we first analyze the influence of the commonly used Cross-Entropy (CE) loss function, and find that the CE loss function prefers high-frequency tokens, which results in low-diversity responses. We then propose a Frequency-Aware Cross-Entropy (FACE) loss function that improves over the CE loss function by incorporating a weighting mechanism conditioned on token frequency. Extensive experiments on benchmark datasets show that the FACE loss function is able to substantially improve the diversity of existing state-of-the-art Seq2Seq response generation methods, in terms of both automatic and human evaluations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.09191](http://arxiv.org/abs/1902.09191)

##### PDF
[http://arxiv.org/pdf/1902.09191](http://arxiv.org/pdf/1902.09191)

