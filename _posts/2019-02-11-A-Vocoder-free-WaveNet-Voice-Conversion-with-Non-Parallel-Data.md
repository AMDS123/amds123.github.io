---
layout: post
title: "A Vocoder-free WaveNet Voice Conversion with Non-Parallel Data"
date: 2019-02-11 02:36:41
categories: arXiv_SD
tags: arXiv_SD
author: Xiaohai Tian, Eng Siong Chng, Haizhou Li
mathjax: true
---

* content
{:toc}

##### Abstract
In a typical voice conversion system, vocoder is commonly used for speech-to-features analysis and features-to-speech synthesis. However, vocoder can be a source of speech quality degradation. This paper presents a vocoder-free voice conversion approach using WaveNet for non-parallel training data. Instead of dealing with the intermediate features, the proposed approach utilizes the WaveNet to map the Phonetic PosteriorGrams (PPGs) to the waveform samples directly. In this way, we avoid the estimation errors caused by vocoder and feature conversion. Additionally, as PPG is assumed to be speaker independent, the proposed method also reduces the feature mismatch problem in WaveNet vocoder based approaches. Experimental results conducted on the CMU-ARCTIC database show that the proposed approach significantly outperforms the baseline approaches in terms of speech quality.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.03705](http://arxiv.org/abs/1902.03705)

##### PDF
[http://arxiv.org/pdf/1902.03705](http://arxiv.org/pdf/1902.03705)

