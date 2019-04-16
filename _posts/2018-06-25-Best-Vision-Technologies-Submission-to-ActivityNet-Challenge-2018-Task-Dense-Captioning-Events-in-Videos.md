---
layout: post
title: "Best Vision Technologies Submission to ActivityNet Challenge 2018-Task: Dense-Captioning Events in Videos"
date: 2018-06-25 04:11:03
categories: arXiv_CV
tags: arXiv_CV Video_Caption Attention Caption Inference RNN
author: Yuan Liu, Moyini Yao
mathjax: true
---

* content
{:toc}

##### Abstract
This note describes the details of our solution to the dense-captioning events in videos task of ActivityNet Challenge 2018. Specifically, we solve this problem with a two-stage way, i.e., first temporal event proposal and then sentence generation. For temporal event proposal, we directly leverage the three-stage workflow in [13, 16]. For sentence generation, we capitalize on LSTM-based captioning framework with temporal attention mechanism (dubbed as LSTM-T). Moreover, the input visual sequence to the LSTM-based video captioning model is comprised of RGB and optical flow images. At inference, we adopt a late fusion scheme to fuse the two LSTM-based captioning models for sentence generation.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1806.09278](https://arxiv.org/abs/1806.09278)

##### PDF
[https://arxiv.org/pdf/1806.09278](https://arxiv.org/pdf/1806.09278)

