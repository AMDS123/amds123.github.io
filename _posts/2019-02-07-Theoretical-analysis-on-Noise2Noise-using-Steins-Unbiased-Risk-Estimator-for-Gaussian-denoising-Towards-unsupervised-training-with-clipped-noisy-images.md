---
layout: post
title: "Theoretical analysis on Noise2Noise using Stein's Unbiased Risk Estimator for Gaussian denoising: Towards unsupervised training with clipped noisy images"
date: 2019-02-07 02:44:55
categories: arXiv_CV
tags: arXiv_CV
author: Magauiya Zhussip, Shakarim Soltanayev, Se Young Chun
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, Noise2Noise has been proposed for unsupervised training of deep neural networks in image restoration problems including denoising Gaussian noise. However, it does not work well for truncated noise with non-zero mean. Here, we perform theoretical analysis on Noise2Noise for the limited case of Gaussian noise removal using Stein's Unbiased Risk Estimator (SURE). We extend SURE to deal with a pair of noise realizations to directly compare with Noise2Noise. Then, we show that Noise2Noise with Gaussian noise is a special case of our newly extended SURE with a pair of uncorrelated noise realizations. Lastly, we propose a compensation method for clipped Gaussian noise to approximately follow Normal distribution and show how this compensation method can be used for SURE based unsupervised denoiser training. We also show that our theoretical analysis provides insights on how to use Noise2Noise for clipped Gaussian noise.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.02452](http://arxiv.org/abs/1902.02452)

##### PDF
[http://arxiv.org/pdf/1902.02452](http://arxiv.org/pdf/1902.02452)

