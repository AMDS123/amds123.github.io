---
layout: post
title: "Layer-structured 3D Scene Inference via View Synthesis"
date: 2018-07-26 17:44:09
categories: arXiv_CV
tags: arXiv_CV Inference Quantitative
author: Shubham Tulsiani, Richard Tucker, Noah Snavely
mathjax: true
---

* content
{:toc}

##### Abstract
We present an approach to infer a layer-structured 3D representation of a scene from a single input image. This allows us to infer not only the depth of the visible pixels, but also to capture the texture and depth for content in the scene that is not directly visible. We overcome the challenge posed by the lack of direct supervision by instead leveraging a more naturally available multi-view supervisory signal. Our insight is to use view synthesis as a proxy task: we enforce that our representation (inferred from a single image), when rendered from a novel perspective, matches the true observed image. We present a learning framework that operationalizes this insight using a new, differentiable novel view renderer. We provide qualitative and quantitative validation of our approach in two different settings, and demonstrate that we can learn to capture the hidden aspects of a scene.

##### Abstract (translated by Google)
我们提出了一种从单个输入图像推断场景的层结构3D表示的方法。这使我们不仅可以推断可见像素的深度，还可以捕获场景中不直接可见的内容的纹理和深度。我们通过利用更自然可用的多视图监控信号来克服缺乏直接监督所带来的挑战。我们的见解是使用视图合成作为代理任务：我们强制执行我们的表示（从单个图像推断），当从新颖的角度渲染时，与真实的观察图像匹配。我们提供了一个学习框架，使用一个新的，可区分的新颖视图渲染器来实现这种洞察力。我们在两种不同的环境中对我们的方法进行定性和定量验证，并证明我们可以学习捕捉场景的隐藏方面。

##### URL
[http://arxiv.org/abs/1807.10264](http://arxiv.org/abs/1807.10264)

##### PDF
[http://arxiv.org/pdf/1807.10264](http://arxiv.org/pdf/1807.10264)

