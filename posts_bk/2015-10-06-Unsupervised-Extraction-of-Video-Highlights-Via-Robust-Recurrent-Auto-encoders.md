---
layout: post
title: "Unsupervised Extraction of Video Highlights Via Robust Recurrent Auto-encoders"
date: 2015-10-06 06:07:50
categories: arXiv_CV
tags: arXiv_CV RNN
author: Huan Yang, Baoyuan Wang, Stephen Lin, David Wipf, Minyi Guo, Baining Guo
mathjax: true
---

* content
{:toc}

##### Abstract
With the growing popularity of short-form video sharing platforms such as \em{Instagram} and \em{Vine}, there has been an increasing need for techniques that automatically extract highlights from video. Whereas prior works have approached this problem with heuristic rules or supervised learning, we present an unsupervised learning approach that takes advantage of the abundance of user-edited videos on social media websites such as YouTube. Based on the idea that the most significant sub-events within a video class are commonly present among edited videos while less interesting ones appear less frequently, we identify the significant sub-events via a robust recurrent auto-encoder trained on a collection of user-edited videos queried for each particular class of interest. The auto-encoder is trained using a proposed shrinking exponential loss function that makes it robust to noise in the web-crawled training data, and is configured with bidirectional long short term memory (LSTM)~\cite{LSTM:97} cells to better model the temporal structure of highlight segments. Different from supervised techniques, our method can infer highlights using only a set of downloaded edited videos, without also needing their pre-edited counterparts which are rarely available online. Extensive experiments indicate the promise of our proposed solution in this challenging unsupervised settin

##### Abstract (translated by Google)
随着\ em {Instagram}和\ em {Vine}等短视频分享平台的日益普及，人们越来越需要自动从视频中提取精彩片段的技术。鉴于之前的作品通过启发式规则或监督式学习来解决这个问题，我们提出了一种无监督的学习方法，利用YouTube等社交媒体网站上丰富的用户编辑视频。基于视频类别中最重要的子事件普遍存在于编辑的视频中的想法，而不太有趣的子事件不太频繁地出现，我们通过在一组用户定制的视频类别上训练的强大的经常性自动编码器来识别重要的子事件，为每个感兴趣的特定类别查询编辑的视频。使用提出的收缩指数损失函数训练自动编码器，使其对网络抓取的训练数据中的噪声具有鲁棒性，并且使用双向长期短期记忆（LSTM）单元{LSTM：97}建模高亮段的时间结构。与监督技术不同，我们的方法可以仅使用一组下载的编辑视频来推断高光，而不需要预先编辑的在线很少可用的对应部分。广泛的实验表明，我们提出的解决方案在这个具有挑战性的无监督settin的承诺

##### URL
[https://arxiv.org/abs/1510.01442](https://arxiv.org/abs/1510.01442)

##### PDF
[https://arxiv.org/pdf/1510.01442](https://arxiv.org/pdf/1510.01442)

