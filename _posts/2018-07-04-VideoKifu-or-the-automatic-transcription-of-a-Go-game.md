---
layout: post
title: "VideoKifu, or the automatic transcription of a Go game"
date: 2018-07-04 13:52:10
categories: arXiv_CV
tags: arXiv_CV
author: Mario Corsolini, Andrea Carta
mathjax: true
---

* content
{:toc}

##### Abstract
In two previous papers [<a href="https://export.arxiv.org/abs/1508.03269">arXiv:1508.03269</a>, <a href="https://export.arxiv.org/abs/1701.05419">arXiv:1701.05419</a>] we described the techniques we employed for reconstructing the whole move sequence of a Go game. That task was at first accomplished by means of a series of photographs, manually shot, as explained during the scientific conference held within the LIX European Go Congress (Liberec, CZ). The photographs were subsequently replaced by a possibly unattended video live stream (provided by webcams, videocameras, smartphones and so on) or, were the live stream not available, by means of a pre-recorded video of the game itself, on condition that the goban and the stones were clearly visible more often than not. As we hinted in the latter paper, in the last two years we have improved both the algorithms employed for reconstructing the grid and detecting the stones, making extensive usage of the multicore capabilities offered by modern CPUs. Those capabilities prompted us to develop some asynchronous routines, capable of double-checking the position of the grid and the number and colour of any stone previously detected, in order to get rid of minor errors possibly occurred during the main analysis, and that may pass undetected especially in the course of an unattended live streaming. Those routines will be described in details, as they address some problems that are of general interest when reconstructing the move sequence, for example what to do when large movements of the whole goban occur (deliberate or not) and how to deal with captures of dead stones $-$ that could be wrongly detected and recorded as "fresh" moves if not promptly removed.

##### Abstract (translated by Google)
在之前的两篇论文[<a href="https://export.arxiv.org/abs/1508.03269"> arXiv：1508.03269 </a>，<a href =“https://export.arxiv.org/abs/ 1701.05419“> arXiv：1701.05419 </a>]我们描述了我们用于重建Go游戏的整个移动序列的技术。这项任务最初是通过手动拍摄的一系列照片完成的，正如在LIX欧洲围棋大会（利贝雷茨，CZ）举行的科学会议期间所解释的那样。这些照片后来被一个可能无人看管的视频直播流（由网络摄像头，摄像机，智能手机等提供）取代，或者是通过预先录制的游戏本身视频而无法获得直播，条件是： goban和石头经常清晰可见。正如我们在后一篇论文中暗示的那样，在过去两年中，我们改进了用于重建网格和检测石头的算法，广泛使用了现代CPU提供的多核功能。这些功能促使我们开发了一些异步程序，能够仔细检查网格的位置以及先前检测到的任何石头的数量和颜色，以便摆脱主要分析期间可能发生的微小错误，并且可能通过特别是在无人值守的直播流媒体中未被发现。这些例程将被详细描述，因为它们解决了在重建移动序列时一般感兴趣的一些问题，例如当整个goban的大幅度移动发生时（故意与否）以及如何处理死亡的捕获时该怎么做如果没有及时删除，可能会错误地检测到并记录为“新鲜”动作的$  -  $。

##### URL
[http://arxiv.org/abs/1807.01577](http://arxiv.org/abs/1807.01577)

##### PDF
[http://arxiv.org/pdf/1807.01577](http://arxiv.org/pdf/1807.01577)

