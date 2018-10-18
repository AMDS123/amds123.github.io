---
layout: post
title: "An Analysis of Attention Mechanisms: The Case of Word Sense Disambiguation in Neural Machine Translation"
date: 2018-10-17 14:58:54
categories: arXiv_CL
tags: arXiv_CL Attention NMT
author: Gongbo Tang, Rico Sennrich, Joakim Nivre
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work has shown that the encoder-decoder attention mechanisms in neural machine translation (NMT) are different from the word alignment in statistical machine translation. In this paper, we focus on analyzing encoder-decoder attention mechanisms, in the case of word sense disambiguation (WSD) in NMT models. We hypothesize that attention mechanisms pay more attention to context tokens when translating ambiguous words. We explore the attention distribution patterns when translating ambiguous nouns. Counter-intuitively, we find that attention mechanisms are likely to distribute more attention to the ambiguous noun itself rather than context tokens, in comparison to other nouns. We conclude that attention mechanism is not the main mechanism used by NMT models to incorporate contextual information for WSD. The experimental results suggest that NMT models learn to encode contextual information necessary for WSD in the encoder hidden states. For the attention mechanism in Transformer models, we reveal that the first few layers gradually learn to "align" source and target tokens and the last few layers learn to extract features from the related but unaligned context tokens.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.07595](http://arxiv.org/abs/1810.07595)

##### PDF
[http://arxiv.org/pdf/1810.07595](http://arxiv.org/pdf/1810.07595)

