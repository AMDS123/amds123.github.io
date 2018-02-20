---
layout: post
title: "Fast 5DOF Needle Tracking in iOCT"
date: 2018-02-18 21:15:54
categories: arXiv_CV
tags: arXiv_CV Tracking
author: Jakob Weiss, Nicola Rieke, Mohammad Ali Nasseri, Mathias Maier, Abouzar Eslami, Nassir Navab
mathjax: true
---

* content
{:toc}

##### Abstract
Purpose. Intraoperative Optical Coherence Tomography (iOCT) is an increasingly available imaging technique for ophthalmic microsurgery that provides high-resolution cross-sectional information of the surgical scene. We propose to build on its desirable qualities and present a method for tracking the orientation and location of a surgical needle. Thereby, we enable direct analysis of instrument-tissue interaction directly in OCT space without complex multimodal calibration that would be required with traditional instrument tracking methods. Method. The intersection of the needle with the iOCT scan is detected by a peculiar multi-step ellipse fitting that takes advantage of the directionality of the modality. The geometric modelling allows us to use the ellipse parameters and provide them into a latency aware estimator to infer the 5DOF pose during needle movement. Results. Experiments on phantom data and ex-vivo porcine eyes indicate that the algorithm retains angular precision especially during lateral needle movement and provides a more robust and consistent estimation than baseline methods. Conclusion. Using solely crosssectional iOCT information, we are able to successfully and robustly estimate a 5DOF pose of the instrument in less than 5.5 ms on a CPU.

##### Abstract (translated by Google)
目的。术中光学相干断层扫描（iOCT）是一种用于眼科显微手术的日益可用的成像技术，可提供手术场景的高分辨率横截面信息。我们提出建立在其理想品质基础上，并提出一种跟踪手术针的方向和位置的方法。因此，我们可以直接在OCT空间中直接分析仪器与组织的相互作用，而无需使用传统仪器跟踪方法所需的复杂多模态校准。方法。针与iOCT扫描的交叉点通过独特的多步椭圆拟合检测，该拟合利用了模态的方向性。几何建模允许我们使用椭圆参数并将其提供到延迟感知估计器中以推断针运动期间的5DOF姿态。结果。幻影数据和体外猪眼的实验表明，该算法保留角度精度，特别是在侧向针移动期间，并且提供比基线方法更稳健和一致的估计。结论。仅使用横截面iOCT信息，我们能够在CPU上在5.5 ms以内成功并稳健地估计仪器的5DOF姿态。

##### URL
[http://arxiv.org/abs/1802.06446](http://arxiv.org/abs/1802.06446)

##### PDF
[http://arxiv.org/pdf/1802.06446](http://arxiv.org/pdf/1802.06446)

