---
layout: post
title: "Elastic CRFs for Open-ontology Slot Filling"
date: 2018-11-04 07:38:17
categories: arXiv_CL
tags: arXiv_CL Ontology Prediction Relation
author: Yinpei Dai, Yichi Zhang, Zhijian Ou, Yanmeng Wang, Junlan Feng
mathjax: true
---

* content
{:toc}

##### Abstract
Slot filling is a crucial component in task-oriented dialog systems, which is to parse (user) utterances into semantic concepts called slots. An ontology is defined by the collection of slots and the values that each slot can take. The widely-used practice of treating slot filling as a sequence labeling task suffers from two drawbacks. First, the ontology is usually pre-defined and fixed. Most current methods are unable to predict new labels for unseen slots. Second, the one-hot encoding of slot labels ignores the semantic meanings and relations for slots, which are implicit in their natural language descriptions. These observations motivate us to propose a novel model called elastic conditional random field (eCRF), for open-ontology slot filling. eCRFs can leverage the neural features of both the utterance and the slot descriptions, and are able to model the interactions between different slots. Experimental results show that eCRFs outperforms existing models on both the in-domain and the cross-doamin tasks, especially in predictions of unseen slots and values.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.01331](http://arxiv.org/abs/1811.01331)

##### PDF
[http://arxiv.org/pdf/1811.01331](http://arxiv.org/pdf/1811.01331)

