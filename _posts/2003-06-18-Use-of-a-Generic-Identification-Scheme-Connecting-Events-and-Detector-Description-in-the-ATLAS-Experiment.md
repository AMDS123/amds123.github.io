---
layout: post
title: "Use of a Generic Identification Scheme Connecting Events and Detector Description in the ATLAS Experiment"
date: 2003-06-18 17:01:53
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: C. Arnault, A. Schaffer
mathjax: true
---

* content
{:toc}

##### Abstract
High energy physics detectors can be described hierarchically from the different subsystems to their divisions in r, phi, theta and to the individual readout channels. An identification schema that follows the logical decomposition of the ATLAS detector has been introduced allowing identification of individual readout channels as well as other parts of the detector, in particular detector elements. These identifiers provide a sort of ?glue? allowing, for example, the connection of raw event data to their detector description for position calculation or alignment corrections, as well as fast access to subsets of the event data for event trigger selection. There are two important requirements on the software to support such an identification scheme. First is the possibility to formally specify these identifiers in terms of their structure and allowed values. And second is to generate different forms of the identifiers optimised in terms of access efficiency to information content, compactness or search key efficiency. We present here the generic toolkit developed in the context of the ATLAS experiment to primarily provide the identification of the readout channels and detector elements. The architecture of the toolkit is decomposed into three parts: an XML-based dictionary containing the formal specification of a particular range of identifiers, a set of various identifier classes (offering various level of compaction), and finally a set of ?helper? classes, specific for each detector system, which serve as intermediaries between the dictionary and the identifier classes to create, manipulate and interpret the identifiers. This architecture will be described as well as the various applications of this identification scheme.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/physics/0306141](https://arxiv.org/abs/physics/0306141)

##### PDF
[https://arxiv.org/pdf/physics/0306141](https://arxiv.org/pdf/physics/0306141)

