---
layout: post
title: "Stereoscopic Neural Style Transfer"
date: 2018-02-28 18:58:10
categories: arXiv_CV
tags: arXiv_CV Style_Transfer Quantitative
author: Dongdong Chen, Lu Yuan, Jing Liao, Nenghai Yu, Gang Hua
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents the first attempt at stereoscopic neural style transfer, which responds to the emerging demand for 3D movies or AR/VR. We start with a careful examination of applying existing monocular style transfer methods to left and right views of stereoscopic images separately. This reveals that the original disparity consistency cannot be well preserved in the final stylization results, which causes 3D fatigue to the viewers. To address this issue, we incorporate a new disparity loss into the widely adopted style loss function by enforcing the bidirectional disparity constraint in non-occluded regions. For a practical real-time solution, we propose the first feed-forward network by jointly training a stylization sub-network and a disparity sub-network, and integrate them in a feature level middle domain. Our disparity sub-network is also the first end-to-end network for simultaneous bidirectional disparity and occlusion mask estimation. Finally, our network is effectively extended to stereoscopic videos, by considering both temporal coherence and disparity consistency. We will show that the proposed method clearly outperforms the baseline algorithms both quantitatively and qualitatively.

##### Abstract (translated by Google)
本文介绍了立体神经风格转换的第一次尝试，它响应了对3D电影或AR / VR的新兴需求。我们首先仔细检查将现有的单眼式传输方法分别应用于立体图像的左视图和右视图。这表明原始视差一致性在最终的程式化结果中不能很好地保留，这导致观众的3D疲劳。为了解决这个问题，我们通过在非遮挡区域实施双向视差约束，将新的视差损失纳入广泛采用的样式损失函数中。对于一个实际的实时解决方案，我们通过联合训练一个程式化子网络和一个视差子网络来提出第一个前馈网络，并将它们集成到一个特征级中间域中。我们的视差子网络也是第一个同时进行双向视差和遮挡遮罩估计的端到端网络。最后，我们的网络通过考虑时间一致性和视差一致性而有效地扩展到立体视频。我们将证明所提出的方法在数量和质量上都明显优于基线算法。

##### URL
[http://arxiv.org/abs/1802.10591](http://arxiv.org/abs/1802.10591)

##### PDF
[http://arxiv.org/pdf/1802.10591](http://arxiv.org/pdf/1802.10591)

