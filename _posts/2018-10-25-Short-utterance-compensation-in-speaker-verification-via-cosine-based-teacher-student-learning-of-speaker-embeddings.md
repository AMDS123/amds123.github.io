---
layout: post
title: "Short utterance compensation in speaker verification via cosine-based teacher-student learning of speaker embeddings"
date: 2018-10-25 14:03:01
categories: arXiv_AI
tags: arXiv_AI Embedding CNN
author: Jee-weon Jung, Hee-soo Heo, Hye-jin Shim, Ha-jin Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Input utterance with short duration is one of the most critical threats that degrade the performance of speaker verification systems. This study aimed to develop an integrated text-independent speaker verification system that inputs utterances with short durations of 2.05 seconds. For this goal, we propose an approach using a teacher-student learning framework that maximizes the cosine similarity of two speaker embeddings extracted from long and short utterances. In the proposed architecture, phonetic-level features in which each feature represents a segment of 130 ms are extracted using convolutional layers. The gated recurrent units extract an utterance-level speaker embedding using the phonetic-level features. Experiments were conducted using deep neural networks that take raw waveforms as input, and output speaker embeddings on the VoxCeleb 1 dataset. The equal error rates without short utterance compensation are 8.72 % and 12.8 %, for evaluation sets with durations of 3.59 s and 2.05 s, respectively. The proposed model with compensation exhibits an equal error rate of 10.08 % for 2.05 s utterances, which compensates more than 65 % of the performance degradation.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.10884](https://arxiv.org/abs/1810.10884)

##### PDF
[https://arxiv.org/pdf/1810.10884](https://arxiv.org/pdf/1810.10884)

