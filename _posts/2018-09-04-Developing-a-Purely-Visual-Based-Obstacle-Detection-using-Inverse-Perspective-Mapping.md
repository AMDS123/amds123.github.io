---
layout: post
title: "Developing a Purely Visual Based Obstacle Detection using Inverse Perspective Mapping"
date: 2018-09-04 23:09:45
categories: arXiv_CV
tags: arXiv_CV Face Detection
author: Julian Nubert, Niklas Funk, Fabio Meier, Fabrice Oehler
mathjax: true
---

* content
{:toc}

##### Abstract
Our solution is implemented in and for the frame of Duckietown. The goal of Duckietown is to provide a relatively simple platform to explore, tackle and solve many problems linked to autonomous driving. "Duckietown" is simple in the basics, but an infinitely expandable environment. From controlling single driving Duckiebots until complete fleet management, every scenario is possible and can be put into practice. So far, none of the existing modules was capable of reliably detecting obstacles and reacting to them in real time. We faced the general problem of detecting obstacles given images from a monocular RGB camera mounted at the front of our Duckiebot and reacting to them properly without crashing or erroneously stopping the Duckiebot. Both, the detection as well as the reaction have to be implemented and have to run on a Raspberry Pi in real time. Due to the strong hardware limitations, we decided to not use any learning algorithms for the obstacle detection part. As it later transpired, a working "hard coded" software needs thorough analysis and understanding of the given problem. In layman's terms, we simply seek to make Duckietown a safer place.

##### Abstract (translated by Google)
我们的解决方案是在Duckietown的框架中实现的。 Duckietown的目标是提供一个相对简单的平台来探索，解决和解决与自动驾驶相关的许多问题。 “Duckietown”在基础知识方面很简单，但却是一个无限可扩展的环境。从控制单个驾驶Duckiebots直到完整的车队管理，每个场景都是可能的，并且可以付诸实践。到目前为止，现有的模块都没有能够可靠地检测障碍物并实时对它们作出反应。我们遇到了一个问题，即从安装在我们Duckiebot前面的单目RGB摄像机拍摄的图像中检测到障碍物并对它们做出适当反应而不会崩溃或错误地停止Duckiebot。两者都必须实现检测和反应，并且必须实时在Raspberry Pi上运行。由于强大的硬件限制，我们决定不对障碍物检测部分使用任何学习算法。后来发现，工作的“硬编码”软件需要彻底分析和理解给定的问题。通俗地说，我们只是想让Duckietown成为一个更安全的地方。

##### URL
[http://arxiv.org/abs/1809.01268](http://arxiv.org/abs/1809.01268)

##### PDF
[http://arxiv.org/pdf/1809.01268](http://arxiv.org/pdf/1809.01268)

