---
layout: post
title: "Sparse Adversarial Perturbations for Videos"
date: 2018-03-07 06:28:43
categories: arXiv_CV
tags: arXiv_CV Adversarial Sparse Action_Recognition Optimization RNN Recognition
author: Xingxing Wei, Jun Zhu, Hang Su
mathjax: true
---

* content
{:toc}

##### Abstract
Although adversarial samples of deep neural networks (DNNs) have been intensively studied on static images, their extensions in videos are never explored. Compared with images, attacking a video needs to consider not only spatial cues but also temporal cues. Moreover, to improve the imperceptibility as well as reduce the computation cost, perturbations should be added on as fewer frames as possible, i.e., adversarial perturbations are temporally sparse. This further motivates the propagation of perturbations, which denotes that perturbations added on the current frame can transfer to the next frames via their temporal interactions. Thus, no (or few) extra perturbations are needed for these frames to misclassify them. To this end, we propose an l2,1-norm based optimization algorithm to compute the sparse adversarial perturbations for videos. We choose the action recognition as the targeted task, and networks with a CNN+RNN architecture as threat models to verify our method. Thanks to the propagation, we can compute perturbations on a shortened version video, and then adapt them to the long version video to fool DNNs. Experimental results on the UCF101 dataset demonstrate that even only one frame in a video is perturbed, the fooling rate can still reach 59.7%.

##### Abstract (translated by Google)
尽管深度神经网络（DNN）的敌对样本已经在静态图像上进行了深入研究，但它们在视频中的扩展从未被探索过。与图像相比，攻击视频不仅需要考虑空间线索，还需要考虑时间线索。此外，为了提高不可感知性并降低计算成本，应该尽可能少地增加扰动，即对抗性扰动在时间上是稀疏的。这进一步激发了扰动的传播，这表示在当前帧上添加的扰动可以通过它们的时间相互作用转移到下一帧。因此，这些帧不需要（或很少）额外的扰动来对它们进行错误分类。为此，我们提出了基于l2,1范数的优化算法来计算视频的稀疏对抗扰动。我们选择动作识别作为目标任务，并与CNN + RNN架构网络作为威胁模型来验证我们的方法。由于传播，我们可以计算缩短版本视频的扰动，然后将它们调整为长版视频来欺骗DNN。 UCF101数据集上的实验结果表明，即使只有一帧视频被扰乱，愚弄率仍然可以达到59.7％。

##### URL
[http://arxiv.org/abs/1803.02536](http://arxiv.org/abs/1803.02536)

##### PDF
[http://arxiv.org/pdf/1803.02536](http://arxiv.org/pdf/1803.02536)

