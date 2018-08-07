---
layout: post
title: "Parsing Geometry Using Structure-Aware Shape Templates"
date: 2018-08-03 20:14:58
categories: arXiv_CV
tags: arXiv_CV GAN Recognition
author: Vignesh Ganapathi-Subramanian, Olga Diamanti, Soeren Pirk, Chengcheng Tang, Matthias Niessner, Leonidas J. Guibas
mathjax: true
---

* content
{:toc}

##### Abstract
Real-life man-made objects often exhibit strong and easily-identifiable structure, as a direct result of their design or their intended functionality. Structure typically appears in the form of individual parts and their arrangement. Knowing about object structure can be an important cue for object recognition and scene understanding - a key goal for various AR and robotics applications. However, commodity RGB-D sensors used in these scenarios only produce raw, unorganized point clouds, without structural information about the captured scene. Moreover, the generated data is commonly partial and susceptible to artifacts and noise, which makes inferring the structure of scanned objects challenging. In this paper, we organize large shape collections into parameterized shape templates to capture the underlying structure of the objects. The templates allow us to transfer the structural information onto new objects and incomplete scans. We employ a deep neural network that matches the partial scan with one of the shape templates, then match and fit it to complete and detailed models from the collection. This allows us to faithfully label its parts and to guide the reconstruction of the scanned object. We showcase the effectiveness of our method by comparing it to other state-of-the-art approaches.

##### Abstract (translated by Google)
现实生活中的人造物体通常表现出强大且易于识别的结构，这是其设计或其预期功能的直接结果。结构通常以单个部件及其布置的形式出现。了解对象结构可以成为对象识别和场景理解的重要线索 - 这是各种AR和机器人应用的关键目标。然而，在这些场景中使用的商品RGB-D传感器仅产生原始的，无组织的点云，而没有关于捕获的场景的结构信息。此外，所生成的数据通常是部分的并且易受伪像和噪声的影响，这使得推断扫描对象的结构具有挑战性。在本文中，我们将大型形状集合组织成参数化形状模板，以捕获对象的底层结构。模板允许我们将结构信息传输到新对象和不完整扫描。我们采用深度神经网络，将部分扫描与其中一个形状模板相匹配，然后匹配并将其与集合中的完整和详细模型相匹配。这使我们能够忠实地标记其部件并指导重建被扫描物体。我们通过将其与其他最先进的方法进行比较来展示我们方法的有效性。

##### URL
[https://arxiv.org/abs/1808.01337](https://arxiv.org/abs/1808.01337)

##### PDF
[https://arxiv.org/pdf/1808.01337](https://arxiv.org/pdf/1808.01337)

