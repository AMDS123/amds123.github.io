---
layout: post
title: "Robust Sequence-to-Sequence Acoustic Modeling with Stepwise Monotonic Attention for Neural TTS"
date: 2019-06-03 09:52:19
categories: arXiv_CL
tags: arXiv_CL Attention Inference
author: Mutian He, Yan Deng, Lei He
mathjax: true
---

* content
{:toc}

##### Abstract
Neural TTS has demonstrated strong capabilities to generate human-like speech with high quality and naturalness, while its generalization to out-of-domain texts is still a challenging task, with regard to the design of attention-based sequence-to-sequence acoustic modeling. Various errors occur in those texts with unseen context, including attention collapse, skipping, repeating, etc., which limits the broader applications. In this paper, we propose a novel stepwise monotonic attention method in sequence-to-sequence acoustic modeling to improve the robustness on out-of-domain texts. The method utilizes the strict monotonic property in TTS with extra constraints on monotonic attention that the alignments between inputs and outputs sequence must be not only monotonic but also allowing no skipping on the inputs. In inference, soft attention could be used to evade mismatch between training and test in monotonic hard attention. The experimental results show that the proposed method could achieve significant improvements in robustness on various out-of-domain scenarios, without any regression on the in-domain test set.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.00672](http://arxiv.org/abs/1906.00672)

##### PDF
[http://arxiv.org/pdf/1906.00672](http://arxiv.org/pdf/1906.00672)

