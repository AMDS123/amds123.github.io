---
layout: post
title: "Compositional Representation of Morphologically-Rich Input for Neural Machine Translation"
date: 2018-05-05 10:27:32
categories: arXiv_CL
tags: arXiv_CL Segmentation Embedding NMT
author: Duygu Ataman, Marcello Federico
mathjax: true
---

* content
{:toc}

##### Abstract
Neural machine translation (NMT) models are typically trained with fixed-size input and output vocabularies, which creates an important bottleneck on their accuracy and generalization capability. As a solution, various studies proposed segmenting words into sub-word units and performing translation at the sub-lexical level. However, statistical word segmentation methods have recently shown to be prone to morphological errors, which can lead to inaccurate translations. In this paper, we propose to overcome this problem by replacing the source-language embedding layer of NMT with a bi-directional recurrent neural network that generates compositional representations of the input at any desired level of granularity. We test our approach in a low-resource setting with five languages from different morphological typologies, and under different composition assumptions. By training NMT to compose word representations from character n-grams, our approach consistently outperforms (from 1.71 to 2.48 BLEU points) NMT learning embeddings of statistically generated sub-word units.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1805.02036](https://arxiv.org/abs/1805.02036)

##### PDF
[https://arxiv.org/pdf/1805.02036](https://arxiv.org/pdf/1805.02036)

