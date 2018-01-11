---
layout: post
title: "Recognizing Material Properties from Images"
date: 2018-01-09 20:22:41
categories: arXiv_CV
tags: arXiv_CV Transfer_Learning Classification Recognition
author: Gabriel Schwartz, Ko Nishino
mathjax: true
---

* content
{:toc}

##### Abstract
Humans rely on properties of the materials that make up objects to guide our interactions with them. Grasping smooth materials, for example, requires care, and softness is an ideal property for fabric used in bedding. Even when these properties are not visual (e.g. softness is a physical property), we may still infer their presence visually. We refer to such material properties as visual material attributes. Recognizing these attributes in images can contribute valuable information for general scene understanding and material recognition. Unlike well-known object and scene attributes, visual material attributes are local properties with no fixed shape or spatial extent. We show that given a set of images annotated with known material attributes, we may accurately recognize the attributes from small local image patches. Obtaining such annotations in a consistent fashion at scale, however, is challenging. To address this, we introduce a method that allows us to probe the human visual perception of materials by asking simple yes/no questions comparing pairs of image patches. This provides sufficient weak supervision to build a set of attributes and associated classifiers that, while unnamed, serve the same function as the named attributes we use to describe materials. Doing so allows us to recognize visual material attributes without resorting to exhaustive manual annotation of a fixed set of named attributes. Furthermore, we show that this method may be integrated in the end-to-end learning of a material classification CNN to simultaneously recognize materials and discover their visual attributes. Our experimental results show that visual material attributes, whether named or automatically discovered, provide a useful intermediate representation for known material categories themselves as well as a basis for transfer learning when recognizing previously-unseen categories.

##### Abstract (translated by Google)
人类依靠构成物体的材料的属性来指导我们与它们的相互作用。抓住光滑的材料，例如，需要小心，柔软是床上用织物的理想特性。即使这些属性不是可视的（例如，柔软是一种物理属性），我们仍然可以通过视觉来推断它们的存在。我们将这种材料属性称为视觉材料属性。识别图像中的这些属性可以为一般的场景理解和材料识别提供有价值的信息。与着名的对象和场景属性不同，可视材质属性是没有固定形状或空间范围的局部属性。我们表明，给定一组用已知材质属性注释的图像，我们可以准确地识别来自小本地图像块的属性。然而，以一致的方式大规模获得这些注释是具有挑战性的。为了解决这个问题，我们介绍一种方法，让我们通过比较成对的图像块来询问简单的是/否问题来探测材料的人类视觉感知。这提供了足够的弱监督来建立一组属性和关联的分类器，虽然未命名，但它们与我们用来描述材料的命名属性具有相同的功能。这样做可以让我们识别视觉材质属性，而无需对一组固定的命名属性进行详尽的手动注释。此外，我们表明，这种方法可能被整合到材料分类CNN的端到端学习中，以同时识别材料并发现其视觉属性。我们的实验结果表明，视觉材料属性，无论是命名还是自动发现，都为已知的材料类别本身提供了一个有用的中间表示，并且在识别先前看不见的类别时提供了转移学习的基础。

##### URL
[https://arxiv.org/abs/1801.03127](https://arxiv.org/abs/1801.03127)

##### PDF
[https://arxiv.org/pdf/1801.03127](https://arxiv.org/pdf/1801.03127)

