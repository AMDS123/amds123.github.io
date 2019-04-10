---
layout: post
title: "SCSampler: Sampling Salient Clips from Video for Efficient Action Recognition"
date: 2019-04-08 18:28:12
categories: arXiv_CV
tags: arXiv_CV Salient Action_Recognition Classification Prediction Recognition
author: Bruno Korbar, Du Tran, Lorenzo Torresani
mathjax: true
---

* content
{:toc}

##### Abstract
While many action recognition datasets consist of collections of brief, trimmed videos each containing a relevant action, videos in the real-world (e.g., on YouTube) exhibit very different properties: they are often several minutes long, where brief relevant clips are often interleaved with segments of extended duration containing little change. Applying densely an action recognition system to every temporal clip within such videos is prohibitively expensive. Furthermore, as we show in our experiments, this results in suboptimal recognition accuracy as informative predictions from relevant clips are outnumbered by meaningless classification outputs over long uninformative sections of the video. In this paper we introduce a lightweight `clip-sampling' model that can efficiently identify the most salient temporal clips within a long video. We demonstrate that the computational cost of action recognition on untrimmed videos can be dramatically reduced by invoking recognition only on these most salient clips. Furthermore, we show that this yields significant gains in recognition accuracy compared to analysis of all clips or randomly/uniformly selected clips. On Sports1M, our clip sampling scheme elevates the accuracy of an already state-of-the-art action classifier by 7% and reduces by more than 15 times its computational cost.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04289](http://arxiv.org/abs/1904.04289)

##### PDF
[http://arxiv.org/pdf/1904.04289](http://arxiv.org/pdf/1904.04289)

