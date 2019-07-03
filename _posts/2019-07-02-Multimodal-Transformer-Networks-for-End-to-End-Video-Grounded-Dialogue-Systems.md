---
layout: post
title: "Multimodal Transformer Networks for End-to-End Video-Grounded Dialogue Systems"
date: 2019-07-02 04:54:17
categories: arXiv_CL
tags: arXiv_CL Attention Caption Inference RNN
author: Hung Le, Doyen Sahoo, Nancy F. Chen, Steven C.H. Hoi
mathjax: true
---

* content
{:toc}

##### Abstract
Developing Video-Grounded Dialogue Systems (VGDS), where a dialogue is conducted based on visual and audio aspects of a given video, is significantly more challenging than traditional image or text-grounded dialogue systems because (1) feature space of videos span across multiple picture frames, making it difficult to obtain semantic information; and (2) a dialogue agent must perceive and process information from different modalities (audio, video, caption, etc.) to obtain a comprehensive understanding. Most existing work is based on RNNs and sequence-to-sequence architectures, which are not very effective for capturing complex long-term dependencies (like in videos). To overcome this, we propose Multimodal Transformer Networks (MTN) to encode videos and incorporate information from different modalities. We also propose query-aware attention through an auto-encoder to extract query-aware features from non-text modalities. We develop a training procedure to simulate token-level decoding to improve the quality of generated responses during inference. We get state of the art performance on Dialogue System Technology Challenge 7 (DSTC7). Our model also generalizes to another multimodal visual-grounded dialogue task, and obtains promising performance. We implemented our models using PyTorch and the code is released at https://github.com/henryhungle/MTN.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.01166](http://arxiv.org/abs/1907.01166)

##### PDF
[http://arxiv.org/pdf/1907.01166](http://arxiv.org/pdf/1907.01166)

