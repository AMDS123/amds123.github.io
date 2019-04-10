---
layout: post
title: "Bilingual-GAN: A Step Towards Parallel Text Generation"
date: 2019-04-09 15:42:08
categories: arXiv_CL
tags: arXiv_CL Adversarial Attention GAN Text_Generation
author: Ahmad Rashid, Alan Do-Omri, Md. Akmal Haidar, Qun Liu, Mehdi Rezagholizadeh
mathjax: true
---

* content
{:toc}

##### Abstract
Latent space based GAN methods and attention based sequence to sequence models have achieved impressive results in text generation and unsupervised machine translation respectively. Leveraging the two domains, we propose an adversarial latent space based model capable of generating parallel sentences in two languages concurrently and translating bidirectionally. The bilingual generation goal is achieved by sampling from the latent space that is shared between both languages. First two denoising autoencoders are trained, with shared encoders and back-translation to enforce a shared latent state between the two languages. The decoder is shared for the two translation directions. Next, a GAN is trained to generate synthetic "code" mimicking the languages' shared latent space. This code is then fed into the decoder to generate text in either language. We perform our experiments on Europarl and Multi30k datasets, on the English-French language pair, and document our performance using both supervised and unsupervised machine translation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04742](http://arxiv.org/abs/1904.04742)

##### PDF
[http://arxiv.org/pdf/1904.04742](http://arxiv.org/pdf/1904.04742)

