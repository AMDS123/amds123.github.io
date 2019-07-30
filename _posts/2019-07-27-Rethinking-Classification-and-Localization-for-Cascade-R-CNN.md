---
layout: post
title: "Rethinking Classification and Localization for Cascade R-CNN"
date: 2019-07-27 13:57:05
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Detection
author: Ang Li, Xue Yang, Chongyang Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
We extend the state-of-the-art Cascade R-CNN with a simple feature sharing mechanism. Our approach focuses on the performance increases on high IoU but decreases on low IoU thresholds--a key problem this detector suffers from. Feature sharing is extremely helpful, our results show that given this mechanism embedded into all stages, we can easily narrow the gap between the last stage and preceding stages on low IoU thresholds without resorting to the commonly used testing ensemble but the network itself. We also observe obvious improvements on all IoU thresholds benefited from feature sharing, and the resulting cascade structure can easily match or exceed its counterparts, only with negligible extra parameters introduced. To push the envelope, we demonstrate 43.2 AP on COCO object detection without any bells and whistles including testing ensemble, surpassing previous Cascade R-CNN by a large margin. Our framework is easy to implement and we hope it can serve as a general and strong baseline for future research.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.11914](http://arxiv.org/abs/1907.11914)

##### PDF
[http://arxiv.org/pdf/1907.11914](http://arxiv.org/pdf/1907.11914)

