---
layout: post
title: "From FiLM to Video: Multi-turn Question Answering with Multi-modal Context"
date: 2018-12-17 19:41:37
categories: arXiv_CV
tags: arXiv_CV GAN Embedding RNN
author: Dat Tien Nguyen, Shikhar Sharma, Hannes Schulz, Layla El Asri
mathjax: true
---

* content
{:toc}

##### Abstract
Understanding audio-visual content and the ability to have an informative conversation about it have both been challenging areas for intelligent systems. The Audio Visual Scene-aware Dialog (AVSD) challenge, organized as a track of the Dialog System Technology Challenge 7 (DSTC7), proposes a combined task, where a system has to answer questions pertaining to a video given a dialogue with previous question-answer pairs and the video itself. We propose for this task a hierarchical encoder-decoder model which computes a multi-modal embedding of the dialogue context. It first embeds the dialogue history using two LSTMs. We extract video and audio frames at regular intervals and compute semantic features using pre-trained I3D and VGGish models, respectively. Before summarizing both modalities into fixed-length vectors using LSTMs, we use FiLM blocks to condition them on the embeddings of the current question, which allows us to reduce the dimensionality considerably. Finally, we use an LSTM decoder that we train with scheduled sampling and evaluate using beam search. Compared to the modality-fusing baseline model released by the AVSD challenge organizers, our model achieves a relative improvements of more than 16%, scoring 0.36 BLEU-4 and more than 33%, scoring 0.997 CIDEr.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.07023](http://arxiv.org/abs/1812.07023)

##### PDF
[http://arxiv.org/pdf/1812.07023](http://arxiv.org/pdf/1812.07023)

