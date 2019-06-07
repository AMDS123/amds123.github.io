---
layout: post
title: "Unsupervised Pivot Translation for Distant Languages"
date: 2019-06-06 07:48:36
categories: arXiv_AI
tags: arXiv_AI Attention NMT
author: Yichong Leng, Xu Tan, Tao Qin, Xiang-Yang Li, Tie-Yan Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised neural machine translation (NMT) has attracted a lot of attention recently. While state-of-the-art methods for unsupervised translation usually perform well between similar languages (e.g., English-German translation), they perform poorly between distant languages, because unsupervised alignment does not work well for distant languages. In this work, we introduce unsupervised pivot translation for distant languages, which translates a language to a distant language through multiple hops, and the unsupervised translation on each hop is relatively easier than the original direct translation. We propose a learning to route (LTR) method to choose the translation path between the source and target languages. LTR is trained on language pairs whose best translation path is available and is applied on the unseen language pairs for path selection. Experiments on 20 languages and 294 distant language pairs demonstrate the advantages of the unsupervised pivot translation for distant languages, as well as the effectiveness of the proposed LTR for path selection. Specifically, in the best case, LTR achieves an improvement of 5.58 BLEU points over the conventional direct unsupervised method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.02461](http://arxiv.org/abs/1906.02461)

##### PDF
[http://arxiv.org/pdf/1906.02461](http://arxiv.org/pdf/1906.02461)

