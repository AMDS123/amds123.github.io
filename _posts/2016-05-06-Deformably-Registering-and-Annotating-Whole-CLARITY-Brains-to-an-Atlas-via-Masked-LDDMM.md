---
layout: post
title: "Deformably Registering and Annotating Whole CLARITY Brains to an Atlas via Masked LDDMM"
date: 2016-05-06 19:51:27
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Kwame S. Kutten, Joshua T. Vogelstein, Nicolas Charon, Li Ye, Karl Deisseroth, Michael I. Miller
mathjax: true
---

* content
{:toc}

##### Abstract
The CLARITY method renders brains optically transparent to enable high-resolution imaging in the structurally intact brain. Anatomically annotating CLARITY brains is necessary for discovering which regions contain signals of interest. Manually annotating whole-brain, terabyte CLARITY images is difficult, time-consuming, subjective, and error-prone. Automatically registering CLARITY images to a pre-annotated brain atlas offers a solution, but is difficult for several reasons. Removal of the brain from the skull and subsequent storage and processing cause variable non-rigid deformations, thus compounding inter-subject anatomical variability. Additionally, the signal in CLARITY images arises from various biochemical contrast agents which only sparsely label brain structures. This sparse labeling challenges the most commonly used registration algorithms that need to match image histogram statistics to the more densely labeled histological brain atlases. The standard method is a multiscale Mutual Information B-spline algorithm that dynamically generates an average template as an intermediate registration target. We determined that this method performs poorly when registering CLARITY brains to the Allen Institute's Mouse Reference Atlas (ARA), because the image histogram statistics are poorly matched. Therefore, we developed a method (Mask-LDDMM) for registering CLARITY images, that automatically find the brain boundary and learns the optimal deformation between the brain and atlas masks. Using Mask-LDDMM without an average template provided better results than the standard approach when registering CLARITY brains to the ARA. The LDDMM pipelines developed here provide a fast automated way to anatomically annotate CLARITY images. Our code is available as open source software at this http URL

##### Abstract (translated by Google)
CLARITY方法使大脑光学透明，以在结构完整的大脑中实现高分辨率成像。解剖注释CLARITY大脑是发现哪些区域包含感兴趣的信号所必需的。手动标注全脑，TB级的CLARITY图像困难，耗时，主观且容易出错。将CLARITY图像自动注册到预先注释的大脑图集提供了一个解决方案，但由于几个原因很困难。从颅骨中移除脑部，并随后进行储存和处理，引起可变的非刚性变形，从而复合了受试者之间的解剖变异性。此外，CLARITY图像中的信号来自各种生物化学造影剂，这些造影剂仅稀疏地标记脑结构。这种稀疏标记挑战了最常用的配准算法，这些算法需要将图像直方图统计量与更密集标记的组织学脑图谱相匹配。标准方法是一个多尺度的互信息B样条算法，动态生成一个平均模板作为中间注册目标。我们确定这种方法在将CLARITY大脑注册到Allen研究所的鼠标参考图谱（ARA）时表现不佳，因为图像直方图统计数据不匹配。因此，我们开发了一种用于注册CLARITY图像的方法（Mask-LDDMM），该方法自动查找大脑边界，并学习大脑和阿特拉斯面具之间的最佳变形。在向ARA注册CLARITY大脑时，使用没有平均模板的Mask-LDDMM提供比标准方法更好的结果。这里开发的LDDMM管道提供了一种快速自动的方式来解剖注释CLARITY图像。我们的代码在这个http URL中以开源软件的形式提供

##### URL
[https://arxiv.org/abs/1605.02060](https://arxiv.org/abs/1605.02060)

##### PDF
[https://arxiv.org/pdf/1605.02060](https://arxiv.org/pdf/1605.02060)

