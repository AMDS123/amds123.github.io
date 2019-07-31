---
layout: post
title: "English-Czech Systems in WMT19: Document-Level Transformer"
date: 2019-07-30 06:17:19
categories: arXiv_CL
tags: arXiv_CL NMT
author: Martin Popel, Dominik Mach&#xe1;&#x10d;ek, Michal Auersperger, Ond&#x159;ej Bojar, Pavel Pecina
mathjax: true
---

* content
{:toc}

##### Abstract
We describe our NMT systems submitted to the WMT19 shared task in English-Czech news translation. Our systems are based on the Transformer model implemented in either Tensor2Tensor (T2T) or Marian framework. 
 We aimed at improving the adequacy and coherence of translated documents by enlarging the context of the source and target. Instead of translating each sentence independently, we split the document into possibly overlapping multi-sentence segments. In case of the T2T implementation, this "document-level"-trained system achieves a $+0.6$ BLEU improvement ($p&lt;0.05$) relative to the same system applied on isolated sentences. To assess the potential effect document-level models might have on lexical coherence, we performed a semi-automatic analysis, which revealed only a few sentences improved in this aspect. Thus, we cannot draw any conclusions from this weak evidence.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.12750](http://arxiv.org/abs/1907.12750)

##### PDF
[http://arxiv.org/pdf/1907.12750](http://arxiv.org/pdf/1907.12750)

