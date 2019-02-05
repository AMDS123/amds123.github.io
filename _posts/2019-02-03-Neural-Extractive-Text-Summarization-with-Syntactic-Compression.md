---
layout: post
title: "Neural Extractive Text Summarization with Syntactic Compression"
date: 2019-02-03 08:19:42
categories: arXiv_CL
tags: arXiv_CL Summarization
author: Jiacheng Xu, Greg Durrett
mathjax: true
---

* content
{:toc}

##### Abstract
Recent neural network approaches to summarization are largely either sentence-extractive, choosing a set of sentences as the summary, or abstractive, generating the summary from a seq2seq model. In this work, we present a neural model for single-document summarization based on joint extraction and compression. Following recent successful extractive models, we frame the summarization problem as a series of local decisions. Our model chooses sentences from the document and then decides which of a set of compression options to apply to each selected sentence. We compute this set of options using discrete compression rules based on syntactic constituency parses; however, our approach is modular and can flexibly use any available source of compressions. For learning, we construct oracle extractive-compressive summaries that reflect uncertainty over our model's decision sequence, then learn both of our components jointly with this supervision. Experimental results on the CNN/Daily Mail and New York Times datasets show that our model achieves the state-of-the-art performance on content selection evaluated by ROUGE. Moreover, human and manual evaluation show that our model's output generally remains grammatical.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.00863](http://arxiv.org/abs/1902.00863)

##### PDF
[http://arxiv.org/pdf/1902.00863](http://arxiv.org/pdf/1902.00863)

