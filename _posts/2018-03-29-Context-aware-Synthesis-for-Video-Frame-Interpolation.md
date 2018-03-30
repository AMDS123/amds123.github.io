---
layout: post
title: "Context-aware Synthesis for Video Frame Interpolation"
date: 2018-03-29 08:56:14
categories: arXiv_CV
tags: arXiv_CV CNN
author: Simon Niklaus, Feng Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Video frame interpolation algorithms typically estimate optical flow or its variations and then use it to guide the synthesis of an intermediate frame between two consecutive original frames. To handle challenges like occlusion, bidirectional flow between the two input frames is often estimated and used to warp and blend the input frames. However, how to effectively blend the two warped frames still remains a challenging problem. This paper presents a context-aware synthesis approach that warps not only the input frames but also their pixel-wise contextual information and uses them to interpolate a high-quality intermediate frame. Specifically, we first use a pre-trained neural network to extract per-pixel contextual information for input frames. We then employ a state-of-the-art optical flow algorithm to estimate bidirectional flow between them and pre-warp both input frames and their context maps. Finally, unlike common approaches that blend the pre-warped frames, our method feeds them and their context maps to a video frame synthesis neural network to produce the interpolated frame in a context-aware fashion. Our neural network is fully convolutional and is trained end to end. Our experiments show that our method can handle challenging scenarios such as occlusion and large motion and outperforms representative state-of-the-art approaches.

##### Abstract (translated by Google)
视频帧插值算法通常估计光流或其变化，然后用它来指导两个连续原始帧之间的中间帧的合成。为了处理诸如遮挡之类的挑战，经常估计两个输入帧之间的双向流，并用它来扭曲和混合输入帧。但是，如何有效地混合两个变形帧仍然是一个具有挑战性的问题。本文提出了一种上下文感知合成方法，该方法不仅剔除输入帧，而且还剔除像素方面的上下文信息，并使用它们插入高质量的中间帧。具体来说，我们首先使用预先训练的神经网络为输入帧提取每个像素的上下文信息。然后，我们采用先进的光流算法来估计它们之间的双向流动，并预先调整输入帧及其上下文映射。最后，与混合预扭曲帧的常见方法不同，我们的方法将它们和它们的上下文映射馈送到视频帧合成神经网络，以便以情境感知的方式产生内插帧。我们的神经网络是完全卷积的并且是端对端训练的。我们的实验表明，我们的方法可以处理诸如遮挡和大动作等具有挑战性的场景，并且超越了具有代表性的最先进方法。

##### URL
[http://arxiv.org/abs/1803.10967](http://arxiv.org/abs/1803.10967)

##### PDF
[http://arxiv.org/pdf/1803.10967](http://arxiv.org/pdf/1803.10967)

