---
layout: post
title: "ThisIsCompetition at SemEval-2019 Task 9: BERT is unstable for out-of-domain samples"
date: 2019-04-06 02:24:30
categories: arXiv_CL
tags: arXiv_CL Review Adversarial Embedding Inference RNN
author: Cheoneum Park, Juae Kim, Hyeon-gu Lee, Reinald Kim Amplayo, Harksoo Kim, Jungyun Seo, Changki Lee
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes our system, Joint Encoders for Stable Suggestion Inference (JESSI), for the SemEval 2019 Task 9: Suggestion Mining from Online Reviews and Forums. JESSI is a combination of two sentence encoders: (a) one using multiple pre-trained word embeddings learned from log-bilinear regression (GloVe) and translation (CoVe) models, and (b) one on top of word encodings from a pre-trained deep bidirectional transformer (BERT). We include a domain adversarial training module when training for out-of-domain samples. Our experiments show that while BERT performs exceptionally well for in-domain samples, several runs of the model show that it is unstable for out-of-domain samples. The problem is mitigated tremendously by (1) combining BERT with a non-BERT encoder, and (2) using an RNN-based classifier on top of BERT. Our final models obtained second place with 77.78\% F-Score on Subtask A (i.e. in-domain) and achieved an F-Score of 79.59\% on Subtask B (i.e. out-of-domain), even without using any additional external data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03339](http://arxiv.org/abs/1904.03339)

##### PDF
[http://arxiv.org/pdf/1904.03339](http://arxiv.org/pdf/1904.03339)

