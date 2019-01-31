---
layout: post
title: "Decoder-tailored Polar Code Design Using the Genetic Algorithm"
date: 2019-01-28 22:10:40
categories: arXiv_AI
tags: arXiv_AI
author: Ahmed Elkelesh, Moustafa Ebada, Sebastian Cammerer, Stephan ten Brink
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new framework for constructing polar codes (i.e., selecting the frozen bit positions) for arbitrary channels, and tailored to a given decoding algorithm, rather than based on the (not necessarily optimal) assumption of successive cancellation (SC) decoding. The proposed framework is based on the Genetic Algorithm (GenAlg), where populations (i.e., collections) of information sets evolve successively via evolutionary transformations based on their individual error-rate performance. These populations converge towards an information set that fits both the decoding behavior and the defined channel. Using our proposed algorithm over the additive white Gaussian noise (AWGN) channel, we construct a polar code of length 2048 with code rate 0.5, without the CRC-aid, tailored to plain successive cancellation list (SCL) decoding, achieving the same error-rate performance as the CRC-aided SCL decoding, and leading to a coding gain of 1 dB at BER of $10^{-6}$. Further, a belief propagation (BP)-tailored construction approaches the SCL error-rate performance without any modifications in the decoding algorithm itself. The performance gains can be attributed to the significant reduction in the total number of low-weight codewords. To demonstrate the flexibility, coding gains for the Rayleigh channel are shown under SCL and BP decoding. Besides improvements in error-rate performance, we show that, when required, the GenAlg can be also set up to reduce the decoding complexity, e.g., the SCL list size or the number of BP iterations can be reduced, while maintaining the same error-rate performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.10464](http://arxiv.org/abs/1901.10464)

##### PDF
[http://arxiv.org/pdf/1901.10464](http://arxiv.org/pdf/1901.10464)

