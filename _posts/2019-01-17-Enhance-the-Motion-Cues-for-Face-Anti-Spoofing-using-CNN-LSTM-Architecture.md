---
layout: post
title: "Enhance the Motion Cues for Face Anti-Spoofing using CNN-LSTM Architecture"
date: 2019-01-17 05:58:22
categories: arXiv_CV
tags: arXiv_CV Attention Face CNN RNN
author: Xiaoguang Tu, Hengsheng Zhang, Mei Xie, Yao Luo, Yuefei Zhang, Zheng Ma
mathjax: true
---

* content
{:toc}

##### Abstract
Spatio-temporal information is very important to capture the discriminative cues between genuine and fake faces from video sequences. To explore such a temporal feature, the fine-grained motions (e.g., eye blinking, mouth movements and head swing) across video frames are very critical. In this paper, we propose a joint CNN-LSTM network for face anti-spoofing, focusing on the motion cues across video frames. We first extract the high discriminative features of video frames using the conventional Convolutional Neural Network (CNN). Then we leverage Long Short-Term Memory (LSTM) with the extracted features as inputs to capture the temporal dynamics in videos. To ensure the fine-grained motions more easily to be perceived in the training process, the eulerian motion magnification is used as the preprocessing to enhance the facial expressions exhibited by individuals, and the attention mechanism is embedded in LSTM to ensure the model learn to focus selectively on the dynamic frames across the video clips. Experiments on Replay Attack and MSU-MFSD databases show that the proposed method yields state-of-the-art performance with better generalization ability compared with several other popular algorithms.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.05635](https://arxiv.org/abs/1901.05635)

##### PDF
[https://arxiv.org/pdf/1901.05635](https://arxiv.org/pdf/1901.05635)

