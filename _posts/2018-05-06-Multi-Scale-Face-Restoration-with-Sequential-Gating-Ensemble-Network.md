---
layout: post
title: "Multi-Scale Face Restoration with Sequential Gating Ensemble Network"
date: 2018-05-06 07:38:42
categories: arXiv_CV
tags: arXiv_CV Adversarial Face Recognition Face_Recognition
author: Jianxin Lin, Tiankuang Zhou, Zhibo Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Restoring face images from distortions is important in face recognition applications and is challenged by multiple scale issues, which is still not well-solved in research area. In this paper, we present a Sequential Gating Ensemble Network (SGEN) for multi-scale face restoration issue. We first employ the principle of ensemble learning into SGEN architecture design to reinforce predictive performance of the network. The SGEN aggregates multi-level base-encoders and base-decoders into the network, which enables the network to contain multiple scales of receptive field. Instead of combining these base-en/decoders directly with non-sequential operations, the SGEN takes base-en/decoders from different levels as sequential data. Specifically, the SGEN learns to sequentially extract high level information from base-encoders in bottom-up manner and restore low level information from base-decoders in top-down manner. Besides, we propose to realize bottom-up and top-down information combination and selection with Sequential Gating Unit (SGU). The SGU sequentially takes two inputs from different levels and decides the output based on one active input. Experiment results demonstrate that our SGEN is more effective at multi-scale human face restoration with more image details and less noise than state-of-the-art image restoration models. By using adversarial training, SGEN also produces more visually preferred results than other models through subjective evaluation.

##### Abstract (translated by Google)
从人脸识别应用中恢复人脸图像的失真是很重要的，并且受到多个尺度问题的挑战，这在研究领域仍然没有得到很好的解决。在本文中，我们提出了一个用于多尺度人脸恢复问题的顺序门控集成网络（SGEN）。我们首先将集成学习原理应用于SGEN架构设计中，以加强网络的预测性能。 SGEN将多级基本编码器和基本解码器集成到网络中，使网络能够包含多种比例的接受域。与其将这些base-en / decoders直接与非连续操作相结合，SGEN将来自不同级别的base-en / decoders作为连续数据。具体而言，SGEN学习以自下而上的方式从基本编码器顺序地提取高级信息，并以自上而下的方式从基本解码器恢复低级信息。此外，我们还提出使用顺序门控单元（SGU）实现自下而上和自上而下的信息组合和选择。 SGU依次从不同级别接收两路输入，并根据一路有效输入决定输出。实验结果表明，我们的SGEN在多尺度人脸恢复方面更为有效，图像细节更多，噪声更低，比现有技术的图像恢复模型更有效。通过使用对抗训练，SGEN还通过主观评估比其他模型产生更多视觉上优先的结果。

##### URL
[http://arxiv.org/abs/1805.02164](http://arxiv.org/abs/1805.02164)

##### PDF
[http://arxiv.org/pdf/1805.02164](http://arxiv.org/pdf/1805.02164)

