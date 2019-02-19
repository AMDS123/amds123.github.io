---
layout: post
title: "Letter-Based Speech Recognition with Gated ConvNets"
date: 2019-02-16 01:19:21
categories: arXiv_AI
tags: arXiv_AI Speech_Recognition Inference Recognition
author: Vitaliy Liptchinsky, Gabriel Synnaeve, Ronan Collobert
mathjax: true
---

* content
{:toc}

##### Abstract
In the recent literature, "end-to-end" speech systems often refer to letter-based acoustic models trained in a sequence-to-sequence manner, either via a recurrent model or via a structured output learning approach (such as CTC). In contrast to traditional phone (or senone)-based approaches, these "end-to-end'' approaches alleviate the need of word pronunciation modeling, and do not require a "forced alignment" step at training time. Phone-based approaches remain however state of the art on classical benchmarks. In this paper, we propose a letter-based speech recognition system, leveraging a ConvNet acoustic model. Key ingredients of the ConvNet are Gated Linear Units and high dropout. The ConvNet is trained to map audio sequences to their corresponding letter transcriptions, either via a classical CTC approach, or via a recent variant called ASG. Coupled with a simple decoder at inference time, our system matches the best existing letter-based systems on WSJ (in word error rate), and shows near state of the art performance on LibriSpeech.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1712.09444](http://arxiv.org/abs/1712.09444)

##### PDF
[http://arxiv.org/pdf/1712.09444](http://arxiv.org/pdf/1712.09444)

