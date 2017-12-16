---
layout: post
title: "Guidefill: GPU Accelerated, Artist Guided Geometric Inpainting for 3D Conversion"
date: 2017-07-31 19:40:09
categories: arXiv_CV
tags: arXiv_CV Face Tracking
author: L. Robert Hocking, Russell MacKenzie, Carola-Bibiane Schoenlieb
mathjax: true
---

* content
{:toc}

##### Abstract
The conversion of traditional film into stereo 3D has become an important problem in the past decade. One of the main bottlenecks is a disocclusion step, which in commercial 3D conversion is usually done by teams of artists armed with a toolbox of inpainting algorithms. A current difficulty in this is that most available algorithms are either too slow for interactive use, or provide no intuitive means for users to tweak the output. In this paper we present a new fast inpainting algorithm based on transporting along automatically detected splines, which the user may edit. Our algorithm is implemented on the GPU and fills the inpainting domain in successive shells that adapt their shape on the fly. In order to allocate GPU resources as efficiently as possible, we propose a parallel algorithm to track the inpainting interface as it evolves, ensuring that no resources are wasted on pixels that are not currently being worked on. Theoretical analysis of the time and processor complexiy of our algorithm without and with tracking (as well as numerous numerical experiments) demonstrate the merits of the latter. Our transport mechanism is similar to the one used in coherence transport, but improves upon it by corrected a "kinking" phenomena whereby extrapolated isophotes may bend at the boundary of the inpainting domain. Theoretical results explaining this phenomena and its resolution are presented. Although our method ignores texture, in many cases this is not a problem due to the thin inpainting domains in 3D conversion. Experimental results show that our method can achieve a visual quality that is competitive with the state-of-the-art while maintaining interactive speeds and providing the user with an intuitive interface to tweak the results.

##### Abstract (translated by Google)
传统电影转换成立体3D已成为过去十年来的一个重要问题。其中一个主要的瓶颈就是一个不连贯的步骤，在商业化的3D转换中，通常是由具有修改算法工具箱的艺术家团队完成的。当前的困难在于，大多数可用的算法对于交互式使用来说太慢，或者没有为用户调整输出提供直观的手段。在本文中，我们提出了一种新的快速修复算法，基于自动检测样条的传输，用户可以编辑。我们的算法在GPU上实现，并在连续的壳体中填充修改域，以适应其形状。为了尽可能高效地分配GPU资源，我们提出了一种并行算法来跟踪正在发展的修复界面，确保没有资源浪费在当前没有处理的像素上。我们的算法的时间和处理器复杂性的理论分析没有和跟踪（以及许多数值实验）证明了后者的优点。我们的运输机制类似于在一致性运输中使用的运输机制，但是通过纠正一个“扭曲”现象，外推的等照度可能在修补域的边界弯曲。介绍了解释这一现象及其解决方法的理论结果。虽然我们的方法忽略纹理，但在许多情况下，这不是由于3D转换中的细小的修复域造成的问题。实验结果表明，我们的方法可以实现与最新技术相竞争的视觉质量，同时保持交互速度，并为用户提供直观的界面来调整结果。

##### URL
[https://arxiv.org/abs/1611.05319](https://arxiv.org/abs/1611.05319)

##### PDF
[https://arxiv.org/pdf/1611.05319](https://arxiv.org/pdf/1611.05319)

