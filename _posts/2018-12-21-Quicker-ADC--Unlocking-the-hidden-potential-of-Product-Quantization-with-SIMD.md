---
layout: post
title: "Quicker ADC : Unlocking the hidden potential of Product Quantization with SIMD"
date: 2018-12-21 14:51:27
categories: arXiv_AI
tags: arXiv_AI Face Optimization
author: Fabien Andr&#xe9;, Anne-Marie Kermarrec, Nicolas Le Scouarnec
mathjax: true
---

* content
{:toc}

##### Abstract
Efficient Nearest Neighbor (NN) search in high-dimensional spaces is a foundation of many multimedia retrieval systems. A common approach is to rely on Product Quantization that allows storing large vector databases in memory and also allows efficient distance computations. Yet, implementations of nearest neighbor search with Product Quantization have their performance limited by the many memory accesses they perform. Following this observation, Andr\'e et al. proposed more efficient implementations of $m\times{}4$ product quantizers (PQ) leveraging specific SIMD instructions. 
 Quicker ADC contributes additional implementations not limited to $m\times{}4$ codes and relying on AVX-512, the latest revision of SIMD instruction set. In doing so, Quicker ADC faces the challenge of using efficiently 5,6 and 7-bit shuffles that do not align to computer bytes or words. To this end, we introduce (i) irregular product quantizers combining sub-quantizers of different granularity and (ii) split tables allowing lookup tables larger than registers. We evaluate Quicker ADC with multiple indexes including Inverted Multi-Indexes and IVF HNSW and show that it outperforms FAISS PQ implementation and optimization (i.e., Polysemous codes) for numerous configurations. Finally, we open-source at <a href="http://github.com/technicolor-research/faiss-quickeradc">this http URL</a> a fork of FAISS that includes Quicker ADC.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.09162](http://arxiv.org/abs/1812.09162)

##### PDF
[http://arxiv.org/pdf/1812.09162](http://arxiv.org/pdf/1812.09162)

