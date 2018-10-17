---
layout: post
title: "Automatic Segmentation of Thoracic Aorta Segments in Low-Dose Chest CT"
date: 2018-10-09 13:31:10
categories: arXiv_CV
tags: arXiv_CV Segmentation Face CNN
author: Julia M. H. Noothout, Bob D. de Vos, Jelmer M. Wolterink, Ivana Isgum
mathjax: true
---

* content
{:toc}

##### Abstract
Morphological analysis and identification of pathologies in the aorta are important for cardiovascular diagnosis and risk assessment in patients. Manual annotation is time-consuming and cumbersome in CT scans acquired without contrast enhancement and with low radiation dose. Hence, we propose an automatic method to segment the ascending aorta, the aortic arch and the thoracic descending aorta in low-dose chest CT without contrast enhancement. Segmentation was performed using a dilated convolutional neural network (CNN), with a receptive field of 131X131 voxels, that classified voxels in axial, coronal and sagittal image slices. To obtain a final segmentation, the obtained probabilities of the three planes were averaged per class, and voxels were subsequently assigned to the class with the highest class probability. Two-fold cross-validation experiments were performed where ten scans were used to train the network and another ten to evaluate the performance. Dice coefficients of 0.83, 0.86 and 0.88, and Average Symmetrical Surface Distances (ASSDs) of 2.44, 1.56 and 1.87 mm were obtained for the ascending aorta, the aortic arch, and the descending aorta, respectively. The results indicate that the proposed method could be used in large-scale studies analyzing the anatomical location of pathology and morphology of the thoracic aorta.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.05727](https://arxiv.org/abs/1810.05727)

##### PDF
[https://arxiv.org/pdf/1810.05727](https://arxiv.org/pdf/1810.05727)

