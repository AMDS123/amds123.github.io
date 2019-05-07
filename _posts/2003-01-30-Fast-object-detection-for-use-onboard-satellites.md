---
layout: post
title: "Fast object detection for use onboard satellites"
date: 2003-01-30 15:25:48
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Martin Bange (1), Stefan Jordan (2), Michael Biermann (3), Thomas Kaempke (1), R alf-Dieter Scholz (4) ((1) FAW, Ulm, Germany, (2) IAAT, Tuebingen, Germany, (3) ARI, Heidelberg, Germa ny, (4) AIP, Potsdam, Germany)
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an object detection algorithm which is efficient and fast enough to be used in (almost) real time with the limited computer capacities onboard satellites. For stars below the saturation limit of the CCD detectors it is based on a four neighbourhood local maximum criterion in order to find the centre of a stellar image. For saturated stars it is based on the assumption that the image is increasing monotonically towards the centre in the unsaturated part of the image. The algorithm also calculates approximate stellar magnitudes and efficiently rejects most of the cosmics which would otherwise lead to a large number of false detections. The quality of the algorithm was evaluated with the help of a large set of simulated data for the DIVA satellite mission; different assumptions were made for the noise level, and the presence of cosmics or for a variable sky background. We could show that our algorithm fulfills the requirements for DIVA; only in the case of simulated images which included the bright galaxy M31 some fainter stars could not be detected in the galaxy's vicinity. Since stellar images contain large areas without any stars, we propose an additional block-skipping algorithm which can be coded on special-purpose hardware.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/astro-ph/0301611](https://arxiv.org/abs/astro-ph/0301611)

##### PDF
[https://arxiv.org/pdf/astro-ph/0301611](https://arxiv.org/pdf/astro-ph/0301611)

