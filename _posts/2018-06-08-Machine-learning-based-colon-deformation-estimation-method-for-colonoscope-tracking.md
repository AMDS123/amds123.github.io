---
layout: post
title: "Machine learning-based colon deformation estimation method for colonoscope tracking"
date: 2018-06-08 08:15:29
categories: arXiv_CV
tags: arXiv_CV Tracking Relation
author: Masahiro Oda, Takayuki Kitasaka, Kazuhiro Furukawa, Ryoji Miyahara, Yoshiki Hirooka, Hidemi Goto, Nassir Navab, Kensaku Mori
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a colon deformation estimation method, which can be used to estimate colon deformations during colonoscope insertions. Colonoscope tracking or navigation system that navigates a physician to polyp positions during a colonoscope insertion is required to reduce complications such as colon perforation. A previous colonoscope tracking method obtains a colonoscope position in the colon by registering a colonoscope shape and a colon shape. The colonoscope shape is obtained using an electromagnetic sensor, and the colon shape is obtained from a CT volume. However, large tracking errors were observed due to colon deformations occurred during colonoscope insertions. Such deformations make the registration difficult. Because the colon deformation is caused by a colonoscope, there is a strong relationship between the colon deformation and the colonoscope shape. An estimation method of colon deformations occur during colonoscope insertions is necessary to reduce tracking errors. We propose a colon deformation estimation method. This method is used to estimate a deformed colon shape from a colonoscope shape. We use the regression forests algorithm to estimate a deformed colon shape. The regression forests algorithm is trained using pairs of colon and colonoscope shapes, which contains deformations occur during colonoscope insertions. As a preliminary study, we utilized the method to estimate deformations of a colon phantom. In our experiments, the proposed method correctly estimated deformed colon phantom shapes.

##### Abstract (translated by Google)
本文介绍了一种结肠变形估计方法，可用于估计结肠镜插入过程中的结肠变形。为了减少结肠穿孔等并发症，需要在结肠镜插入过程中将医生导航到息肉位置的结肠镜跟踪或导航系统。先前的结肠镜追踪方法通过登记结肠镜形状和结肠形状来获得结肠中的结肠镜位置。使用电磁传感器获得结肠镜形状，并且从CT体积获得结肠形状。然而，由于在结肠镜插入期间发生结肠变形，观察到大的跟踪误差。这种变形使登记变得困难。由于结肠变形是由结肠镜引起的，因此结肠变形与结肠镜形状之间存在很强的关系。在结肠镜插入过程中发生结肠变形的估计方法对于减少跟踪误差是必要的。我们提出一种结肠变形估计方法。该方法用于从结肠镜形状估计变形的结肠形状。我们使用回归森林算法来估计变形的结肠形状。回归森林算法使用结肠和结肠镜形状对进行训练，其中包含结肠镜插入期间发生的变形。作为一项初步研究，我们利用该方法来估计冒号幻影的变形。在我们的实验中，所提出的方法正确估计变形的结肠幻影形状。

##### URL
[http://arxiv.org/abs/1806.03014](http://arxiv.org/abs/1806.03014)

##### PDF
[http://arxiv.org/pdf/1806.03014](http://arxiv.org/pdf/1806.03014)

