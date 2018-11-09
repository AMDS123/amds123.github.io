---
layout: post
title: "Phonetic-attention scoring for deep speaker features in speaker verification"
date: 2018-11-08 03:54:55
categories: arXiv_CL
tags: arXiv_CL Attention
author: Lantian Li, Zhiyuan Tang, Ying Shi, Dong Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Recent studies have shown that frame-level deep speaker features can be derived from a deep neural network with the training target set to discriminate speakers by a short speech segment. By pooling the frame-level features, utterance-level representations, called d-vectors, can be derived and used in the automatic speaker verification (ASV) task. This simple average pooling, however, is inherently sensitive to the phonetic content of the utterance. An interesting idea borrowed from machine translation is the attention-based mechanism, where the contribution of an input word to the translation at a particular time is weighted by an attention score. This score reflects the relevance of the input word and the present translation. We can use the same idea to align utterances with different phonetic contents. This paper proposes a phonetic-attention scoring approach for d-vector systems. By this approach, an attention score is computed for each frame pair. This score reflects the similarity of the two frames in phonetic content, and is used to weigh the contribution of this frame pair in the utterance-based scoring. This new scoring approach emphasizes the frame pairs with similar phonetic contents, which essentially provides a soft alignment for utterances with any phonetic contents. Experimental results show that compared with the naive average pooling, this phonetic-attention scoring approach can deliver consistent performance improvement in ASV tasks of both text-dependent and text-independent.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.03255](http://arxiv.org/abs/1811.03255)

##### PDF
[http://arxiv.org/pdf/1811.03255](http://arxiv.org/pdf/1811.03255)

