---
layout: post
title: 'Compressed Video Action Recognition'
date: 2017-12-05 21:10:17
categories: arXiv_CV
tags: arXiv_CV Image_Caption Action_Recognition Recognition
author: Chao-Yuan Wu, Manzil Zaheer, Hexiang Hu, R. Manmatha, Alexander J. Smola, Philipp Kr&#xe4;henb&#xfc;hl
---

* content
{:toc}

##### Abstract
Training robust deep video representations has proven to be much more challenging than learning deep image representations and consequently hampered tasks like video action recognition. This is in part due to the enormous size of raw video streams, the associated amount of computation required, and the high temporal redundancy. The 'true' and interesting signal is often drowned in too much irrelevant data. Motivated by the fact that the superfluous information can be reduced by up to two orders of magnitude with video compression techniques (like H.264, HEVC, etc.), in this work, we propose to train a deep network directly on the compressed video, devoid of redundancy, rather than the traditional highly redundant RGB stream. </p> <p>This representation has a higher information density and we found the training to be easier. In addition, the signals in a compressed video provide free, albeit noisy, motion information. We propose novel techniques to use them effectively. Our approach is about 4.6 times faster than a state-of-the-art 3D-CNN model, 2.7 times faster than a ResNet-152, and very easy to implement. On the task of action recognition, our approach outperforms all the other methods on the UCF-101, HMDB-51, and Charades dataset.

##### Abstract (translated by Google)
训练强壮的深度视频表示已经被证明比学习深度图像表示更困难，因此阻碍了视频动作识别等任务。这部分是由于原始视频流的巨大尺寸，所需的相关计算量以及高时间冗余。 “真实”和有趣的信号经常被淹没在太多不相关的数据中。由于视频压缩技术（如H.264，HEVC等）可以将多余的信息降低两个数量级，因此在这项工作中，我们建议直接在压缩视频上训练一个深度网络，没有冗余，而不是传统的高冗余RGB流。这种表示具有更高的信息密度，我们发现训练更容易。另外，压缩视频中的信号提供了免费的，尽管是嘈杂的运动信息。我们提出了新的技术来有效地使用它们。我们的方法比现有技术的3D-CNN模型快4.6倍，比ResNet-152快2.7倍，而且非常容易实现。在动作识别的任务上，我们的方法优于UCF-101，HMDB-51和Charades数据集上的所有其他方法。

##### URL
[http://arxiv.org/abs/1712.00636](http://arxiv.org/abs/1712.00636)

