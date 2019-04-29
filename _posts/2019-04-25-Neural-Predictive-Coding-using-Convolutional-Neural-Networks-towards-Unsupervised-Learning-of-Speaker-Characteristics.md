---
layout: post
title: "Neural Predictive Coding using Convolutional Neural Networks towards Unsupervised Learning of Speaker Characteristics"
date: 2019-04-25 23:27:08
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Embedding CNN Recognition
author: Arindam Jati, Panayiotis Georgiou
mathjax: true
---

* content
{:toc}

##### Abstract
Learning speaker-specific features is vital in many applications like speaker recognition, diarization and speech recognition. This paper provides a novel approach, we term Neural Predictive Coding (NPC), to learn speaker-specific characteristics in a completely unsupervised manner from large amounts of unlabeled training data that even contain many non-speech events and multi-speaker audio streams. The NPC framework exploits the proposed short-term active-speaker stationarity hypothesis which assumes two temporally-close short speech segments belong to the same speaker, and thus a common representation that can encode the commonalities of both the segments, should capture the vocal characteristics of that speaker. We train a convolutional deep siamese network to produce "speaker embeddings" by learning to separate `same' vs `different' speaker pairs which are generated from an unlabeled data of audio streams. Two sets of experiments are done in different scenarios to evaluate the strength of NPC embeddings and compare with state-of-the-art in-domain supervised methods. First, two speaker identification experiments with different context lengths are performed in a scenario with comparatively limited within-speaker channel variability. NPC embeddings are found to perform the best at short duration experiment, and they provide complementary information to i-vectors for full utterance experiments. Second, a large scale speaker verification task having a wide range of within-speaker channel variability is adopted as an upper-bound experiment where comparisons are drawn with in-domain supervised methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1802.07860](http://arxiv.org/abs/1802.07860)

##### PDF
[http://arxiv.org/pdf/1802.07860](http://arxiv.org/pdf/1802.07860)

