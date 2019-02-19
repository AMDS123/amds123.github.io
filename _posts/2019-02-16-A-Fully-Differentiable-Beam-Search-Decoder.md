---
layout: post
title: "A Fully Differentiable Beam Search Decoder"
date: 2019-02-16 01:28:12
categories: arXiv_CL
tags: arXiv_CL Attention Speech_Recognition Inference Language_Model Recognition
author: Ronan Collobert, Awni Hannun, Gabriel Synnaeve
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a new beam search decoder that is fully differentiable, making it possible to optimize at training time through the inference procedure. Our decoder allows us to combine models which operate at different granularities (e.g. acoustic and language models). It can be used when target sequences are not aligned to input sequences by considering all possible alignments between the two. We demonstrate our approach scales by applying it to speech recognition, jointly training acoustic and word-level language models. The system is end-to-end, with gradients flowing through the whole architecture from the word-level transcriptions. Recent research efforts have shown that deep neural networks with attention-based mechanisms are powerful enough to successfully train an acoustic model from the final transcription, while implicitly learning a language model. Instead, we show that it is possible to discriminatively train an acoustic model jointly with an explicit and possibly pre-trained language model.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.06022](http://arxiv.org/abs/1902.06022)

##### PDF
[http://arxiv.org/pdf/1902.06022](http://arxiv.org/pdf/1902.06022)

