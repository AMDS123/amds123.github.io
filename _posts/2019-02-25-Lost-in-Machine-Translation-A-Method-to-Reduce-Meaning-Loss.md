---
layout: post
title: "Lost in Machine Translation: A Method to Reduce Meaning Loss"
date: 2019-02-25 18:54:10
categories: arXiv_CL
tags: arXiv_CL
author: Reuben Cohn-Gordon, Noah Goodman
mathjax: true
---

* content
{:toc}

##### Abstract
A desideratum of high-quality translation systems is that they preserve meaning, in the sense that two sentences with different meanings should not translate to one and the same sentence in another language. However, state-of-the-art systems often fail in this regard, particularly in cases where the source and target languages partition the "meaning space" in different ways. For instance, "I cut my finger." and "I cut my finger off." describe different states of the world but are translated to French (by both Fairseq and Google Translate) as "Je me suis coupe le doigt.", which is ambiguous as to whether the finger is detached. More generally, translation systems are typically many-to-one (non-injective) functions from source to target language, which in many cases results in important distinctions in meaning being lost in translation. Building on Bayesian models of informative utterance production, we present a method to define a less ambiguous translation system in terms of an underlying pre-trained neural sequence-to-sequence model. This method increases injectivity, resulting in greater preservation of meaning as measured by improvement in cycle-consistency, without impeding translation quality (measured by BLEU score).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.09514](http://arxiv.org/abs/1902.09514)

##### PDF
[http://arxiv.org/pdf/1902.09514](http://arxiv.org/pdf/1902.09514)

