---
layout: post
title: "Deep convolutional neural networks for predominant instrument recognition in polyphonic music"
date: 2016-12-26 12:29:26
categories: arXiv_CV
tags: arXiv_CV CNN Recognition
author: Yoonchang Han, Jaehun Kim, Kyogu Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Identifying musical instruments in polyphonic music recordings is a challenging but important problem in the field of music information retrieval. It enables music search by instrument, helps recognize musical genres, or can make music transcription easier and more accurate. In this paper, we present a convolutional neural network framework for predominant instrument recognition in real-world polyphonic music. We train our network from fixed-length music excerpts with a single-labeled predominant instrument and estimate an arbitrary number of predominant instruments from an audio signal with a variable length. To obtain the audio-excerpt-wise result, we aggregate multiple outputs from sliding windows over the test audio. In doing so, we investigated two different aggregation methods: one takes the average for each instrument and the other takes the instrument-wise sum followed by normalization. In addition, we conducted extensive experiments on several important factors that affect the performance, including analysis window size, identification threshold, and activation functions for neural networks to find the optimal set of parameters. Using a dataset of 10k audio excerpts from 11 instruments for evaluation, we found that convolutional neural networks are more robust than conventional methods that exploit spectral features and source separation with support vector machines. Experimental results showed that the proposed convolutional network architecture obtained an F1 measure of 0.602 for micro and 0.503 for macro, respectively, achieving 19.6% and 16.4% in performance improvement compared with other state-of-the-art algorithms.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1605.09507](https://arxiv.org/abs/1605.09507)

##### PDF
[https://arxiv.org/pdf/1605.09507](https://arxiv.org/pdf/1605.09507)

