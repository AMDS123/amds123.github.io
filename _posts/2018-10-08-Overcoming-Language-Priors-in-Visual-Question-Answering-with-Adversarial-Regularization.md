---
layout: post
title: "Overcoming Language Priors in Visual Question Answering with Adversarial Regularization"
date: 2018-10-08 18:29:05
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial QA Relation VQA
author: Sainandan Ramakrishnan, Aishwarya Agrawal, Stefan Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Modern Visual Question Answering (VQA) models have been shown to rely heavily on superficial correlations between question and answer words learned during training such as overwhelmingly reporting the type of room as kitchen or the sport being played as tennis, irrespective of the image. Most alarmingly, this shortcoming is often not well reflected during evaluation because the same strong priors exist in test distributions; however, a VQA system that fails to ground questions in image content would likely perform poorly in real-world settings. In this work, we present a novel regularization scheme for VQA that reduces this effect. We introduce a question-only model that takes as input the question encoding from the VQA model and must leverage language biases in order to succeed. We then pose training as an adversarial game between the VQA model and this question-only adversary -- discouraging the VQA model from capturing language biases in its question encoding. Further,we leverage this question-only model to estimate the increase in model confidence after considering the image, which we maximize explicitly to encourage visual grounding. Our approach is a model agnostic training procedure and simple to implement. We show empirically that it can improve performance significantly on a bias-sensitive split of the VQA dataset for multiple base models -- achieving state-of-the-art on this task. Further, on standard VQA tasks, our approach shows significantly less drop in accuracy compared to existing bias-reducing VQA models.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.03649](https://arxiv.org/abs/1810.03649)

##### PDF
[https://arxiv.org/pdf/1810.03649](https://arxiv.org/pdf/1810.03649)

