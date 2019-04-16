---
layout: post
title: "Video Captioning with Boundary-aware Hierarchical Language Decoding and Joint Video Prediction"
date: 2018-07-08 08:49:34
categories: arXiv_CV
tags: arXiv_CV Video_Caption Attention Caption RNN Language_Model Prediction
author: Xiangxi Shi, Jianfei Cai, Jiuxiang Gu, Shafiq Joty
mathjax: true
---

* content
{:toc}

##### Abstract
The explosion of video data on the internet requires effective and efficient technology to generate captions automatically for people who are not able to watch the videos. Despite the great progress of video captioning research, particularly on video feature encoding, the language decoder is still largely based on the prevailing RNN decoder such as LSTM, which tends to prefer the frequent word that aligns with the video. In this paper, we propose a boundary-aware hierarchical language decoder for video captioning, which consists of a high-level GRU based language decoder, working as a global (caption-level) language model, and a low-level GRU based language decoder, working as a local (phrase-level) language model. Most importantly, we introduce a binary gate into the low-level GRU language decoder to detect the language boundaries. Together with other advanced components including joint video prediction, shared soft attention, and boundary-aware video encoding, our integrated video captioning framework can discover hierarchical language information and distinguish the subject and the object in a sentence, which are usually confusing during the language generation. Extensive experiments on two widely-used video captioning datasets, MSR-Video-to-Text (MSR-VTT) \cite{xu2016msr} and YouTube-to-Text (MSVD) \cite{chen2011collecting} show that our method is highly competitive, compared with the state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1807.03658](https://arxiv.org/abs/1807.03658)

##### PDF
[https://arxiv.org/pdf/1807.03658](https://arxiv.org/pdf/1807.03658)

