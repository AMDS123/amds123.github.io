---
layout: post
title: "HardIDX: Practical and Secure Index with SGX"
date: 2017-03-14 17:09:30
categories: arXiv_CV
tags: arXiv_CV
author: Benny Fuhry (1), Raad Bahmani (2), Ferdinand Brasser (2), Florian Hahn (1), Florian Kerschbaum (3), Ahmad-Reza Sadeghi (2) ((1) SAP Research, (2) Technische Universität Darmstadt, (3) University of Waterloo)
mathjax: true
---

* content
{:toc}

##### Abstract
Software-based approaches for search over encrypted data are still either challenged by lack of proper, low-leakage encryption or slow performance. Existing hardware-based approaches do not scale well due to hardware limitations and software designs that are not specifically tailored to the hardware architecture, and are rarely well analyzed for their security (e.g., the impact of side channels). Additionally, existing hardware-based solutions often have a large code footprint in the trusted environment susceptible to software compromises. In this paper we present HardIDX: a hardware-based approach, leveraging Intel's SGX, for search over encrypted data. It implements only the security critical core, i.e., the search functionality, in the trusted environment and resorts to untrusted software for the remainder. HardIDX is deployable as a highly performant encrypted database index: it is logarithmic in the size of the index and searches are performed within a few milliseconds rather than seconds. We formally model and prove the security of our scheme showing that its leakage is equivalent to the best known searchable encryption schemes. Our implementation has a very small code and memory footprint yet still scales to virtually unlimited search index sizes, i.e., size is limited only by the general - non-secure - hardware resources.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1703.04583](https://arxiv.org/abs/1703.04583)

##### PDF
[https://arxiv.org/pdf/1703.04583](https://arxiv.org/pdf/1703.04583)

