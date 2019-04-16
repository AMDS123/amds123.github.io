---
layout: post
title: "Translation of Patent Sentences with a Large Vocabulary of Technical Terms Using Neural Machine Translation"
date: 2017-04-14 19:36:54
categories: arXiv_CL
tags: arXiv_CL NMT
author: Zi Long, Takehito Utsuro, Tomoharu Mitsuhashi, Mikio Yamamoto
mathjax: true
---

* content
{:toc}

##### Abstract
Neural machine translation (NMT), a new approach to machine translation, has achieved promising results comparable to those of traditional approaches such as statistical machine translation (SMT). Despite its recent success, NMT cannot handle a larger vocabulary because training complexity and decoding complexity proportionally increase with the number of target words. This problem becomes even more serious when translating patent documents, which contain many technical terms that are observed infrequently. In NMTs, words that are out of vocabulary are represented by a single unknown token. In this paper, we propose a method that enables NMT to translate patent sentences comprising a large vocabulary of technical terms. We train an NMT system on bilingual data wherein technical terms are replaced with technical term tokens; this allows it to translate most of the source sentences except technical terms. Further, we use it as a decoder to translate source sentences with technical term tokens and replace the tokens with technical term translations using SMT. We also use it to rerank the 1,000-best SMT translations on the basis of the average of the SMT score and that of the NMT rescoring of the translated sentences with technical term tokens. Our experiments on Japanese-Chinese patent sentences show that the proposed NMT system achieves a substantial improvement of up to 3.1 BLEU points and 2.3 RIBES points over traditional SMT systems and an improvement of approximately 0.6 BLEU points and 0.8 RIBES points over an equivalent NMT system without our proposed technique.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1704.04521](https://arxiv.org/abs/1704.04521)

##### PDF
[https://arxiv.org/pdf/1704.04521](https://arxiv.org/pdf/1704.04521)

