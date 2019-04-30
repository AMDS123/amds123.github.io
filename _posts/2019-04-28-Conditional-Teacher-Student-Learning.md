---
layout: post
title: "Conditional Teacher-Student Learning"
date: 2019-04-28 23:43:20
categories: arXiv_CV
tags: arXiv_CV Knowledge Prediction
author: Zhong Meng, Jinyu Li, Yong Zhao, Yifan Gong
mathjax: true
---

* content
{:toc}

##### Abstract
The teacher-student (T/S) learning has been shown to be effective for a variety of problems such as domain adaptation and model compression. One shortcoming of the T/S learning is that a teacher model, not always perfect, sporadically produces wrong guidance in form of posterior probabilities that misleads the student model towards a suboptimal performance. To overcome this problem, we propose a conditional T/S learning scheme, in which a "smart" student model selectively chooses to learn from either the teacher model or the ground truth labels conditioned on whether the teacher can correctly predict the ground truth. Unlike a naive linear combination of the two knowledge sources, the conditional learning is exclusively engaged with the teacher model when the teacher model's prediction is correct, and otherwise backs off to the ground truth. Thus, the student model is able to learn effectively from the teacher and even potentially surpass the teacher. We examine the proposed learning scheme on two tasks: domain adaptation on CHiME-3 dataset and speaker adaptation on Microsoft short message dictation dataset. The proposed method achieves 9.8% and 12.8% relative word error rate reductions, respectively, over T/S learning for environment adaptation and speaker-independent model for speaker adaptation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12399](http://arxiv.org/abs/1904.12399)

##### PDF
[http://arxiv.org/pdf/1904.12399](http://arxiv.org/pdf/1904.12399)

