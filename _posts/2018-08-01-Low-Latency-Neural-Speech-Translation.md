---
layout: post
title: "Low-Latency Neural Speech Translation"
date: 2018-08-01 18:17:05
categories: arXiv_CL
tags: arXiv_CL NMT Deep_Learning
author: Jan Niehues, Ngoc-Quan Pham, Thanh-Le Ha, Matthias Sperber, Alex Waibel
mathjax: true
---

* content
{:toc}

##### Abstract
Through the development of neural machine translation, the quality of machine translation systems has been improved significantly. By exploiting advancements in deep learning, systems are now able to better approximate the complex mapping from source sentences to target sentences. But with this ability, new challenges also arise. An example is the translation of partial sentences in low-latency speech translation. Since the model has only seen complete sentences in training, it will always try to generate a complete sentence, though the input may only be a partial sentence. We show that NMT systems can be adapted to scenarios where no task-specific training data is available. Furthermore, this is possible without losing performance on the original training data. We achieve this by creating artificial data and by using multi-task learning. After adaptation, we are able to reduce the number of corrections displayed during incremental output construction by 45%, without a decrease in translation quality.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1808.00491](https://arxiv.org/abs/1808.00491)

##### PDF
[https://arxiv.org/pdf/1808.00491](https://arxiv.org/pdf/1808.00491)

