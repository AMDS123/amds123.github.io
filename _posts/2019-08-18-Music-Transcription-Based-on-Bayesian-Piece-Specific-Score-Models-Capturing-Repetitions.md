---
layout: post
title: "Music Transcription Based on Bayesian Piece-Specific Score Models Capturing Repetitions"
date: 2019-08-18 14:26:59
categories: arXiv_AI
tags: arXiv_AI Sparse Inference Language_Model
author: Eita Nakamura, Kazuyoshi Yoshii
mathjax: true
---

* content
{:toc}

##### Abstract
Most work on models for music transcription has focused on describing local sequential dependence of notes in musical scores and failed to capture their global repetitive structure, which can be a useful guide for transcribing music. Focusing on the rhythm, we formulate several classes of Bayesian Markov models of musical scores that describe repetitions indirectly by sparse transition probabilities of notes or note patterns. This enables us to construct piece-specific models for unseen scores with unfixed repetitive structure and to derive tractable inference algorithms. Moreover, to describe approximate repetitions, we explicitly incorporate a process of modifying the repeated notes/note patterns. We apply these models as a prior music language model for rhythm transcription, where piece-specific score models are inferred from performed MIDI data by unsupervised learning, in contrast to the conventional supervised construction of score models. Evaluations using vocal melodies of popular music showed that the Bayesian models improved the transcription accuracy for most of the tested model types, indicating the universal efficacy of the proposed approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.06969](http://arxiv.org/abs/1908.06969)

##### PDF
[http://arxiv.org/pdf/1908.06969](http://arxiv.org/pdf/1908.06969)

