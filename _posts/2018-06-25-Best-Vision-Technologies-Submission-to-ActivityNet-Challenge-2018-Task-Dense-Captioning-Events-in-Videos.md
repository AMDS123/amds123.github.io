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
本笔记描述了我们对ActivityNet Challenge 2018视频任务中的密集字幕事件的解决方案的详细信息。具体而言，我们采用两阶段方式解决此问题，即首先提出时间事件建议，然后再生成句子。对于时间事件提议，我们直接利用[13,16]中的三阶段工作流程。对于句子生成，我们利用基于LSTM的字幕框架和时间关注机制（称为LSTM-T）。此外，基于LSTM的视频字幕模型的输入视觉序列由RGB和光流图像组成。在推论中，我们采用后期融合方案来融合两种基于LSTM的字幕模型来生成句子。

##### URL
[http://arxiv.org/abs/1806.09278](http://arxiv.org/abs/1806.09278)

##### PDF
[http://arxiv.org/pdf/1806.09278](http://arxiv.org/pdf/1806.09278)

