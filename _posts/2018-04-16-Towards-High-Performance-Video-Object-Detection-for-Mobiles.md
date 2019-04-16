---
layout: post
title: "Towards High Performance Video Object Detection for Mobiles"
date: 2018-04-16 17:59:36
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Detection
author: Xizhou Zhu, Jifeng Dai, Xingchi Zhu, Yichen Wei, Lu Yuan
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the recent success of video object detection on Desktop GPUs, its architecture is still far too heavy for mobiles. It is also unclear whether the key principles of sparse feature propagation and multi-frame feature aggregation apply at very limited computational resources. In this paper, we present a light weight network architecture for video object detection on mobiles. Light weight image object detector is applied on sparse key frames. A very small network, Light Flow, is designed for establishing correspondence across frames. A flow-guided GRU module is designed to effectively aggregate features on key frames. For non-key frames, sparse feature propagation is performed. The whole network can be trained end-to-end. The proposed system achieves 60.2% mAP score at speed of 25.6 fps on mobiles (e.g., HuaWei Mate 8).

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1804.05830](https://arxiv.org/abs/1804.05830)

##### PDF
[https://arxiv.org/pdf/1804.05830](https://arxiv.org/pdf/1804.05830)

