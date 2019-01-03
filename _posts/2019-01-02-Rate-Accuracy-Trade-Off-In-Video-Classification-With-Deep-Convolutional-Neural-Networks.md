---
layout: post
title: "Rate-Accuracy Trade-Off In Video Classification With Deep Convolutional Neural Networks"
date: 2019-01-02 13:08:19
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN Video_Classification Classification Recognition
author: Mohammad Jubran, Alhabib Abbas, Aaron Chadha, Yiannis Andreopoulos
mathjax: true
---

* content
{:toc}

##### Abstract
Advanced video classification systems decode video frames to derive the necessary texture and motion representations for ingestion and analysis by spatio-temporal deep convolutional neural networks (CNNs). However, when considering visual Internet-of-Things applications, surveillance systems and semantic crawlers of large video repositories, the video capture and the CNN-based semantic analysis parts do not tend to be co-located. This necessitates the transport of compressed video over networks and incurs significant overhead in bandwidth and energy consumption, thereby significantly undermining the deployment potential of such systems. In this paper, we investigate the trade-off between the encoding bitrate and the achievable accuracy of CNN-based video classification models that directly ingest AVC/H.264 and HEVC encoded videos. Instead of retaining entire compressed video bitstreams and applying complex optical flow calculations prior to CNN processing, we only retain motion vector and select texture information at significantly-reduced bitrates and apply no additional processing prior to CNN ingestion. Based on three CNN architectures and two action recognition datasets, we achieve 11%-94% saving in bitrate with marginal effect on classification accuracy. A model-based selection between multiple CNNs increases these savings further, to the point where, if up to 7% loss of accuracy can be tolerated, video classification can take place with as little as 3 kbps for the transport of the required compressed video information to the system implementing the CNN models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.03964](http://arxiv.org/abs/1810.03964)

##### PDF
[http://arxiv.org/pdf/1810.03964](http://arxiv.org/pdf/1810.03964)

