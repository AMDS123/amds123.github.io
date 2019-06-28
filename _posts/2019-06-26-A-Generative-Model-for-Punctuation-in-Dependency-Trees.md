---
layout: post
title: "A Generative Model for Punctuation in Dependency Trees"
date: 2019-06-26 19:03:17
categories: arXiv_CL
tags: arXiv_CL Face
author: Xiang Lisa Li, Dingquan Wang, Jason Eisner
mathjax: true
---

* content
{:toc}

##### Abstract
Treebanks traditionally treat punctuation marks as ordinary words, but linguists have suggested that a tree's "true" punctuation marks are not observed (Nunberg, 1990). These latent "underlying" marks serve to delimit or separate constituents in the syntax tree. When the tree's yield is rendered as a written sentence, a string rewriting mechanism transduces the underlying marks into "surface" marks, which are part of the observed (surface) string but should not be regarded as part of the tree. We formalize this idea in a generative model of punctuation that admits efficient dynamic programming. We train it without observing the underlying marks, by locally maximizing the incomplete data likelihood (similarly to EM). When we use the trained model to reconstruct the tree's underlying punctuation, the results appear plausible across 5 languages, and in particular, are consistent with Nunberg's analysis of English. We show that our generative model can be used to beat baselines on punctuation restoration. Also, our reconstruction of a sentence's underlying punctuation lets us appropriately render the surface punctuation (via our trained underlying-to-surface mechanism) when we syntactically transform the sentence.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.11298](http://arxiv.org/abs/1906.11298)

##### PDF
[http://arxiv.org/pdf/1906.11298](http://arxiv.org/pdf/1906.11298)

