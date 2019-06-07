---
layout: post
title: "One-shot Information Extraction from Document Images using Neuro-Deductive Program Synthesis"
date: 2019-06-06 05:48:21
categories: arXiv_AI
tags: arXiv_AI Object_Detection Detection Relation
author: Vishal Sunder, Ashwin Srinivasan, Lovekesh Vig, Gautam Shroff, Rohit Rahul
mathjax: true
---

* content
{:toc}

##### Abstract
Our interest in this paper is in meeting a rapidly growing industrial demand for information extraction from images of documents such as invoices, bills, receipts etc. In practice users are able to provide a very small number of example images labeled with the information that needs to be extracted. We adopt a novel two-level neuro-deductive, approach where (a) we use pre-trained deep neural networks to populate a relational database with facts about each document-image; and (b) we use a form of deductive reasoning, related to meta-interpretive learning of transition systems to learn extraction programs: Given task-specific transitions defined using the entities and relations identified by the neural detectors and a small number of instances (usually 1, sometimes 2) of images and the desired outputs, a resource-bounded meta-interpreter constructs proofs for the instance(s) via logical deduction; a set of logic programs that extract each desired entity is easily synthesized from such proofs. In most cases a single training example together with a noisy-clone of itself suffices to learn a program-set that generalizes well on test documents, at which time the value of each entity is determined by a majority vote across its program-set. We demonstrate our two-level neuro-deductive approach on publicly available datasets ("Patent" and "Doctor's Bills") and also describe its use in a real-life industrial problem.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.02427](http://arxiv.org/abs/1906.02427)

##### PDF
[http://arxiv.org/pdf/1906.02427](http://arxiv.org/pdf/1906.02427)

