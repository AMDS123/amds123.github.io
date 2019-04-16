---
layout: post
title: "LiveSketch: Query Perturbations for Guided Sketch-based Visual Search"
date: 2019-04-14 00:33:15
categories: arXiv_AI
tags: arXiv_AI Embedding RNN
author: John Collomosse, Tu Bui, Hailin Jin
mathjax: true
---

* content
{:toc}

##### Abstract
LiveSketch is a novel algorithm for searching large image collections using hand-sketched queries. LiveSketch tackles the inherent ambiguity of sketch search by creating visual suggestions that augment the query as it is drawn, making query specification an iterative rather than one-shot process that helps disambiguate users' search intent. Our technical contributions are: a triplet convnet architecture that incorporates an RNN based variational autoencoder to search for images using vector (stroke-based) queries; real-time clustering to identify likely search intents (and so, targets within the search embedding); and the use of backpropagation from those targets to perturb the input stroke sequence, so suggesting alterations to the query in order to guide the search. We show improvements in accuracy and time-to-task over contemporary baselines using a 67M image corpus.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.06611](http://arxiv.org/abs/1904.06611)

##### PDF
[http://arxiv.org/pdf/1904.06611](http://arxiv.org/pdf/1904.06611)

