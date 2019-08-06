---
layout: post
title: "Pretraining by Backtranslation for End-to-end ASR in Low-Resource Settings"
date: 2019-08-02 22:40:48
categories: arXiv_CL
tags: arXiv_CL Attention
author: Matthew Wiesner, Adithya Renduchintala, Shinji Watanabe, Chunxi Liu, Najim Dehak, Sanjeev Khudanpur
mathjax: true
---

* content
{:toc}

##### Abstract
We explore training attention-based encoder-decoder ASR in low-resource settings. These models perform poorly when trained on small amounts of transcribed speech, in part because they depend on having sufficient target-side text to train the attention and decoder networks. In this paper we address this shortcoming by pretraining our network parameters using only text-based data and transcribed speech from other languages. We analyze the relative contributions of both sources of data. Across 3 test languages, our text-based approach resulted in a 20% average relative improvement over a text-based augmentation technique without pretraining. Using transcribed speech from nearby languages gives a further 20-30% relative reduction in character error rate.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.03919](http://arxiv.org/abs/1812.03919)

##### PDF
[http://arxiv.org/pdf/1812.03919](http://arxiv.org/pdf/1812.03919)

