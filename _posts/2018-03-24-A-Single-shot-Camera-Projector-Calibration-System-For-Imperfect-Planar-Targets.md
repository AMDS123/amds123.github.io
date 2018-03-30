---
layout: post
title: "A Single-shot Camera-Projector Calibration System For Imperfect Planar Targets"
date: 2018-03-24 05:25:23
categories: arXiv_CV
tags: arXiv_CV
author: Bingyao Huang, Samed Ozdemir, Ying Tang, Haibin Ling
mathjax: true
---

* content
{:toc}

##### Abstract
Existing camera-projector calibration methods typically warp feature points from a camera image to a projector image using estimated homographies, and often suffer from errors in camera parameters and noise due to imperfect planarity of the calibration target. In this paper we propose a simple yet robust solution that explicitly deals with these challenges. Following the structured light (SL) camera-project calibration framework, a carefully designed correspondence algorithm is built on top of the De Bruijn patterns. Such correspondence is then used for initial camera-projector calibration. Then, to gain more robustness against noises, especially those from an imperfect planar calibration board, a novel bundle adjustment algorithm is developed to jointly optimize the estimated camera and projector models. Aside from the robustness, our solution requires only one shot of SL pattern for each calibration board pose, which is much more convenient than multi-shot solutions in practice. Data validations are conducted on both synthetic and real datasets, and our method shows clear advantages over existing methods in all experiments.

##### Abstract (translated by Google)
现有的照相机 - 投影仪校准方法通常使用估计的单应性将从照相机图像到投影仪图像的特征点扭曲，并且由于校准目标的不完整平面性而经常遭受照相机参数和噪声的误差。在本文中，我们提出了一个简单而强大的解决方案，可以明确处理这些挑战。在结构光（SL）相机项目校准框架之后，精心设计的对应算法建立在De Bruijn模式之上。这种对应关系然后用于初始相机投影仪校准。然后，为了获得更强的鲁棒性以抵御噪声，尤其是来自不完美平面校准板的噪声，开发了新的束调整算法来联合优化估计的相机和投影仪模型。除了鲁棒性之外，我们的解决方案仅需要每个校准板姿态一次SL图案，这比实际中的多次拍摄解决方案更方便。数据验证是在合成数据集和真实数据集上进行的，我们的方法在所有实验中都比现有方法显示出明显的优势。

##### URL
[https://arxiv.org/abs/1803.09058](https://arxiv.org/abs/1803.09058)

##### PDF
[https://arxiv.org/pdf/1803.09058](https://arxiv.org/pdf/1803.09058)

