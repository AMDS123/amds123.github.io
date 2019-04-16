---
layout: post
title: "Syntax-Directed Attention for Neural Machine Translation"
date: 2018-10-15 03:04:12
categories: arXiv_CL
tags: arXiv_CL Attention NMT Prediction
author: Kehai Chen, Rui Wang, Masao Utiyama, Eiichiro Sumita, Tiejun Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Attention mechanism, including global attention and local attention, plays a key role in neural machine translation (NMT). Global attention attends to all source words for word prediction. In comparison, local attention selectively looks at fixed-window source words. However, alignment weights for the current target word often decrease to the left and right by linear distance centering on the aligned source position and neglect syntax-directed distance constraints. In this paper, we extend local attention with syntax-distance constraint, to focus on syntactically related source words with the predicted target word, thus learning a more effective context vector for word prediction. Moreover, we further propose a double context NMT architecture, which consists of a global context vector and a syntax-directed context vector over the global attention, to provide more translation performance for NMT from source representation. The experiments on the large-scale Chinese-to-English and English-to-Germen translation tasks show that the proposed approach achieves a substantial and significant improvement over the baseline system.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1711.04231](https://arxiv.org/abs/1711.04231)

##### PDF
[https://arxiv.org/e-print/1711.04231](https://arxiv.org/e-print/1711.04231)

