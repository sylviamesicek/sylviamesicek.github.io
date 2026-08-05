+++
title="Discontinuous Galerkin Method Applied to Critical Phenomena in Gravitational Collapse"
date=2026-08-04

template="publication.html"

extra.journal="Physical Review D"
extra.kind = "publication"

[taxonomies]
categories = ["Numerical Relativity"]
+++

This work applies the FEM-based Discontinuous Galerkin method to simulations of critical phenomena in spherically symmetric black hole collapse.

<!-- **Citation**: *Atmosphere: Towards Practical Verified Kernels in Rust*. Xiangdong C., Zhaofeng L., Mesicek L., Narayanan V., and Burtsev A. Published in _KISV '23: Proceedings of the 1st Workshop on Kernel Isolation, Safety and Verification_. -->

**Citation**: Johnson, S., Mesicek, S., & Belz, J. (2026). Discontinuous Galerkin method applied to critical phenomena in gravitational collapse. *Physical Review D, 114*(4). https://doi.org/10.1103/k9rg-pb8z

**DOI**: [10.1103/k9rg-pb8z](https://link.aps.org/doi/10.1103/k9rg-pb8z)

<!-- more -->

### Abstract

Numerical studies of critical phenomena in gravitational collapse have provided key insights into the nonlinear dynamics of Einstein’s field equations in the strong-field regime. However, most prior investigations have been restricted to highly symmetric models, limiting our understanding of the universality of critical behavior. Extending these studies to more general systems poses substantial computational challenges, as resolving the fine-scale structure near the black hole threshold requires extremely high spatial and temporal resolution. In this work, we present the first direct comparison between the discontinuous Galerkin (DG) and finite-difference methods applied to critical phenomena. For the case study, we used the classical example of spherically symmetric gravitational collapse of massless scalar fields. The DG method, which combines the high-order accuracy of spectral techniques with the flexibility and locality of finite-difference schemes, demonstrates significant computational advantages: Near criticality, it achieves comparable accuracy with fewer degrees of freedom, approximately half the number of computational steps, and a third of the run-time required by finite-difference methods. These improvements mitigate the run-time and resolution limitations characteristic of finite-difference simulations in higher dimensions and complex field systems. A detailed extension of the DG framework to the collapse of nonlinear, axisymmetric gravitational waves will be reported in future work.

<!-- ### Contribution

I built and managed the wavelet-adaptive finite difference code used as a comparision to the adaptive DG method in this paper, and performed parameter space searches for fine structure in  -->