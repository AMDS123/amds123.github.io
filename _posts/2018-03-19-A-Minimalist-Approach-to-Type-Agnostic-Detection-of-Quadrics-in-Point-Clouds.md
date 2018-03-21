---
layout: post
title: "A Minimalist Approach to Type-Agnostic Detection of Quadrics in Point Clouds"
date: 2018-03-19 23:01:01
categories: arXiv_CV
tags: arXiv_CV Segmentation Detection
author: Tolga Birdal, Benjamin Busam, Nassir Navab, Slobodan Ilic, Peter Sturm
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a segmentation-free, automatic and efficient procedure to detect general geometric quadric forms in point clouds, where clutter and occlusions are inevitable. Our everyday world is dominated by man-made objects which are designed using 3D primitives (such as planes, cones, spheres, cylinders, etc.). These objects are also omnipresent in industrial environments. This gives rise to the possibility of abstracting 3D scenes through primitives, thereby positions these geometric forms as an integral part of perception and high level 3D scene understanding. 
 As opposed to state-of-the-art, where a tailored algorithm treats each primitive type separately, we propose to encapsulate all types in a single robust detection procedure. At the center of our approach lies a closed form 3D quadric fit, operating in both primal &amp; dual spaces and requiring as low as 4 oriented-points. Around this fit, we design a novel, local null-space voting strategy to reduce the 4-point case to 3. Voting is coupled with the famous RANSAC and makes our algorithm orders of magnitude faster than its conventional counterparts. This is the first method capable of performing a generic cross-type multi-object primitive detection in difficult scenes. Results on synthetic and real datasets support the validity of our method.

##### Abstract (translated by Google)
本文提出了一种无需分割，自动且高效的程序来检测点云中的一般几何二次曲面，其中杂波和遮挡是不可避免的。我们的日常世界由人造物体支配，这些人造物体是使用3D基元（例如飞机，锥体，球体，圆柱体等）设计的。这些对象在工业环境中也是无处不在的。这导致通过图元抽取3D场景的可能性，从而将这些几何形状定位为感知和高级3D场景理解的组成部分。
 与最先进的技术相比，定制算法分别处理每种原始类型，我们建议将所有类型封装在一个健壮的检测程序中。我们的方法的核心是一个封闭的三维二次拟合，双空间并且需要低至4个定向点。围绕这种拟合，我们设计了一种新颖的局部零空间投票策略，以将4分的情况减少到3.投票与着名的RANSAC相结合，使得我们的算法的数量级比传统的算法快几个数量级。这是第一种能够在困难场景中执行通用交叉类型多对象基元检测的方法。合成和真实数据集的结果支持我们方法的有效性。

##### URL
[http://arxiv.org/abs/1803.07191](http://arxiv.org/abs/1803.07191)

##### PDF
[http://arxiv.org/pdf/1803.07191](http://arxiv.org/pdf/1803.07191)

