---
layout: post
title: "NetSpectre: Read Arbitrary Memory over Network"
date: 2018-07-27 11:13:18
categories: arXiv_CV
tags: arXiv_CV
author: Michael Schwarz, Martin Schwarzl, Moritz Lipp, Daniel Gruss
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present NetSpectre, a generic remote Spectre variant 1 attack. For this purpose, we demonstrate the first access-driven remote Evict+Reload cache attack over network, leaking 15 bits per hour. Beyond retrofitting existing attacks to a network scenario, we also demonstrate the first Spectre attack which does not use a cache covert channel. Instead, we present a novel high-performance AVX-based covert channel that we use in our cache-free Spectre attack. We show that in particular remote Spectre attacks perform significantly better with the AVX-based covert channel, leaking 60 bits per hour from the target system. We verified that our NetSpectre attacks work in local-area networks as well as between virtual machines in the Google cloud. NetSpectre marks a paradigm shift from local attacks, to remote attacks, exposing a much wider range and larger number of devices to Spectre attacks. Spectre attacks now must also be considered on devices which do not run any potentially attacker-controlled code at all. We show that especially in this remote scenario, attacks based on weaker gadgets which do not leak actual data, are still very powerful to break address-space layout randomization remotely. Several of the Spectre gadgets we discuss are more versatile than anticipated. In particular, value-thresholding is a technique we devise, which leaks a secret value without the typical bit selection mechanisms. We outline challenges for future research on Spectre attacks and Spectre mitigations.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1807.10535](https://arxiv.org/abs/1807.10535)

##### PDF
[https://arxiv.org/pdf/1807.10535](https://arxiv.org/pdf/1807.10535)

