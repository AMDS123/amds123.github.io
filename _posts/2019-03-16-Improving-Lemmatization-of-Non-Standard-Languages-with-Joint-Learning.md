---
layout: post
title: "Improving Lemmatization of Non-Standard Languages with Joint Learning"
date: 2019-03-16 14:59:13
categories: arXiv_CL
tags: arXiv_CL Language_Model
author: Enrique Manjavacas, &#xc1;kos K&#xe1;d&#xe1;r, Mike Kestemont
mathjax: true
---

* content
{:toc}

##### Abstract
Lemmatization of standard languages is concerned with (i) abstracting over morphological differences and (ii) resolving token-lemma ambiguities of inflected words in order to map them to a dictionary headword. In the present paper we aim to improve lemmatization performance on a set of non-standard historical languages in which the difficulty is increased by an additional aspect (iii): spelling variation due to lacking orthographic standards. We approach lemmatization as a string-transduction task with an encoder-decoder architecture which we enrich with sentence context information using a hierarchical sentence encoder. We show significant improvements over the state-of-the-art when training the sentence encoder jointly for lemmatization and language modeling. Crucially, our architecture does not require POS or morphological annotations, which are not always available for historical corpora. Additionally, we also test the proposed model on a set of typologically diverse standard languages showing results on par or better than a model without enhanced sentence representations and previous state-of-the-art systems. Finally, to encourage future work on processing of non-standard varieties, we release the dataset of non-standard languages underlying the present study, based on openly accessible sources.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.06939](http://arxiv.org/abs/1903.06939)

##### PDF
[http://arxiv.org/pdf/1903.06939](http://arxiv.org/pdf/1903.06939)

