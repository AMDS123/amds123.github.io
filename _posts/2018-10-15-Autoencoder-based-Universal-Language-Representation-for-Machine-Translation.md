---
layout: post
title: "Autoencoder-based Universal Language Representation for Machine Translation"
date: 2018-10-15 13:52:35
categories: arXiv_CL
tags: arXiv_CL
author: Carlos Escolano, Marta R. Costa-jussà, José A. R. Fonollosa
mathjax: true
---

* content
{:toc}

##### Abstract
Universal language representation is the holy grail in machine translation (MT). Thanks to the new neural MT approach, it seems that there are good perspectives towards this goal. In this paper, we propose a new architecture based on combining variational autoencoders with encoder-decoders and introducing an interlingual loss as an additional training objective. By adding and forcing this interlingual loss, we are able to train multiple encoders and decoders for each language, sharing a common universal representation. Since the final objective of this universal representation is producing close results for similar input sentences (in any language), we propose to evaluate it by encoding the same sentence in two different languages, decoding both latent representations into the same language and comparing both outputs. Preliminary results on the WMT 2017 Turkish/English task shows that the proposed architecture is capable of learning a universal language representation and simultaneously training both translation directions with state-of-the-art results.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.06351](https://arxiv.org/abs/1810.06351)

##### PDF
[https://arxiv.org/pdf/1810.06351](https://arxiv.org/pdf/1810.06351)

