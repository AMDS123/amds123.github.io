---
layout: post
title: "XLNet: Generalized Autoregressive Pretraining for Language Understanding"
date: 2019-06-19 17:35:48
categories: arXiv_CL
tags: arXiv_CL Sentiment Inference Language_Model
author: Zhilin Yang, Zihang Dai, Yiming Yang, Jaime Carbonell, Ruslan Salakhutdinov, Quoc V. Le
mathjax: true
---

* content
{:toc}

##### Abstract
With the capability of modeling bidirectional contexts, denoising autoencoding based pretraining like BERT achieves better performance than pretraining approaches based on autoregressive language modeling. However, relying on corrupting the input with masks, BERT neglects dependency between the masked positions and suffers from a pretrain-finetune discrepancy. In light of these pros and cons, we propose XLNet, a generalized autoregressive pretraining method that (1) enables learning bidirectional contexts by maximizing the expected likelihood over all permutations of the factorization order and (2) overcomes the limitations of BERT thanks to its autoregressive formulation. Furthermore, XLNet integrates ideas from Transformer-XL, the state-of-the-art autoregressive model, into pretraining. Empirically, XLNet outperforms BERT on 20 tasks, often by a large margin, and achieves state-of-the-art results on 18 tasks including question answering, natural language inference, sentiment analysis, and document ranking.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.08237](http://arxiv.org/abs/1906.08237)

##### PDF
[http://arxiv.org/pdf/1906.08237](http://arxiv.org/pdf/1906.08237)

