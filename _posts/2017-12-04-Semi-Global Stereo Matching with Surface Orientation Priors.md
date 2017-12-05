---
layout: post
title:  'Semi-Global Stereo Matching with Surface Orientation Priors'
date:   2017-12-05 18:44:29
categories: CV
tags: CV
author: Daniel Scharstein, Tatsunori Taniai, Sudipta N. Sinha
---

* content
{:toc}

##### Abstract
Semi-Global Matching (SGM) is a widely-used efficient stereo matching technique. It works well for textured scenes, but fails on untextured slanted surfaces due to its fronto-parallel smoothness assumption. To remedy this problem, we propose a simple extension, termed SGM-P, to utilize precomputed surface orientation priors. Such priors favor different surface slants in different 2D image regions or 3D scene regions and can be derived in various ways. In this paper we evaluate plane orientation priors derived from stereo matching at a coarser resolution and show that such priors can yield significant performance gains for difficult weakly-textured scenes. We also explore surface normal priors derived from Manhattan-world assumptions, and we analyze the potential performance gains using oracle priors derived from ground-truth data. SGM-P only adds a minor computational overhead to SGM and is an attractive alternative to more complex methods employing higher-order smoothness terms.

##### Abstract (translated by Google)
半全球匹配（SGM）是一种广泛使用的高效立体匹配技术。它适用于有纹理的场景，但由于其平行平滑假设，在无纹理的倾斜表面上失败。为了解决这个问题，我们提出了一个简单的扩展，称为SGM-P，以利用预先计算的表面定向先验。这样的先验在不同的2D图像区域或3D场景区域中倾向于不同的表面倾斜，并且可以以各种方式导出。在本文中，我们评估了从较粗糙分辨率的立体匹配导出的平面方向的先验，并显示出这样的先验可以在困难的弱纹理场景中产生显着的性能增益。我们还探索源自曼哈顿世界假设的表面正态前体，并且我们使用从地面实况数据得到的先验知识来分析潜在的性能增益。 SGM-P仅为SGM增加了一个小的计算开销，并且是采用更高阶平滑项的更复杂方法的有吸引力的替代方案。

