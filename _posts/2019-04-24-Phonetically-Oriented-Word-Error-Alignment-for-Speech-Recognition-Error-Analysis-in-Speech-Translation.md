---
layout: post
title: "Phonetically-Oriented Word Error Alignment for Speech Recognition Error Analysis in Speech Translation"
date: 2019-04-24 19:09:35
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Recognition
author: Nicholas Ruiz, Marcello Federico
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a variation to the commonly used Word Error Rate (WER) metric for speech recognition evaluation which incorporates the alignment of phonemes, in the absence of time boundary information. After computing the Levenshtein alignment on words in the reference and hypothesis transcripts, spans of adjacent errors are converted into phonemes with word and syllable boundaries and a phonetic Levenshtein alignment is performed. The aligned phonemes are recombined into aligned words that adjust the word alignment labels in each error region. We demonstrate that our Phonetically-Oriented Word Error Rate (POWER) yields similar scores to WER with the added advantages of better word alignments and the ability to capture one-to-many word alignments corresponding to homophonic errors in speech recognition hypotheses. These improved alignments allow us to better trace the impact of Levenshtein error types on downstream tasks such as speech translation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.11024](http://arxiv.org/abs/1904.11024)

##### PDF
[http://arxiv.org/pdf/1904.11024](http://arxiv.org/pdf/1904.11024)

