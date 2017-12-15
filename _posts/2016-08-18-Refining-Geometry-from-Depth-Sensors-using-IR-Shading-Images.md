---
layout: post
title: "Refining Geometry from Depth Sensors using IR Shading Images"
date: 2016-08-18 08:19:43
categories: arXiv_CV
tags: arXiv_CV Face
author: Gyeongmin Choe, Jaesik Park, Yu-Wing Tai, In So Kweon
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a method to refine geometry of 3D meshes from a consumer level depth camera, e.g. Kinect, by exploiting shading cues captured from an infrared (IR) camera. A major benefit to using an IR camera instead of an RGB camera is that the IR images captured are narrow band images that filter out most undesired ambient light, which makes our system robust against natural indoor illumination. Moreover, for many natural objects with colorful textures in the visible spectrum, the subjects appear to have a uniform albedo in the IR spectrum. Based on our analyses on the IR projector light of the Kinect, we define a near light source IR shading model that describes the captured intensity as a function of surface normals, albedo, lighting direction, and distance between light source and surface points. To resolve the ambiguity in our model between the normals and distances, we utilize an initial 3D mesh from the Kinect fusion and multi-view information to reliably estimate surface details that were not captured and reconstructed by the Kinect fusion. Our approach directly operates on the mesh model for geometry refinement. We ran experiments on our algorithm for geometries captured by both the Kinect I and Kinect II, as the depth acquisition in Kinect I is based on a structured-light technique and that of the Kinect II is based on a time-of-flight (ToF) technology. The effectiveness of our approach is demonstrated through several challenging real-world examples. We have also performed a user study to evaluate the quality of the mesh models before and after our refinements.

##### Abstract (translated by Google)
我们提出了一种从消费级别的深度相机中改进3D网格几何的方法， Kinect，通过利用从红外（IR）摄像头捕获的阴影线索。使用红外摄像机代替RGB摄像机的一个主要优点是捕获的红外图像是窄带图像，可以过滤掉大部分不需要的环境光，这使得我们的系统对自然室内照明具有很强的鲁棒性。而且，对于许多在可见光谱中具有彩色纹理的自然物体，在IR光谱中，被摄体似乎具有均匀的反照率。基于我们对Kinect的红外投影灯的分析，我们定义了一个近光源IR阴影模型，该模型将捕获的强度描述为表面法线，反照率，照明方向以及光源和表面点之间的距离的函数。为了解决模型在法线和距离之间的模糊性，我们利用Kinect融合和多视图信息的初始三维网格来可靠估计未被Kinect融合捕获和重建的表面细节。我们的方法直接在几何细化的网格模型上运行。我们对Kinect I和Kinect II捕获的几何图形进行了算法实验，因为Kinect I的深度采集基于结构光技术，Kinect II的深度采集基于飞行时间（ToF ）技术。我们的方法的有效性通过几个具有挑战性的现实世界的例子来证明。我们还进行了用户研究，以评估我们改进前后的网格模型的质量。

##### URL
[https://arxiv.org/abs/1608.05204](https://arxiv.org/abs/1608.05204)

##### PDF
[https://arxiv.org/pdf/1608.05204](https://arxiv.org/pdf/1608.05204)

