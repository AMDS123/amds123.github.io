---
layout: post
title: "Robust and fully automated segmentation of mandible from CT scans"
date: 2017-02-23 01:23:45
categories: arXiv_CV
tags: arXiv_CV Segmentation Detection Recognition
author: Neslisah Torosdagli, Denise K. Liberton, Payal Verma, Murat Sincan Janice Lee, Sumanta Pattanaik, Ulas Bagci
mathjax: true
---

* content
{:toc}

##### Abstract
Mandible bone segmentation from computed tomography (CT) scans is challenging due to mandible's structural irregularities, complex shape patterns, and lack of contrast in joints. Furthermore, connections of teeth to mandible and mandible to remaining parts of the skull make it extremely difficult to identify mandible boundary automatically. This study addresses these challenges by proposing a novel framework where we define the segmentation as two complementary tasks: recognition and delineation. For recognition, we use random forest regression to localize mandible in 3D. For delineation, we propose to use 3D gradient-based fuzzy connectedness (FC) image segmentation algorithm, operating on the recognized mandible sub-volume. Despite heavy CT artifacts and dental fillings, consisting half of the CT image data in our experiments, we have achieved highly accurate detection and delineation results. Specifically, detection accuracy more than 96% (measured by union of intersection (UoI)), the delineation accuracy of 91% (measured by dice similarity coefficient), and less than 1 mm in shape mismatch (Hausdorff Distance) were found.

##### Abstract (translated by Google)
由于下颌骨的结构不规则，复杂的形状模式以及关节缺乏对比，计算机断层扫描（CT）扫描的下颌骨分割具有挑战性。此外，牙齿与下颌骨和下颌骨连接至颅骨的其余部分使得自动识别下颌骨界限变得极为困难。本研究通过提出一个新的框架来解决这些挑战，我们将分割定义为两个互补的任务：认可和描述。为了识别，我们使用随机森林回归来定位3D下颌骨。为了描绘，我们建议使用基于梯度的三维模糊连接（FC）图像分割算法，在已识别的下颌骨体积上进行操作。尽管在我们的实验中有大量的CT伪影和牙齿填充物（包括一半的CT图像数据），但是我们已经实现了高度准确的检测和描绘结果。具体而言，检测精度超过96％（通过交点联合测量（UoI）），91％（通过骰子相似性系数测量）和小于1mm的形状不匹配（Hausdorff距离）的轮廓精度被发现。

##### URL
[https://arxiv.org/abs/1702.07059](https://arxiv.org/abs/1702.07059)

##### PDF
[https://arxiv.org/pdf/1702.07059](https://arxiv.org/pdf/1702.07059)

