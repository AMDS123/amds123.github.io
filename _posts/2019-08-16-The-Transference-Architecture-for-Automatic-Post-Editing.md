---
layout: post
title: "The Transference Architecture for Automatic Post-Editing"
date: 2019-08-16 20:09:11
categories: arXiv_CL
tags: arXiv_CL Attention NMT
author: Santanu Pal, Hongfei Xu, Nico Herbig, Antonio Krueger, Josef van Genabith
mathjax: true
---

* content
{:toc}

##### Abstract
In automatic post-editing (APE) it makes sense to condition post-editing (pe) decisions on both the source (src) and the machine translated text (mt) as input. This has led to multi-source encoder based APE approaches. A research challenge now is the search for architectures that best support the capture, preparation and provision of src and mt information and its integration with pe decisions. In this paper we present a new multi-source APE model, called transference. Unlike previous approaches, it (i) uses a transformer encoder block for src, (ii) followed by a decoder block, but without masking for self-attention on mt, which effectively acts as second encoder combining src -&gt; mt, and (iii) feeds this representation into a final decoder block generating pe. Our model outperforms the state-of-the-art by 1 BLEU point on the WMT 2016, 2017, and 2018 English--German APE shared tasks (PBSMT and NMT). We further investigate the importance of our newly introduced second encoder and find that a too small amount of layers does hurt the performance, while reducing the number of layers of the decoder does not matter much.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.06151](http://arxiv.org/abs/1908.06151)

##### PDF
[http://arxiv.org/pdf/1908.06151](http://arxiv.org/pdf/1908.06151)

