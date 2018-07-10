---
layout: post
title: "Watch to Edit: Video Retargeting using Gaze"
date: 2018-06-27 16:21:03
categories: arXiv_CV
tags: arXiv_CV Salient Tracking Optimization
author: Kranthi Kumar, Moneish Kumar, Vineet Gandhi, Ramanathan Subramanian
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel approach to optimally retarget videos for varied displays with differing aspect ratios by preserving salient scene content discovered via eye tracking. Our algorithm performs editing with cut, pan and zoom operations by optimizing the path of a cropping window within the original video while seeking to (i) preserve salient regions, and (ii) adhere to the principles of cinematography. Our approach is (a) content agnostic as the same methodology is employed to re-edit a wide-angle video recording or a close-up movie sequence captured with a static or moving camera, and (b) independent of video length and can in principle re-edit an entire movie in one shot. Our algorithm consists of two steps. The first step employs gaze transition cues to detect time stamps where new cuts are to be introduced in the original video via dynamic programming. A subsequent step optimizes the cropping window path (to create pan and zoom effects), while accounting for the original and new cuts. The cropping window path is designed to include maximum gaze information, and is composed of piecewise constant, linear and parabolic segments. It is obtained via L(1) regularized convex optimization which ensures a smooth viewing experience. We test our approach on a wide variety of videos and demonstrate significant improvement over the state-of-the-art, both in terms of computational complexity and qualitative aspects. A study performed with 16 users confirms that our approach results in a superior viewing experience as compared to gaze driven re-editing and letterboxing methods, especially for wide-angle static camera recordings.

##### Abstract (translated by Google)
我们提出了一种新方法，通过保留通过眼动追踪发现的显着场景内容，为具有不同宽高比的各种显示器最佳地重新定位视频。我们的算法通过优化原始视频中裁剪窗口的路径来执行剪切，平移和缩放操作的编辑，同时寻求（i）保留显着区域，以及（ii）遵守电影摄影原理。我们的方法是（a）内容不可知，因为采用相同的方法来重新编辑用静态或移动摄像机拍摄的广角视频录制或特写电影序列，并且（b）独立于视频长度而且可以在原则一次性重新编辑整部电影。我们的算法包括两个步骤。第一步采用注视转换提示来检测时间戳，其中通过动态编程在原始视频中引入新的剪辑。后续步骤优化裁剪窗口路径（以创建平移和缩放效果），同时考虑原始剪切和新剪切。裁剪窗口路径被设计为包括最大注视信息，并且由分段常数，线性和抛物线段组成。它通过L（1）正则化凸优化获得，确保了平滑的观看体验。我们在各种视频上测试我们的方法，并在计算复杂性和定性方面展示了对最新技术的显着改进。与16位用户进行的一项研究证实，与注视驱动的重新编辑和信箱方法相比，我们的方法可带来出色的观看体验，特别是对于广角静态相机录制。

##### URL
[http://arxiv.org/abs/1807.03125](http://arxiv.org/abs/1807.03125)

##### PDF
[http://arxiv.org/pdf/1807.03125](http://arxiv.org/pdf/1807.03125)

