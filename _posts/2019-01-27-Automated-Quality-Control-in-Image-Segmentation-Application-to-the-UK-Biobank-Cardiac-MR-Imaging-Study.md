---
layout: post
title: "Automated Quality Control in Image Segmentation: Application to the UK Biobank Cardiac MR Imaging Study"
date: 2019-01-27 10:52:34
categories: arXiv_CV
tags: arXiv_CV Segmentation Face Classification Quantitative Relation
author: Robert Robinson (1), Vanya V. Valindria (1), Wenjia Bai (1), Ozan Oktay (1), Bernhard Kainz (1), Hideaki Suzuki (2), Mihir M. Sanghvi (4 and 5), Nay Aung (4 and 5), Jos$&#xe9;$ Miguel Paiva (4), Filip Zemrak (4 and 5), Kenneth Fung (4 and 5), Elena Lukaschuk (6), Aaron M. Lee (4 and 5), Valentina Carapella (6), Young Jin Kim (6 and 7), Stefan K. Piechnik (6), Stefan Neubauer (6), Steffen E. Petersen (4 and 5), Chris Page (3), Paul M. Matthews (2 and 8), Daniel Rueckert (1), Ben Glocker (1) ((1) Biomedical Image Analysis Group, Department of Computing, Imperial College London, (2) Division of Brain Sciences, Dept. of Medicine, Imperial College London, (3) GlaxoSmithKline Research and Development, UK, (4) William Harvey Research Institute, Queen Mary University of London, (5) Barts Heart Centre, London, (6) Division of Cardiovascular Medicine, Radcliffe Department of Medicine, University of Oxford, (7) Department of Radiology, Severance Hospital, South Korea, (8) UK Dementia Research Institute, Imperial College London)
mathjax: true
---

* content
{:toc}

##### Abstract
Background: The trend towards large-scale studies including population imaging poses new challenges in terms of quality control (QC). This is a particular issue when automatic processing tools, e.g. image segmentation methods, are employed to derive quantitative measures or biomarkers for later analyses. Manual inspection and visual QC of each segmentation isn't feasible at large scale. However, it's important to be able to automatically detect when a segmentation method fails so as to avoid inclusion of wrong measurements into subsequent analyses which could lead to incorrect conclusions. Methods: To overcome this challenge, we explore an approach for predicting segmentation quality based on Reverse Classification Accuracy, which enables us to discriminate between successful and failed segmentations on a per-cases basis. We validate this approach on a new, large-scale manually-annotated set of 4,800 cardiac magnetic resonance scans. We then apply our method to a large cohort of 7,250 cardiac MRI on which we have performed manual QC. Results: We report results used for predicting segmentation quality metrics including Dice Similarity Coefficient (DSC) and surface-distance measures. As initial validation, we present data for 400 scans demonstrating 99% accuracy for classifying low and high quality segmentations using predicted DSC scores. As further validation we show high correlation between real and predicted scores and 95% classification accuracy on 4,800 scans for which manual segmentations were available. We mimic real-world application of the method on 7,250 cardiac MRI where we show good agreement between predicted quality metrics and manual visual QC scores. Conclusions: We show that RCA has the potential for accurate and fully automatic segmentation QC on a per-case basis in the context of large-scale population imaging as in the UK Biobank Imaging Study.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.09351](http://arxiv.org/abs/1901.09351)

##### PDF
[http://arxiv.org/pdf/1901.09351](http://arxiv.org/pdf/1901.09351)

