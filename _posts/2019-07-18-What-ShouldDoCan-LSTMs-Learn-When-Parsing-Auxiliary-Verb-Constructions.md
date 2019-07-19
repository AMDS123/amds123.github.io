---
layout: post
title: "What Should/Do/Can LSTMs Learn When Parsing Auxiliary Verb Constructions?"
date: 2019-07-18 09:37:38
categories: arXiv_CL
tags: arXiv_CL RNN
author: Miryam de Lhoneux, Sara Stymne, Joakim Nivre
mathjax: true
---

* content
{:toc}

##### Abstract
This article is a linguistic investigation of a neural parser. We look at transitivity and agreement information of auxiliary verb constructions (AVCs) in comparison to finite main verbs (FMVs). This comparison is motivated by theoretical work in dependency grammar and in particular the work of Tesni\`ere (1959) where AVCs and FMVs are both instances of a nucleus, the basic unit of syntax. An AVC is a dissociated nucleus, it consists of at least two words, and a FMV is its non-dissociated counterpart, consisting of exactly one word. We suggest that the representation of AVCs and FMVs should capture similar information. We use diagnostic classifiers to probe agreement and transitivity information in vectors learned by a transition-based neural parser in four typologically different languages. We find that the parser learns different information about AVCs and FMVs if only sequential models (BiLSTMs) are used in the architecture but similar information when a recursive layer is used. We find explanations for why this is the case by looking closely at how information is learned in the network and looking at what happens with different dependency representations of AVCs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.07950](http://arxiv.org/abs/1907.07950)

##### PDF
[http://arxiv.org/pdf/1907.07950](http://arxiv.org/pdf/1907.07950)

