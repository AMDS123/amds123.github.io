---
layout: post
title: "Multi-task Localization and Segmentation for X-ray Guided Planning in Knee Surgery"
date: 2019-07-24 14:32:10
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation Semantic_Segmentation
author: Florian Kordon (1 and 2 and 3), Peter Fischer (1 and 2), Maxim Privalov (4), Benedict Swartman (4), Marc Schnetzke (4), Jochen Franke (4), Ruxandra Lasowski (3), Andreas Maier (1), Holger Kunze (2) ((1) Pattern Recognition Lab, Department of Computer Science, Friedrich-Alexander-Universit&#xe4;t Erlangen-N&#xfc;rnberg, Erlangen, Germany, (2) Advanced Therapies, Siemens Healthcare GmbH, Forchheim, Germany, (3) Faculty of Digital Media, Hochschule Furtwangen, Furtwangen, Germany, (4) Department for Trauma and Orthopaedic Surgery, BG Trauma Center Ludwigshafen, Ludwigshafen, Germany)
mathjax: true
---

* content
{:toc}

##### Abstract
X-ray based measurement and guidance are commonly used tools in orthopaedic surgery to facilitate a minimally invasive workflow. Typically, a surgical planning is first performed using knowledge of bone morphology and anatomical landmarks. Information about bone location then serves as a prior for registration during overlay of the planning on intra-operative X-ray images. Performing these steps manually however is prone to intra-rater/inter-rater variability and increases task complexity for the surgeon. To remedy these issues, we propose an automatic framework for planning and subsequent overlay. We evaluate it on the example of femoral drill site planning for medial patellofemoral ligament reconstruction surgery. A deep multi-task stacked hourglass network is trained on 149 conventional lateral X-ray images to jointly localize two femoral landmarks, to predict a region of interest for the posterior femoral cortex tangent line, and to perform semantic segmentation of the femur, patella, tibia, and fibula with adaptive task complexity weighting. On 38 clinical test images the framework achieves a median localization error of 1.50 mm for the femoral drill site and mean IOU scores of 0.99, 0.97, 0.98, and 0.96 for the femur, patella, tibia, and fibula respectively. The demonstrated approach consistently performs surgical planning at expert-level precision without the need for manual correction.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.10465](http://arxiv.org/abs/1907.10465)

##### PDF
[http://arxiv.org/pdf/1907.10465](http://arxiv.org/pdf/1907.10465)

