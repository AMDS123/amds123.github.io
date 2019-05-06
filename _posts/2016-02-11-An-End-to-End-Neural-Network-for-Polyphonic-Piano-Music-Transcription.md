---
layout: post
title: "An End-to-End Neural Network for Polyphonic Piano Music Transcription"
date: 2016-02-11 12:59:35
categories: arXiv_CV
tags: arXiv_CV Speech_Recognition CNN Inference Language_Model Prediction Relation Recognition
author: Siddharth Sigtia, Emmanouil Benetos, Simon Dixon
mathjax: true
---

* content
{:toc}

##### Abstract
We present a supervised neural network model for polyphonic piano music transcription. The architecture of the proposed model is analogous to speech recognition systems and comprises an acoustic model and a music language model. The acoustic model is a neural network used for estimating the probabilities of pitches in a frame of audio. The language model is a recurrent neural network that models the correlations between pitch combinations over time. The proposed model is general and can be used to transcribe polyphonic music without imposing any constraints on the polyphony. The acoustic and language model predictions are combined using a probabilistic graphical model. Inference over the output variables is performed using the beam search algorithm. We perform two sets of experiments. We investigate various neural network architectures for the acoustic models and also investigate the effect of combining acoustic and music language model predictions using the proposed architecture. We compare performance of the neural network based acoustic models with two popular unsupervised acoustic models. Results show that convolutional neural network acoustic models yields the best performance across all evaluation metrics. We also observe improved performance with the application of the music language models. Finally, we present an efficient variant of beam search that improves performance and reduces run-times by an order of magnitude, making the model suitable for real-time applications.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1508.01774](https://arxiv.org/abs/1508.01774)

##### PDF
[https://arxiv.org/pdf/1508.01774](https://arxiv.org/pdf/1508.01774)

