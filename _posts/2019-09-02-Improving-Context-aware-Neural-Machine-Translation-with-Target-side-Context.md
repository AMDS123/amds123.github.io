---
layout: post
title: "Improving Context-aware Neural Machine Translation with Target-side Context"
date: 2019-09-02 04:04:18
categories: arXiv_CL
tags: arXiv_CL Attention NMT
author: Hayahide Yamagishi, Mamoru Komachi
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, several studies on neural machine translation (NMT) have attempted to use document-level context by using a multi-encoder and two attention mechanisms to read the current and previous sentences to incorporate the context of the previous sentences. These studies concluded that the target-side context is less useful than the source-side context. However, we considered that the reason why the target-side context is less useful lies in the architecture used to model these contexts. 
 Therefore, in this study, we investigate how the target-side context can improve context-aware neural machine translation. We propose a weight sharing method wherein NMT saves decoder states and calculates an attention vector using the saved states when translating a current sentence. Our experiments show that the target-side context is also useful if we plug it into NMT as the decoder state when translating a previous sentence.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00531](http://arxiv.org/abs/1909.00531)

##### PDF
[http://arxiv.org/pdf/1909.00531](http://arxiv.org/pdf/1909.00531)

