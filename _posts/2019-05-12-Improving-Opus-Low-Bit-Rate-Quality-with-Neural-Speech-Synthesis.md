---
layout: post
title: "Improving Opus Low Bit Rate Quality with Neural Speech Synthesis"
date: 2019-05-12 02:17:05
categories: arXiv_SD
tags: arXiv_SD RNN
author: Jan Skoglund, Jean-Marc Valin
mathjax: true
---

* content
{:toc}

##### Abstract
The voice mode of the Opus audio coder can compress wideband speech at bit rates ranging from 6 kb/s to 40 kb/s. However, Opus is at its core a waveform matching coder, and as the rate drops below 10 kb/s, quality degrades quickly. As the rate reduces even further, parametric coders tend to perform better than waveform coders. In this paper we propose a backward-compatible way of improving low bit rate Opus quality by re-synthesizing speech from the decoded parameters. We compare two different neural generative models, WaveNet and LPCNet. WaveNet is a powerful, high-complexity, and high-latency architecture that is not feasible for a practical system, yet provides a best known achievable quality with generative models. LPCNet is a low-complexity, low-latency RNN-based generative model, and practically implementable on mobile phones. We apply these systems with parameters from Opus coded at 6 kb/s as conditioning features for the generative models. Listening tests show that for the same 6 kb/s Opus bit stream, synthesized speech using LPCNet clearly outperforms the output of the standard Opus decoder. This opens up ways to improve the quality of existing speech and audio waveform coders without breaking compatibility.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.04628](http://arxiv.org/abs/1905.04628)

##### PDF
[http://arxiv.org/pdf/1905.04628](http://arxiv.org/pdf/1905.04628)

