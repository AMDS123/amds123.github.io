---
layout: post
title: "Another Diversity-Promoting Objective Function for Neural Dialogue Generation"
date: 2018-11-20 07:15:31
categories: arXiv_CL
tags: arXiv_CL
author: Ryo Nakamura, Katsuhito Sudoh, Koichiro Yoshino, Satoshi Nakamura
mathjax: true
---

* content
{:toc}

##### Abstract
Although generation-based dialogue systems have been widely researched, the response generations by most existing systems have very low diversities. The most likely reason for this problem is Maximum Likelihood Estimation (MLE) with Softmax Cross-Entropy (SCE) loss. MLE trains models to generate the most frequent responses from enormous generation candidates, although in actual dialogues there are various responses based on the context. In this paper, we propose a new objective function called Inverse Token Frequency (ITF) loss, which individually scales smaller loss for frequent token classes and larger loss for rare token classes. This function encourages the model to generate rare tokens rather than frequent tokens. It does not complicate the model and its training is stable because we only replace the objective function. On the OpenSubtitles dialogue dataset, our loss model establishes a state-of-the-art DIST-1 of 7.56, which is the unigram diversity score, while maintaining a good BLEU-1 score. On a Japanese Twitter replies dataset, our loss model achieves a DIST-1 score comparable to the ground truth.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.08100](http://arxiv.org/abs/1811.08100)

##### PDF
[http://arxiv.org/pdf/1811.08100](http://arxiv.org/pdf/1811.08100)

