---
layout: post
title: "Deep Filtering: Signal Extraction Using Complex Time-Frequency Filters"
date: 2019-04-17 17:10:10
categories: arXiv_SD
tags: arXiv_SD
author: Wolfgang Mack, Emanu&#xeb;l A. P. Habets
mathjax: true
---

* content
{:toc}

##### Abstract
Signal extraction from a single-channel mixture with additional undesired signals is most commonly performed using time-frequency (TF) masks. Typically, the mask is estimated with a deep neural network (DNN) and element-wise applied to the complex mixture short-time Fourier transform (STFT) representation to perfom extraction. Ideal mask magnitudes are zero for solely undesired signals in a TF bin and infinity for total destructive interference. Usually, masks have an upper bound to provide well-defined DNN outputs at the cost of limited extraction capabilities. We propose to estimate with a DNN a complex TF filter for each mixture TF bin which maps an STFT area in the respective mixture to the desired TF bin to address destructive interference in mixture TF bins. The DNN is optimized by minimizing the error between the extracted and the groundtruth desired signal allowing to train without having to specify ground-truth TF filters but learn filters by error reduction. We compare our approach with complex and real valued TF masks by separating speech from a variety of different sound and noise classes from the Google AudioSet corpus. We also process the mixture STFT with notch filters and zero whole time-frames to demonstrate the reconstruction capabilities of our approach. The proposed method outperformed the baselines especially when notch filters and time-frame zeroing were applied.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08369](http://arxiv.org/abs/1904.08369)

##### PDF
[http://arxiv.org/pdf/1904.08369](http://arxiv.org/pdf/1904.08369)

