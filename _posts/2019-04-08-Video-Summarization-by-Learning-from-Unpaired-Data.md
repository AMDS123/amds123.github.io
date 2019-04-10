---
layout: post
title: "Video Summarization by Learning from Unpaired Data"
date: 2019-04-08 20:50:01
categories: arXiv_CV
tags: arXiv_CV Adversarial Summarization
author: Mrigank Rochan, Yang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of video summarization. Given an input raw video, the goal is to select a small subset of key frames from the input video to create a shorter summary video that best describes the content of the original video. Most of the current state-of-the-art video summarization approaches use supervised learning and require labeled training data. Each training instance consists of a raw input video and its ground truth summary video curated by human annotators. However, it is very expensive and difficult to create such labeled training examples. To address this limitation, we propose a novel formulation to learn video summarization from unpaired data. We present an approach that learns to generate optimal video summaries using a set of raw videos ($V$) and a set of summary videos ($S$), where there exists no correspondence between $V$ and $S$. We argue that this type of data is much easier to collect. Our model aims to learn a mapping function $F : V \rightarrow S$ such that the distribution of resultant summary videos from $F(V)$ is similar to the distribution of $S$ with the help of an adversarial objective. In addition, we enforce a diversity constraint on $F(V)$ to ensure that the generated video summaries are visually diverse. Experimental results on two benchmark datasets indicate that our proposed approach significantly outperforms other alternative methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.12174](http://arxiv.org/abs/1805.12174)

##### PDF
[http://arxiv.org/pdf/1805.12174](http://arxiv.org/pdf/1805.12174)

