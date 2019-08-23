---
layout: post
title: "Denoising based Sequence-to-Sequence Pre-training for Text Generation"
date: 2019-08-22 05:26:25
categories: arXiv_CL
tags: arXiv_CL Summarization Text_Generation
author: Liang Wang, Wei Zhao, Ruoyu Jia, Sujian Li, Jingming Liu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a new sequence-to-sequence (seq2seq) pre-training method PoDA (Pre-training of Denoising Autoencoders), which learns representations suitable for text generation tasks. Unlike encoder-only (e.g., BERT) or decoder-only (e.g., OpenAI GPT) pre-training approaches, PoDA jointly pre-trains both the encoder and decoder by denoising the noise-corrupted text, and it also has the advantage of keeping the network architecture unchanged in the subsequent fine-tuning stage. Meanwhile, we design a hybrid model of Transformer and pointer-generator networks as the backbone architecture for PoDA. We conduct experiments on two text generation tasks: abstractive summarization, and grammatical error correction. Results on four datasets show that PoDA can improve model performance over strong baselines without using any task-specific techniques and significantly speed up convergence.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.08206](https://arxiv.org/abs/1908.08206)

##### PDF
[https://arxiv.org/pdf/1908.08206](https://arxiv.org/pdf/1908.08206)

