---
layout: post
title: "Lattice Transformer for Speech Translation"
date: 2019-06-13 08:55:06
categories: arXiv_CL
tags: arXiv_CL Segmentation Attention Speech_Recognition RNN Recognition
author: Pei Zhang, Boxing Chen, Niyu Ge, Kai Fan
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in sequence modeling have highlighted the strengths of the transformer architecture, especially in achieving state-of-the-art machine translation results. However, depending on the up-stream systems, e.g., speech recognition, or word segmentation, the input to translation system can vary greatly. The goal of this work is to extend the attention mechanism of the transformer to naturally consume the lattice in addition to the traditional sequential input. We first propose a general lattice transformer for speech translation where the input is the output of the automatic speech recognition (ASR) which contains multiple paths and posterior scores. To leverage the extra information from the lattice structure, we develop a novel controllable lattice attention mechanism to obtain latent representations. On the LDC Spanish-English speech translation corpus, our experiments show that lattice transformer generalizes significantly better and outperforms both a transformer baseline and a lattice LSTM. Additionally, we validate our approach on the WMT 2017 Chinese-English translation task with lattice inputs from different BPE segmentations. In this task, we also observe the improvements over strong baselines.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.05551](https://arxiv.org/abs/1906.05551)

##### PDF
[https://arxiv.org/pdf/1906.05551](https://arxiv.org/pdf/1906.05551)

