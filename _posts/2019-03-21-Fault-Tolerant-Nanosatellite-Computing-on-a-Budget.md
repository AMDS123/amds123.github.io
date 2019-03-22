---
layout: post
title: "Fault-Tolerant Nanosatellite Computing on a Budget"
date: 2019-03-21 00:00:34
categories: arXiv_RO
tags: arXiv_RO
author: Christian M. Fuchs, Nadia Murillo, Aske Plaat, Erik Van der Kouwe, Daniel Harsono, Todor Stefanov
mathjax: true
---

* content
{:toc}

##### Abstract
Micro- and nanosatellites have become popular platforms for a variety of commercial and scientific applications, but today are considered suitable mainly for short and low-priority space missions due to their low reliability. In part, this can be attributed to their reliance upon cheap, low-feature size, COTS components originally designed for embedded and mobile-market applications, for which traditional hardware-voting concepts are ineffective. Software-fault-tolerance concepts have been shown effective for such systems, but have largely been ignored by the space industry due to low maturity, as most have only been researched in theory. In practice, designers of payload instruments and miniaturized satellites are usually forced to sacrifice reliability in favor deliver the level of performance necessary for cutting-edge science and innovative commercial applications. Thus, we developed a software-fault-tolerance-approach based upon thread-level coarse-grain lockstep, which was validated using fault-injection. To offer strong long-term fault coverage, our architecture is implemented as tiled MPSoC on an FPGA, utilizing partial reconfiguration, as well as mixed criticality. This architecture can satisfy the high performance requirements of current and future scientific and commercial space missions at very low cost, while offering the strong fault-coverage guarantees necessary for platform control even for missions with a long duration. This architecture was developed for a 4-year ESA project. Together with two industrial partners, we are developing a prototype to then undergo radiation testing.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.08781](http://arxiv.org/abs/1903.08781)

##### PDF
[http://arxiv.org/pdf/1903.08781](http://arxiv.org/pdf/1903.08781)

