---
layout: post
title: "Simple and Effective Noisy Channel Modeling for Neural Machine Translation"
date: 2019-08-15 19:54:23
categories: arXiv_CL
tags: arXiv_CL Language_Model
author: Kyra Yee, Nathan Ng, Yann N. Dauphin, Michael Auli
mathjax: true
---

* content
{:toc}

##### Abstract
Previous work on neural noisy channel modeling relied on latent variable models that incrementally process the source and target sentence. This makes decoding decisions based on partial source prefixes even though the full source is available. We pursue an alternative approach based on standard sequence to sequence models which utilize the entire source. These models perform remarkably well as channel models, even though they have neither been trained on, nor designed to factor over incomplete target sentences. Experiments with neural language models trained on billions of words show that noisy channel models can outperform a direct model by up to 3.2 BLEU on WMT'17 German-English translation. We evaluate on four language-pairs and our channel models consistently outperform strong alternatives such right-to-left reranking models and ensembles of direct models.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.05731](https://arxiv.org/abs/1908.05731)

##### PDF
[https://arxiv.org/pdf/1908.05731](https://arxiv.org/pdf/1908.05731)

