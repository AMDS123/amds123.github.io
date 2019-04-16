---
layout: post
title: "Morphological and Language-Agnostic Word Segmentation for NMT"
date: 2018-06-14 11:44:48
categories: arXiv_CL
tags: arXiv_CL Segmentation NMT
author: Dominik Macháček, Jonáš Vidra, Ondřej Bojar
mathjax: true
---

* content
{:toc}

##### Abstract
The state of the art of handling rich morphology in neural machine translation (NMT) is to break word forms into subword units, so that the overall vocabulary size of these units fits the practical limits given by the NMT model and GPU memory capacity. In this paper, we compare two common but linguistically uninformed methods of subword construction (BPE and STE, the method implemented in Tensor2Tensor toolkit) and two linguistically-motivated methods: Morfessor and one novel method, based on a derivational dictionary. Our experiments with German-to-Czech translation, both morphologically rich, document that so far, the non-motivated methods perform better. Furthermore, we iden- tify a critical difference between BPE and STE and show a simple pre- processing step for BPE that considerably increases translation quality as evaluated by automatic measures.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1806.05482](https://arxiv.org/abs/1806.05482)

##### PDF
[https://arxiv.org/pdf/1806.05482](https://arxiv.org/pdf/1806.05482)

