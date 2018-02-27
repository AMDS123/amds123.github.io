---
layout: post
title: "Constructing Category-Specific Models for Monocular Object-SLAM"
date: 2018-02-26 13:42:40
categories: arXiv_CV
tags: arXiv_CV Sparse Knowledge SLAM
author: Parv Parkhiya, Rishabh Khawad, J. Krishna Murthy, Brojeshwar Bhowmick, K. Madhava Krishna
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new paradigm for real-time object-oriented SLAM with a monocular camera. Contrary to previous approaches, that rely on object-level models, we construct category-level models from CAD collections which are now widely available. To alleviate the need for huge amounts of labeled data, we develop a rendering pipeline that enables synthesis of large datasets from a limited amount of manually labeled data. Using data thus synthesized, we learn category-level models for object deformations in 3D, as well as discriminative object features in 2D. These category models are instance-independent and aid in the design of object landmark observations that can be incorporated into a generic monocular SLAM framework. Where typical object-SLAM approaches usually solve only for object and camera poses, we also estimate object shape on-the-fly, allowing for a wide range of objects from the category to be present in the scene. Moreover, since our 2D object features are learned discriminatively, the proposed object-SLAM system succeeds in several scenarios where sparse feature-based monocular SLAM fails due to insufficient features or parallax. Also, the proposed category-models help in object instance retrieval, useful for Augmented Reality (AR) applications. We evaluate the proposed framework on multiple challenging real-world scenes and show --- to the best of our knowledge --- first results of an instance-independent monocular object-SLAM system and the benefits it enjoys over feature-based SLAM methods.

##### Abstract (translated by Google)
我们为单眼相机提供了一种面向实时面向对象SLAM的新范例。与先前的依赖于对象级模型的方法相反，我们从现在广泛可用的CAD集合构建分类级模型。为了减少对大量标记数据的需求，我们开发了一个渲染管线，可以从有限数量的手动标记数据中合成大型数据集。使用这样合成的数据，我们学习了3D中物体变形的类别级模型，以及2D中的判别性物体特征。这些类别模型是独立于实例的，有助于设计可以结合到通用单眼SLAM框架中的对象标志性观察。在典型的物体SLAM方法中，通常只能求解物体和相机姿态，我们还可以即时估计物体的形状，从而可以在场景中出现范围广泛的物体。此外，由于我们的二维对象特征是有区别地学习的，所以所提出的对象 -  SLAM系统在几个由于特征或视差不足而导致基于稀疏特征的单眼SLAM失败的情况下成功。此外，所提出的类别模型有助于对象实例检索，对增强现实（AR）应用程序非常有用。我们评估了关于多个具有挑战性的真实世界场景的建议框架，并且尽我们所知地展示了独立于实例的单眼物体SLAM系统的第一个结果以及它在基于特征的SLAM方法中的优势。

##### URL
[http://arxiv.org/abs/1802.09292](http://arxiv.org/abs/1802.09292)

##### PDF
[http://arxiv.org/pdf/1802.09292](http://arxiv.org/pdf/1802.09292)

