---
layout: post
title: "Network-Accelerated Non-Contiguous Memory Transfers"
date: 2019-08-22 20:52:23
categories: arXiv_CV
tags: arXiv_CV
author: Salvatore Di Girolamo, Konstantin Taranov, Andreas Kurth, Michael Schaffner, Timo Schneider, Jakub Beránek, Maciej Besta, Luca Benini, Duncan Roweth, Torsten Hoefler
mathjax: true
---

* content
{:toc}

##### Abstract
Applications often communicate data that is non-contiguous in the send- or the receive-buffer, e.g., when exchanging a column of a matrix stored in row-major order. While non-contiguous transfers are well supported in HPC (e.g., MPI derived datatypes), they can still be up to 5x slower than contiguous transfers of the same size. As we enter the era of network acceleration, we need to investigate which tasks to offload to the NIC: In this work we argue that non-contiguous memory transfers can be transparently networkaccelerated, truly achieving zero-copy communications. We implement and extend sPIN, a packet streaming processor, within a Portals 4 NIC SST model, and evaluate strategies for NIC-offloaded processing of MPI datatypes, ranging from datatype-specific handlers to general solutions for any MPI datatype. We demonstrate up to 10x speedup in the unpack throughput of real applications, demonstrating that non-contiguous memory transfers are a first-class candidate for network acceleration.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.08590](https://arxiv.org/abs/1908.08590)

##### PDF
[https://arxiv.org/pdf/1908.08590](https://arxiv.org/pdf/1908.08590)

