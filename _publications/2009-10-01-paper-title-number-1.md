---
title: "Analyzing Sharpness along GD Trajectory: Progressive Sharpening and Edge of Stability"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: ''
date: 2022-10-15
venue: '36th Conference on Neural Information Processing Systems (NeurIPS)'
paperurl: 'http://wangzx19.github.io/files/analyzing_sharpness_along_gd_t.pdf'
citation: 'Li, Z., Wang, Z., & Li, J. (2022). Analyzing sharpness along gd trajectory: Progressive sharpening and edge of stability. arXiv preprint arXiv:2207.12678.'
---
Zhouzi Li$^*$, **Zixuan Wang$^*$**, Jian Li. (Accepted to NeurIPS 2022)

**Abstract: ** Recent findings demonstrate that modern neural networks trained by full-batch gradient descent typically enter a regime called Edge of Stability (EOS). In this regime, the sharpness, i.e., the maximum Hessian eigenvalue, first increases to the value 2/(step size) (the progressive sharpening phase) and then oscillates around this value (the EOS phase). This paper aims to analyze the GD dynamics and the sharpness along the optimization trajectory. Our analysis naturally divides the GD trajectory into four phases depending on the change in the sharpness value. We empirically identify the norm of output layer weight as an interesting indicator of the sharpness dynamics. Based on this empirical observation, we attempt to theoretically and empirically explain the dynamics of various key quantities that lead to the change of the sharpness in each phase of EOS. Moreover, based on certain assumptions, we provide a theoretical proof of the sharpness behavior in the EOS regime in two-layer fully-connected linear neural networks. We also discuss some other empirical findings and the limitation of our theoretical results.

