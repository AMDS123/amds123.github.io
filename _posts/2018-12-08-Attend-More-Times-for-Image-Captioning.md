---
layout: post
title: "Attend More Times for Image Captioning"
date: 2018-12-08 08:23:33
categories: arXiv_CV
tags: arXiv_CV Image_Caption Attention Caption RNN
author: Jiajun Du, Yu Qin, Hongtao Lu, Yonghua Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Most attention-based image captioning models attend to the image once per word. However, attending once per word is rigid and is easy to miss some information. Attending more times can adjust the attention position, find the missing information back and avoid generating the wrong word. In this paper, we show that attending more times per word can gain improvements in the image captioning task. We propose a flexible two-LSTM merge model to make it convenient to encode more attentions than words. Our captioning model uses two LSTMs to encode the word sequence and the attention sequence respectively. The information of the two LSTMs and the image feature are combined to predict the next word. Experiments on the MSCOCO caption dataset show that our method outperforms the state-of-the-art. Using bottom up features and self-critical training method, our method gets BLEU-4, METEOR, ROUGE-L and CIDEr scores of 0.381, 0.283, 0.580 and 1.261 on the Karpathy test split.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.03283](http://arxiv.org/abs/1812.03283)

##### PDF
[http://arxiv.org/pdf/1812.03283](http://arxiv.org/pdf/1812.03283)

