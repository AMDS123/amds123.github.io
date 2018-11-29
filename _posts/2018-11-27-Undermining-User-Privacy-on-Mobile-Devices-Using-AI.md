---
layout: post
title: "Undermining User Privacy on Mobile Devices Using AI"
date: 2018-11-27 19:44:12
categories: arXiv_AI
tags: arXiv_AI CNN Inference Deep_Learning
author: Berk Gulmezoglu, Andreas Zankl, Caner Tol, Saad Islam, Thomas Eisenbarth, Berk Sunar
mathjax: true
---

* content
{:toc}

##### Abstract
Over the past years, literature has shown that attacks exploiting the microarchitecture of modern processors pose a serious threat to the privacy of mobile phone users. This is because applications leave distinct footprints in the processor, which can be used by malware to infer user activities. In this work, we show that these inference attacks are considerably more practical when combined with advanced AI techniques. In particular, we focus on profiling the activity in the last-level cache (LLC) of ARM processors. We employ a simple Prime+Probe based monitoring technique to obtain cache traces, which we classify with Deep Learning methods including Convolutional Neural Networks. We demonstrate our approach on an off-the-shelf Android phone by launching a successful attack from an unprivileged, zeropermission App in well under a minute. The App thereby detects running applications with an accuracy of 98% and reveals opened websites and streaming videos by monitoring the LLC for at most 6 seconds. This is possible, since Deep Learning compensates measurement disturbances stemming from the inherently noisy LLC monitoring and unfavorable cache characteristics such as random line replacement policies. In summary, our results show that thanks to advanced AI techniques, inference attacks are becoming alarmingly easy to implement and execute in practice. This once more calls for countermeasures that confine microarchitectural leakage and protect mobile phone applications, especially those valuing the privacy of their users.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11218](http://arxiv.org/abs/1811.11218)

##### PDF
[http://arxiv.org/pdf/1811.11218](http://arxiv.org/pdf/1811.11218)

