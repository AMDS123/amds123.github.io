---
layout: post
title: "Deep-learning-based identification of odontogenic keratocysts in hematoxylin- and eosin-stained jaw cyst specimens"
date: 2019-01-12 12:10:52
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Classification
author: Kei Sakamoto, Kei-ichi Morita, Tohru Ikeda, Kou Kayamori
mathjax: true
---

* content
{:toc}

##### Abstract
The aim of this study was to develop a digital histopathology system for identifying odontogenic keratocysts in hematoxylin- and eosin-stained tissue specimens of jaw cysts. Approximately 5000 microscopy images with 400$\times$ magnification were obtained from 199 odontogenic keratocysts, 208 dentigerous cysts, and 55 radicular cysts. A proportion of these images were used to make training patches, which were annotated as belonging to one of the following three classes: keratocysts, non-keratocysts, and stroma. The patches for the cysts contained the complete lining epithelium, with the cyst cavity being present on the upper side. The convolutional neural network (CNN) VGG16 was finetuned to this dataset. The trained CNN could recognize the basal cell palisading pattern, which is the definitive criterion for diagnosing keratocysts. Some of the remaining images were scanned and analyzed by the trained CNN, whose output was then used to train another CNN for binary classification (keratocyst or not). The area under the receiver operating characteristics curve for the entire algorithm was 0.997 for the test dataset. Thus, the proposed patch classification strategy is usable for automated keratocyst diagnosis. However, further optimization must be performed to make it suitable for practical use.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.03857](http://arxiv.org/abs/1901.03857)

##### PDF
[http://arxiv.org/pdf/1901.03857](http://arxiv.org/pdf/1901.03857)

