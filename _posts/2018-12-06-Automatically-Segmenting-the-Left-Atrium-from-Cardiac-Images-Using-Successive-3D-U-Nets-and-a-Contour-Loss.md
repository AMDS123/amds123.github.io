---
layout: post
title: "Automatically Segmenting the Left Atrium from Cardiac Images Using Successive 3D U-Nets and a Contour Loss"
date: 2018-12-06 13:34:24
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Prediction
author: Shuman Jia, Antoine Despinasse, Zihao Wang, Herv&#xe9; Delingette, Xavier Pennec, Pierre Ja&#xef;s, Hubert Cochet, Maxime Sermesant
mathjax: true
---

* content
{:toc}

##### Abstract
Radiological imaging offers effective measurement of anatomy, which is useful in disease diagnosis and assessment. Previous study has shown that the left atrial wall remodeling can provide information to predict treatment outcome in atrial fibrillation. Nevertheless, the segmentation of the left atrial structures from medical images is still very time-consuming. Current advances in neural network may help creating automatic segmentation models that reduce the workload for clinicians. In this preliminary study, we propose automated, two-stage, three-dimensional U-Nets with convolutional neural network, for the challenging task of left atrial segmentation. Unlike previous two-dimensional image segmentation methods, we use 3D U-Nets to obtain the heart cavity directly in 3D. The dual 3D U-Net structure consists of, a first U-Net to coarsely segment and locate the left atrium, and a second U-Net to accurately segment the left atrium under higher resolution. In addition, we introduce a Contour loss based on additional distance information to adjust the final segmentation. We randomly split the data into training datasets (80 subjects) and validation datasets (20 subjects) to train multiple models, with different augmentation setting. Experiments show that the average Dice coefficients for validation datasets are around 0.91 - 0.92, the sensitivity around 0.90-0.94 and the specificity 0.99. Compared with traditional Dice loss, models trained with Contour loss in general offer smaller Hausdorff distance with similar Dice coefficient, and have less connected components in predictions. Finally, we integrate several trained models in an ensemble prediction to segment testing datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.02518](http://arxiv.org/abs/1812.02518)

##### PDF
[http://arxiv.org/pdf/1812.02518](http://arxiv.org/pdf/1812.02518)

