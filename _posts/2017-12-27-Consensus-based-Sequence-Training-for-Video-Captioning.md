---
layout: post
title: "Consensus-based Sequence Training for Video Captioning"
date: 2017-12-27 09:38:52
categories: arXiv_CV
tags: arXiv_CV Video_Caption Reinforcement_Learning Caption
author: Sang Phan, Gustav Eje Henter, Yusuke Miyao, Shin'ichi Satoh
mathjax: true
---

* content
{:toc}

##### Abstract
Captioning models are typically trained using the cross-entropy loss. However, their performance is evaluated on other metrics designed to better correlate with human assessments. Recently, it has been shown that reinforcement learning (RL) can directly optimize these metrics in tasks such as captioning. However, this is computationally costly and requires specifying a baseline reward at each step to make training converge. We propose a fast approach to optimize one's objective of interest through the REINFORCE algorithm. First we show that, by replacing model samples with ground-truth sentences, RL training can be seen as a form of weighted cross-entropy loss, giving a fast, RL-based pre-training algorithm. Second, we propose to use the consensus among ground-truth captions of the same video as the baseline reward. This can be computed very efficiently. We call the complete proposal Consensus-based Sequence Training (CST). Applied to the MSRVTT video captioning benchmark, our proposals train significantly faster than comparable methods and establish a new state-of-the-art on the task, improving the CIDEr score from 47.3 to 54.2.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1712.09532](https://arxiv.org/abs/1712.09532)

##### PDF
[https://arxiv.org/pdf/1712.09532](https://arxiv.org/pdf/1712.09532)

