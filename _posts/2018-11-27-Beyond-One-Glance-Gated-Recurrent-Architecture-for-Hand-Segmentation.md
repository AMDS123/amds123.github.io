---
layout: post
title: "Beyond One Glance: Gated Recurrent Architecture for Hand Segmentation"
date: 2018-11-27 11:16:41
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Wei Wang, Kaicheng Yu, Joachim Hugonot, Pascal Fua, Mathieu Salzmann
mathjax: true
---

* content
{:toc}

##### Abstract
As mixed reality is gaining increased momentum, the development of effective and efficient solutions to egocentric hand segmentation is becoming critical. Traditional segmentation techniques typically follow a one-shot approach, where the image is passed forward only once through a model that produces a segmentation mask. This strategy, however, does not reflect the perception of humans, who continuously refine their representation of the world. In this paper, we therefore introduce a novel gated recurrent architecture. It goes beyond both iteratively passing the predicted segmentation mask through the network and adding a standard recurrent unit to it. Instead, it incorporates multiple encoder-decoder layers of the segmentation network, so as to keep track of its internal state in the refinement process. As evidenced by our results on standard hand segmentation benchmarks and on our own dataset, our approach outperforms these other, simpler recurrent segmentation techniques, as well as the state-of-the-art hand segmentation one. Furthermore, we demonstrate the generality of our approach by applying it to road segmentation, where it also outperforms other baseline methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.10914](http://arxiv.org/abs/1811.10914)

##### PDF
[http://arxiv.org/pdf/1811.10914](http://arxiv.org/pdf/1811.10914)

