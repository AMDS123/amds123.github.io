---
layout: post
title: "To Reverse the Gradient or Not: An Empirical Comparison of Adversarial and Multi-task Learning in Speech Recognition"
date: 2018-12-09 13:18:02
categories: arXiv_CL
tags: arXiv_CL Adversarial Speech_Recognition Prediction Recognition
author: Yossi Adi, Neil Zeghidour, Ronan Collobert, Nicolas Usunier, Vitaliy Liptchinsky, Gabriel Synnaeve
mathjax: true
---

* content
{:toc}

##### Abstract
Transcribed datasets typically contain speaker identity for each instance in the data. We investigate two ways to incorporate this information during training: Multi-Task Learning and Adversarial Learning. In multi-task learning, the goal is speaker prediction; we expect a performance improvement with this joint training if the two tasks of speech recognition and speaker recognition share a common set of underlying features. In contrast, adversarial learning is a means to learn representations invariant to the speaker. We then expect better performance if this learnt invariance helps generalizing to new speakers. While the two approaches seem natural in the context of speech recognition, they are incompatible because they correspond to opposite gradients back-propagated to the model. In order to better understand the effect of these approaches in terms of error rates, we compare both strategies in controlled settings. Moreover, we explore the use of additional untranscribed data in a semi-supervised, adversarial learning manner to improve error rates. Our results show that deep models trained on big datasets already develop invariant representations to speakers without any auxiliary loss. When considering adversarial learning and multi-task learning, the impact on the acoustic model seems minor. However, models trained in a semi-supervised manner can improve error-rates.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.03483](http://arxiv.org/abs/1812.03483)

##### PDF
[http://arxiv.org/pdf/1812.03483](http://arxiv.org/pdf/1812.03483)

