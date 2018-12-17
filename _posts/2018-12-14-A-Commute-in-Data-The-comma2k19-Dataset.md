---
layout: post
title: "A Commute in Data: The comma2k19 Dataset"
date: 2018-12-14 01:20:38
categories: arXiv_RO
tags: arXiv_RO
author: Harald Schafer, Eder Santana, Andrew Haden, Riccardo Biasini
mathjax: true
---

* content
{:toc}

##### Abstract
comma.ai presents comma2k19, a dataset of over 33 hours of commute in California's 280 highway. This means 2019 segments, 1 minute long each, on a 20km section of highway driving between California's San Jose and San Francisco. The dataset was collected using comma EONs that have sensors similar to those of any modern smartphone including a road-facing camera, phone GPS, thermometers and a 9-axis IMU. Additionally, the EON captures raw GNSS measurements and all CAN data sent by the car with a comma grey panda. Laika, an open-source GNSS processing library, is also introduced here. Laika produces 40% more accurate positions than the GNSS module used to collect the raw data. This dataset includes pose (position + orientation) estimates in a global reference frame of the recording camera. These poses were computed with a tightly coupled INS/GNSS/Vision optimizer that relies on data processed by Laika. comma2k19 is ideal for development and validation of tightly coupled GNSS algorithms and mapping algorithms that work with commodity sensors.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.05752](http://arxiv.org/abs/1812.05752)

##### PDF
[http://arxiv.org/pdf/1812.05752](http://arxiv.org/pdf/1812.05752)

