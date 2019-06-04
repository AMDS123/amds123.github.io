---
layout: post
title: "Problem-Agnostic Speech Embeddings for Multi-Speaker Text-to-Speech with SampleRNN"
date: 2019-06-03 12:15:56
categories: arXiv_SD
tags: arXiv_SD Embedding Inference RNN
author: David &#xc1;lvarez, Santiago Pascual, Antonio Bonafonte
mathjax: true
---

* content
{:toc}

##### Abstract
Text-to-speech (TTS) acoustic models map linguistic features into an acoustic representation out of which an audible waveform is generated. The latest and most natural TTS systems build a direct mapping between linguistic and waveform domains, like SampleRNN. This way, possible signal naturalness losses are avoided as intermediate acoustic representations are discarded. Another important dimension of study apart from naturalness is their adaptability to generate voice from new speakers that were unseen during training. In this paper we first propose the use of problem-agnostic speech embeddings in a multi-speaker acoustic model for TTS based on SampleRNN. This way we feed the acoustic model with speaker acoustically dependent representations that enrich the waveform generation more than discrete embeddings unrelated to these factors. Our first results suggest that the proposed embeddings lead to better quality voices than those obtained with discrete embeddings. Furthermore, as we can use any speech segment as an encoded representation during inference, the model is capable to generalize to new speaker identities without retraining the network. We finally show that, with a small increase of speech duration in the embedding extractor, we dramatically reduce the spectral distortion to close the gap towards the target identities.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.00733](http://arxiv.org/abs/1906.00733)

##### PDF
[http://arxiv.org/pdf/1906.00733](http://arxiv.org/pdf/1906.00733)

