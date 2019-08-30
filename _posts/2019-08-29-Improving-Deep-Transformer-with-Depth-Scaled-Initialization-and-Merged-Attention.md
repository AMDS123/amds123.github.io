---
layout: post
title: "Improving Deep Transformer with Depth-Scaled Initialization and Merged Attention"
date: 2019-08-29 17:50:55
categories: arXiv_CL
tags: arXiv_CL Attention
author: Biao Zhang, Ivan Titov, Rico Sennrich
mathjax: true
---

* content
{:toc}

##### Abstract
The general trend in NLP is towards increasing model capacity and performance via deeper neural networks. However, simply stacking more layers of the popular Transformer architecture for machine translation results in poor convergence and high computational overhead. Our empirical analysis suggests that convergence is poor due to gradient vanishing caused by the interaction between residual connections and layer normalization. We propose depth-scaled initialization (DS-Init), which decreases parameter variance at the initialization stage, and reduces output variance of residual connections so as to ease gradient back-propagation through normalization layers. To address computational cost, we propose a merged attention sublayer (MAtt) which combines a simplified averagebased self-attention sublayer and the encoderdecoder attention sublayer on the decoder side. Results on WMT and IWSLT translation tasks with five translation directions show that deep Transformers with DS-Init and MAtt can substantially outperform their base counterpart in terms of BLEU (+1.1 BLEU on average for 12-layer models), while matching the decoding speed of the baseline model thanks to the efficiency improvements of MAtt.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.11365](http://arxiv.org/abs/1908.11365)

##### PDF
[http://arxiv.org/pdf/1908.11365](http://arxiv.org/pdf/1908.11365)

