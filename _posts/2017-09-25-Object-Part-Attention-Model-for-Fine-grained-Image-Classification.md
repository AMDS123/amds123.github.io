---
layout: post
title: "Object-Part Attention Model for Fine-grained Image Classification"
date: 2017-09-25 02:27:29
categories: arXiv_CV
tags: arXiv_CV Attention Weakly_Supervised Image_Classification Classification Relation
author: Yuxin Peng, Xiangteng He, Junjie Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Fine-grained image classification is to recognize hundreds of subcategories belonging to the same basic-level category, such as 200 subcategories belonging to the bird, which is highly challenging due to large variance in the same subcategory and small variance among different subcategories. Existing methods generally first locate the objects or parts and then discriminate which subcategory the image belongs to. However, they mainly have two limitations: (1) Relying on object or part annotations which are heavily labor consuming. (2) Ignoring the spatial relationships between the object and its parts as well as among these parts, both of which are significantly helpful for finding discriminative parts. Therefore, this paper proposes the object-part attention model (OPAM) for weakly supervised fine-grained image classification, and the main novelties are: (1) Object-part attention model integrates two level attentions: object-level attention localizes objects of images, and part-level attention selects discriminative parts of object. Both are jointly employed to learn multi-view and multi-scale features to enhance their mutual promotions. (2) Object-part spatial constraint model combines two spatial constraints: object spatial constraint ensures selected parts highly representative, and part spatial constraint eliminates redundancy and enhances discrimination of selected parts. Both are jointly employed to exploit the subtle and local differences for distinguishing the subcategories. Importantly, neither object nor part annotations are used in our proposed approach, which avoids the heavy labor consumption of labeling. Comparing with more than 10 state-of-the-art methods on 4 widely-used datasets, our OPAM approach achieves the best performance.

##### Abstract (translated by Google)
细粒度图像分类是识别属于同一基本类别的数百个子类别，如属于鸟类的200个子类别，由于同一子类别的差异较大，不同子类别间的差异较小，因此具有很大的挑战性。现有方法通常首先定位对象或部分，然后区分图像属于哪个子类别。但是，它们主要有两个局限性：（1）依赖于耗费人力的对象或部分注释。 （2）忽略物体与其各部分之间以及这些部分之间的空间关系，这两者对于发现有区别的部分都有很大的帮助。因此，本文提出了弱监督细粒度图像分类的对象 - 部分关注模型（OPAM），其主要创新点如下：（1）对象 - 部分关注模型集成了两层关注点：对象关注点定位图像对象，部分级别的关注选择对象的区分部分。双方共同学习多视点，多尺度的特点，加强相互促进。 （2）对象空间约束模型结合了两个空间约束：对象空间约束保证选定部分具有高度代表性，部分空间约束消除冗余，提高了对选定部分的区分度。两者共同利用微妙和地方差异区分子类别。重要的是，在我们提出的方法中，既不使用对象也不使用部分注释，这避免了标签的大量劳动力消耗。与4个广泛使用的数据集上的10多个最先进的方法相比，我们的OPAM方法实现了最佳性能。

##### URL
[https://arxiv.org/abs/1704.01740](https://arxiv.org/abs/1704.01740)

##### PDF
[https://arxiv.org/pdf/1704.01740](https://arxiv.org/pdf/1704.01740)

