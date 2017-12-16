---
layout: post
title: "GazeDirector: Fully Articulated Eye Gaze Redirection in Video"
date: 2017-04-27 22:23:53
categories: arXiv_CV
tags: arXiv_CV Quantitative
author: Erroll Wood, Tadas Baltrusaitis, Louis-Philippe Morency, Peter Robinson, Andreas Bulling
mathjax: true
---

* content
{:toc}

##### Abstract
We present GazeDirector, a new approach for eye gaze redirection that uses model-fitting. Our method first tracks the eyes by fitting a multi-part eye region model to video frames using analysis-by-synthesis, thereby recovering eye region shape, texture, pose, and gaze simultaneously. It then redirects gaze by 1) warping the eyelids from the original image using a model-derived flow field, and 2) rendering and compositing synthesized 3D eyeballs onto the output image in a photorealistic manner. GazeDirector allows us to change where people are looking without person-specific training data, and with full articulation, i.e. we can precisely specify new gaze directions in 3D. Quantitatively, we evaluate both model-fitting and gaze synthesis, with experiments for gaze estimation and redirection on the Columbia gaze dataset. Qualitatively, we compare GazeDirector against recent work on gaze redirection, showing better results especially for large redirection angles. Finally, we demonstrate gaze redirection on YouTube videos by introducing new 3D gaze targets and by manipulating visual behavior.

##### Abstract (translated by Google)
我们介绍GazeDirector，一种使用模型拟合的眼睛注视重定向的新方法。我们的方法首先通过使用综合分析将多部分眼睛区域模型拟合到视频帧来追踪眼睛，由此同时恢复眼睛区域形状，纹理，姿势和注视。然后通过1）使用模型衍生的流场使原始图像的眼睑变形，2）以照片真实的方式将合成的3D眼球渲染和合成到输出图像上，从而重新引导凝视。 GazeDirector使我们能够改变人们在不需要特定人员的训练数据的情况下，在完全清晰的情况下，也就是说，我们可以精确地指定3D的新的凝视方向。在数量上，我们评估模型拟合和凝视合成，在哥伦比亚凝视数据集上进行凝视估计和重定向的实验。定性地，我们将GazeDirector与最近的凝视重定向工作进行了比较，显示出更好的结果，特别是对于大的重定向角度。最后，我们通过引入新的3D凝视目标和操纵视觉行为来展示YouTube视频上的注视重定向。

##### URL
[https://arxiv.org/abs/1704.08763](https://arxiv.org/abs/1704.08763)

##### PDF
[https://arxiv.org/pdf/1704.08763](https://arxiv.org/pdf/1704.08763)

