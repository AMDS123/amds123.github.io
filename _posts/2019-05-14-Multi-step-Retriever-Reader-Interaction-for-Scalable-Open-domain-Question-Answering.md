---
layout: post
title: "Multi-step Retriever-Reader Interaction for Scalable Open-domain Question Answering"
date: 2019-05-14 17:27:08
categories: arXiv_CL
tags: arXiv_CL QA
author: Rajarshi Das, Shehzaad Dhuliawala, Manzil Zaheer, Andrew McCallum
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces a new framework for open-domain question answering in which the retriever and the reader iteratively interact with each other. The framework is agnostic to the architecture of the machine reading model, only requiring access to the token-level hidden representations of the reader. The retriever uses fast nearest neighbor search to scale to corpora containing millions of paragraphs. A gated recurrent unit updates the query at each step conditioned on the state of the reader and the reformulated query is used to re-rank the paragraphs by the retriever. We conduct analysis and show that iterative interaction helps in retrieving informative paragraphs from the corpus. Finally, we show that our multi-step-reasoning framework brings consistent improvement when applied to two widely used reader architectures DrQA and BiDAF on various large open-domain datasets --- TriviaQA-unfiltered, QuasarT, SearchQA, and SQuAD-Open.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.05733](https://arxiv.org/abs/1905.05733)

##### PDF
[https://arxiv.org/pdf/1905.05733](https://arxiv.org/pdf/1905.05733)

