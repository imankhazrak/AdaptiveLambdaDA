# Adaptive Gradient-Norm Weighting for Improved Domain Adversarial Training

This repository accompanies the paper:

**"Adaptive Gradient-Norm Weighting for Improved Domain Adversarial Training"**  
*Authors: Iman Khazrak, Mostafa M. Rezaee, Robert C. Green II*  

---

## Overview

Unsupervised Domain Adaptation (UDA) aims to transfer knowledge from a labeled source domain to an unlabeled target domain under distribution shift. Two widely used frameworks—**Deep Adaptation Network (DAN)** and **Domain-Adversarial Neural Network (DANN)**—combine a classification loss with a domain alignment loss.  
A key challenge in these methods is determining the trade-off coefficient **λ**, which controls the relative importance of domain alignment.  

We propose a **gradient-norm adaptive loss weighting scheme** that dynamically adjusts λ at each training iteration based on the ratio of the gradient magnitudes of the classification and alignment losses. This approach removes the need for manual scheduling, improves training stability, and enhances performance on benchmarks such as **Office-31, MNIST→MNIST-M, and SVHN→MNIST**.  

---

## Key Contributions

- **Adaptive Loss Balancing:** Automatically adjusts λ using gradient norms to balance competing objectives.  
- **Improved Transfer Learning Performance:** Demonstrates superior accuracy compared to standard DAN and DANN.  
- **Generalizable Method:** Lightweight, requires minimal tuning, and can be extended to other multi-loss and multitask learning problems.  

---

## Repository Status

At this stage, this repository serves as a **placeholder**.  
- **Source code and datasets will be made publicly available after the paper has completed the review process and is formally accepted.**  
- Until then, only this documentation is provided to describe the project.  
- This restriction ensures compliance with the review process and prevents premature disclosure of implementation details.  

---
