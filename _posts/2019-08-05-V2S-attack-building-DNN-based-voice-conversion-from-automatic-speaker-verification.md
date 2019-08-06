---
layout: post
title: "V2S attack: building DNN-based voice conversion from automatic speaker verification"
date: 2019-08-05 03:28:13
categories: arXiv_SD
tags: arXiv_SD Speech_Recognition Recognition
author: Taiki Nakamura, Yuki Saito, Shinnosuke Takamichi, Yusuke Ijima, Hiroshi Saruwatari
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a new voice impersonation attack using voice conversion (VC). Enrolling personal voices for automatic speaker verification (ASV) offers natural and flexible biometric authentication systems. Basically, the ASV systems do not include the users' voice data. However, if the ASV system is unexpectedly exposed and hacked by a malicious attacker, there is a risk that the attacker will use VC techniques to reproduce the enrolled user's voices. We name this the ``verification-to-synthesis (V2S) attack'' and propose VC training with the ASV and pre-trained automatic speech recognition (ASR) models and without the targeted speaker's voice data. The VC model reproduces the targeted speaker's individuality by deceiving the ASV model and restores phonetic property of an input voice by matching phonetic posteriorgrams predicted by the ASR model. The experimental evaluation compares converted voices between the proposed method that does not use the targeted speaker's voice data and the standard VC that uses the data. The experimental results demonstrate that the proposed method performs comparably to the existing VC methods that trained using a very small amount of parallel voice data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.01454](http://arxiv.org/abs/1908.01454)

##### PDF
[http://arxiv.org/pdf/1908.01454](http://arxiv.org/pdf/1908.01454)

