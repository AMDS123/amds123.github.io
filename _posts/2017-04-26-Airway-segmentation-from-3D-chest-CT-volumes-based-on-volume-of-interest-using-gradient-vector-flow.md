---
layout: post
title: "Airway segmentation from 3D chest CT volumes based on volume of interest using gradient vector flow"
date: 2017-04-26 09:27:18
categories: arXiv_CV
tags: arXiv_CV Segmentation Detection
author: Qier Meng, Takayuki Kitasaka, Masahiro Oda, Junji Ueno, Kensaku Mori
mathjax: true
---

* content
{:toc}

##### Abstract
Some lung diseases are related to bronchial airway structures and morphology. Although airway segmentation from chest CT volumes is an important task in the computer-aided diagnosis and surgery assistance systems for the chest, complete 3-D airway structure segmentation is a quite challenging task due to its complex tree-like structure. In this paper, we propose a new airway segmentation method from 3D chest CT volumes based on volume of interests (VOI) using gradient vector flow (GVF). This method segments the bronchial regions by applying the cavity enhancement filter (CEF) to trace the bronchial tree structure from the trachea. It uses the CEF in the VOI to segment each branch. And a tube-likeness function based on GVF and the GVF magnitude map in each VOI are utilized to assist predicting the positions and directions of child branches. By calculating the tube-likeness function based on GVF and the GVF magnitude map, the airway-like candidate structures are identified and their centrelines are extracted. Based on the extracted centrelines, we can detect the branch points of the bifurcations and directions of the airway branches in the next level. At the same time, a leakage detection is performed to avoid the leakage by analysing the pixel information and the shape information of airway candidate regions extracted in the VOI. Finally, we unify all of the extracted bronchial regions to form an integrated airway tree. Preliminary experiments using four cases of chest CT volumes demonstrated that the proposed method can extract more bronchial branches in comparison with other methods.

##### Abstract (translated by Google)
一些肺部疾病与支气管气道结构和形态有关。虽然胸部CT容积的气道分割是胸部计算机辅助诊断和手术辅助系统的一项重要任务，但完整的三维气道结构分割由于其复杂的树状结构，是一项颇具挑战性的任务。在本文中，我们提出了一种新的气道分割方法从3D胸部CT卷基于利益（VOI）利用梯度矢量流（GVF）。该方法通过应用腔增强滤波器（CEF）来从气管追踪支气管树结构来分割支气管区域。它使用VOI中的CEF来分割每个分支。利用基于GVF和GVF幅度图的每个VOI的管样函数来辅助预测子分支的位置和方向。通过计算基于GVF和GVF幅度图的管样函数，确定气道样候选结构并提取其中心线。根据提取的中心线，可以检测下一级气道分支的分支点和方向。同时，通过分析在VOI中提取的气道候选区域的像素信息和形状信息，执行泄漏检测以避免泄漏。最后，我们统一所有提取的支气管区域，形成一个完整的气道树。对4例胸部CT容积的初步实验表明，与其他方法相比，所提出的方法可以提取更多的支气管分支。

##### URL
[https://arxiv.org/abs/1704.08030](https://arxiv.org/abs/1704.08030)

##### PDF
[https://arxiv.org/pdf/1704.08030](https://arxiv.org/pdf/1704.08030)

