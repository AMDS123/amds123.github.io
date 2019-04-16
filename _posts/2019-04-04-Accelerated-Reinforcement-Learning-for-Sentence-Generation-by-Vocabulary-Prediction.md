---
layout: post
title: "Accelerated Reinforcement Learning for Sentence Generation by Vocabulary Prediction"
date: 2019-04-04 20:51:38
categories: arXiv_CV
tags: arXiv_CV Image_Caption Reinforcement_Learning Caption Prediction
author: Kazuma Hashimoto, Yoshimasa Tsuruoka
mathjax: true
---

* content
{:toc}

##### Abstract
A major obstacle in reinforcement learning-based sentence generation is the large action space whose size is equal to the vocabulary size of the target-side language. To improve the efficiency of reinforcement learning, we present a novel approach for reducing the action space based on dynamic vocabulary prediction. Our method first predicts a fixed-size small vocabulary for each input to generate its target sentence. The input-specific vocabularies are then used at supervised and reinforcement learning steps, and also at test time. In our experiments on six machine translation and two image captioning datasets, our method achieves faster reinforcement learning ($\sim$2.7x faster) with less GPU memory ($\sim$2.3x less) than the full-vocabulary counterpart. The reinforcement learning with our method consistently leads to significant improvement of BLEU scores, and the scores are equal to or better than those of baselines using the full vocabularies, with faster decoding time ($\sim$3x faster) on CPUs.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1809.01694](https://arxiv.org/abs/1809.01694)

##### PDF
[https://arxiv.org/pdf/1809.01694](https://arxiv.org/pdf/1809.01694)

