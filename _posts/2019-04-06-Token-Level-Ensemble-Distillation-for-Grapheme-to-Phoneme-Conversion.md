---
layout: post
title: "Token-Level Ensemble Distillation for Grapheme-to-Phoneme Conversion"
date: 2019-04-06 13:49:16
categories: arXiv_CL
tags: arXiv_CL Knowledge Speech_Recognition RNN Recognition
author: Hao Sun, Xu Tan, Jun-Wei Gan, Hongzhi Liu, Sheng Zhao, Tao Qin, Tie-Yan Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Grapheme-to-phoneme (G2P) conversion is an important task in automatic speech recognition and text-to-speech systems. Recently, G2P conversion is viewed as a sequence to sequence task and modeled by RNN or CNN based encoder-decoder framework. However, previous works do not consider the practical issues when deploying G2P model in the production system, such as how to leverage additional unlabeled data to boost the accuracy, as well as reduce model size for online deployment. In this work, we propose token-level ensemble distillation for G2P conversion, which can (1) boost the accuracy by distilling the knowledge from additional unlabeled data, and (2) reduce the model size but maintain the high accuracy, both of which are very practical and helpful in the online production system. We use token-level knowledge distillation, which results in better accuracy than the sequence-level counterpart. What is more, we adopt the Transformer instead of RNN or CNN based models to further boost the accuracy of G2P conversion. Experiments on the publicly available CMUDict dataset and an internal English dataset demonstrate the effectiveness of our proposed method. Particularly, our method achieves 19.88% WER on CMUDict dataset, outperforming the previous works by more than 4.22% WER, and setting the new state-of-the-art results.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03446](http://arxiv.org/abs/1904.03446)

##### PDF
[http://arxiv.org/pdf/1904.03446](http://arxiv.org/pdf/1904.03446)

