---
layout: post
title: "Distant Learning for Entity Linking with Automatic Noise Detection"
date: 2019-05-17 10:49:47
categories: arXiv_AI
tags: arXiv_AI Knowledge Face Detection
author: Phong Le, Ivan Titov
mathjax: true
---

* content
{:toc}

##### Abstract
Accurate entity linkers have been produced for domains and languages where annotated data (i.e., texts linked to a knowledge base) is available. However, little progress has been made for the settings where no or very limited amounts of labeled data are present (e.g., legal or most scientific domains). In this work, we show how we can learn to link mentions without having any labeled examples, only a knowledge base and a collection of unannotated texts from the corresponding domain. In order to achieve this, we frame the task as a multi-instance learning problem and rely on surface matching to create initial noisy labels. As the learning signal is weak and our surrogate labels are noisy, we introduce a noise detection component in our model: it lets the model detect and disregard examples which are likely to be noisy. Our method, jointly learning to detect noise and link entities, greatly outperforms the surface matching baseline and for a subset of entity categories even approaches the performance of supervised learning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.07189](http://arxiv.org/abs/1905.07189)

##### PDF
[http://arxiv.org/pdf/1905.07189](http://arxiv.org/pdf/1905.07189)

