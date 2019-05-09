---
layout: post
title: "A Hardware-Oriented and Memory-Efficient Method for CTC Decoding"
date: 2019-05-08 15:59:33
categories: arXiv_AI
tags: arXiv_AI Speech_Recognition Inference RNN Classification Language_Model Recognition
author: Siyuan Lu, Jinming Lu, Jun Lin, Zhongfeng Wang
mathjax: true
---

* content
{:toc}

##### Abstract
The Connectionist Temporal Classification (CTC) has achieved great success in sequence to sequence analysis tasks such as automatic speech recognition (ASR) and scene text recognition (STR). These applications can use the CTC objective function to train the recurrent neural networks (RNNs), and decode the outputs of RNNs during inference. While hardware architectures for RNNs have been studied, hardware-based CTCdecoders are desired for high-speed CTC-based inference systems. This paper, for the first time, provides a low-complexity and memory-efficient approach to build a CTC-decoder based on the beam search decoding. Firstly, we improve the beam search decoding algorithm to save the storage space. Secondly, we compress a dictionary (reduced from 26.02MB to 1.12MB) and use it as the language model. Meanwhile searching this dictionary is trivial. Finally, a fixed-point CTC-decoder for an English ASR and an STR task using the proposed method is implemented with C++ language. It is shown that the proposed method has little precision loss compared with its floating-point counterpart. Our experiments demonstrate the compression ratio of the storage required by the proposed beam search decoding algorithm are 29.49 (ASR) and 17.95 (STR).

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.03175](https://arxiv.org/abs/1905.03175)

##### PDF
[https://arxiv.org/pdf/1905.03175](https://arxiv.org/pdf/1905.03175)

