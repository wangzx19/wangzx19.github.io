---
layout: cv
permalink: /cv/
title: 
tags: [about]
modified: 12-9-2020
comments: false

---

### **Understanding Over-paramaterized Non-orthogonal Tensor Decomposition**
<p align = "right"> 3.2022 – present</p>

Student Research Intern, advised by [Prof. Rong Ge]([Rong Ge, Duke University](https://users.cs.duke.edu/~rongge/))
- Look into the training trajectory of **over-parameterized non-orthogonal tensor decomposition:** we observe **very different behavior from the deflation process** displayed in the orthogonal tensor trajectory. Though the learning process is still low-rank, an already-fitted component cannot always stay fitted; instead, it will **split into two directions** and form two new components.
- Theoretically analyze a simple case of decomposing a non-orthogonal ground-truth tensor. Based on the toy model, we use **the Hessian near the local minimizers** to capture the dynamics of the splitting phenomenon under over-parameterized models.
- Design **a heuristic algorithm** and attempt to provide theoretical and empirical evidence that the algorithm is mathematically **equivalent to the gradient flow trajectory** with infinitesimal initialization for the non-orthogonal over-parameterized tensor decomposition objective.

### **Understanding EoS Training Dynamics with a Minimalist Example**
<p align = "right"> 6.2022 – 10.2022</p>

Student Research Intern, advised by [Prof. Rong Ge]([Rong Ge, Duke University](https://users.cs.duke.edu/~rongge/))
- Focus on understanding the convergence in the **EoS** regime: despite the occurrence of **EoS**, the loss oscillates and converges eventually to some minimum. **The sharpness at the end is just slightly below** 2/η **(valid for different initialization & step size)** in various settings.
- Show that many well-understood nonconvex objectives (e.g. matrix factorization or two-layer linear networks) can also converge when EoS happens, there is often **a larger gap between the sharpness of the endpoint and** 2/η**.**
- Study EoS phenomenon from the first principle by constructing **a minimalist scalar network** with **rigorous analysis for its training dynamics**. We also show why a simpler scalar network cannot display the sharpness concentration and adaptivity property, implying the importance of **depth** for EoS to happen.
- Empirically observe **similar trajectories in several real-world neural networks** trained on CIFAR-10.

### **Analyzing Sharpness: Progressive Sharpening and Edge of Stability**
<p align = "right"> 2.2021 – 5.2022</p>

Independent research project together with Zhouzi Li, advised by [Prof. Jian Li]([Jian Li's Homepage (tsinghua.edu.cn)](http://people.iiis.tsinghua.edu.cn/~jianli/))
- Focus on the explanation for **Edge of Stability (EoS, first discovered by Cohen et al. 2021):** first, the **sharpness** (the largest eigenvalue of the Hessian matrix of the training objective) increases steadily to the value 2/η (the **progressive sharpening** phase, η is the step size); then, it oscillates around this value (the **EoS** phase). However, the loss keeps decreasing monotonically though the conventional L-smoothness assumption is violated. This phenomenon is beyond the scope of traditional optimization theory. 
- Divide the GD trajectory into four phases according to the sharpness and the stability threshold 2/η.
-  Empirically identify the norm of output layer weight as an interesting indicator of the sharpness dynamics, and **heuristically explain the dynamics of various essential quantities (including the training loss and** **the sharpness) in each phase of EoS** for general neural networks under a set of assumptions.
- Theoretically **prove the sharpness behavior** in the **EoS regime** in a **two-layer fully-connected linear neural network** with less and weaker assumptions.
