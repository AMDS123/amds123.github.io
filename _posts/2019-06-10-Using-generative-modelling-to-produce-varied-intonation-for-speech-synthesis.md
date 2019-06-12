---
layout: post
title: "Using generative modelling to produce varied intonation for speech synthesis"
date: 2019-06-10 19:05:03
categories: arXiv_CL
tags: arXiv_CL
author: Zack Hodari, Oliver Watts, Simon King
mathjax: true
---

* content
{:toc}

##### Abstract
Unlike human speakers, typical text-to-speech (TTS) systems are unable to produce multiple distinct renditions of a given sentence. This has previously been addressed by adding explicit external control. In contrast, generative models are able to capture a distribution over multiple renditions and thus produce varied renditions using sampling. Typical neural TTS models learn the average of the data because they minimise mean squared error. In the context of prosody, taking the average produces flatter, more boring speech: an "average prosody". A generative model that can synthesise multiple prosodies will, by design, not model average prosody. We use variational autoencoders (VAE) which explicitly place the most "average" data close to the mean of the Gaussian prior. We propose that by moving towards the tails of the prior distribution, the model will transition towards generating more idiosyncratic, varied renditions. Focusing here on intonation, we investigate the trade-off between naturalness and intonation variation and find that typical acoustic models can either be natural, or varied, but not both. However, sampling from the tails of the VAE prior produces much more varied intonation than the traditional approaches, whilst maintaining the same level of naturalness.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.04233](http://arxiv.org/abs/1906.04233)

##### PDF
[http://arxiv.org/pdf/1906.04233](http://arxiv.org/pdf/1906.04233)

