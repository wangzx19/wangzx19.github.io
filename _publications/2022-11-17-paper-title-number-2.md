---
title: "Understanding Edge-of-Stability Training Dynamics With a Minimalist Example"
collection: publications
permalink: /publication/2022-11-17-paper-title-number-2
excerpt: ''
venue: 'arXiv:2210.03294'
date: 2022-11-17
paperurl: 'http://wangzx19.github.io/files/EoS_tex_ICLRv2.pdf'
citation: 'Zhu, X., Wang, Z., Wang, X., Zhou, M., & Ge, R. (2022). Understanding Edge-of-Stability Training Dynamics with a Minimalist Example. arXiv preprint arXiv:2210.03294.'
---
Xingyu Zhu$^*$, **Zixuan Wang$^*$** , Xiang Wang, Mo Zhou, Rong Ge. (Submitted to ICLR 2023)

**Abstract:** Recently, researchers observed that gradient descent for deep neural networks operates in an “edge-of-stability” (EoS) regime: the sharpness (maximum eigenvalue of the Hessian) is often larger than stability threshold 2/η (where η is the step size). Despite this, the loss oscillates and converges in the long run, and the sharpness at the end is just slightly below 2/η. While many other well-understood nonconvex objectives such as matrix factorization or two-layer networks can also converge despite large sharpness, there is often a larger gap between sharpness of the endpoint and 2/η. In this paper, we study EoS phenomenon by constructing a simple function that has the same behavior. We give rigorous analysis for its training dynamics in a large local region and explain why the final converging point has sharpness close to 2/η. Globally we observe that the training dynamics for our example has an interesting bifurcating behavior, which was also observed in the training of neural nets.