---
layout: post
title: "SDR - half-baked or well done?"
date: 2018-11-06 17:20:05
categories: arXiv_SD
tags: arXiv_SD
author: Jonathan Le Roux, Scott Wisdom, Hakan Erdogan, John R. Hershey
mathjax: true
---

* content
{:toc}

##### Abstract
In speech enhancement and source separation, signal-to-noise ratio is a ubiquitous objective measure of denoising/separation quality. A decade ago, the BSS_eval toolkit was developed to give researchers worldwide a way to evaluate the quality of their algorithms in a simple, fair, and hopefully insightful way: it attempted to account for channel variations, and to not only evaluate the total distortion in the estimated signal but also split it in terms of various factors such as remaining interference, newly added artifacts, and channel errors. In recent years, hundreds of papers have been relying on this toolkit to evaluate their proposed methods and compare them to previous works, often arguing that differences on the order of 0.1 dB proved the effectiveness of a method over others. We argue here that the signal-to-distortion ratio (SDR) implemented in the BSS_eval toolkit has generally been improperly used and abused, especially in the case of single-channel separation, resulting in misleading results. We propose to use a slightly modified definition, resulting in a simpler, more robust measure, called scale-invariant SDR (SI-SDR). We present various examples of critical failure of the original SDR that SI-SDR overcomes.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.02508](http://arxiv.org/abs/1811.02508)

##### PDF
[http://arxiv.org/pdf/1811.02508](http://arxiv.org/pdf/1811.02508)

