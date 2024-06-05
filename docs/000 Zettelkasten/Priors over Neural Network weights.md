---
tags:
  - dl_theory
  - equivariance
share: true
---
From [[Understanding Deep Learning - Chapter 10|Understanding Deep Learning - Chapter 10]], 1d convolutions can be represented as weight matrices from a MLP with a specific prior where the diagonals are the same (d).
![[Pasted image 20240605141546.png|Pasted image 20240605141546.png]]

---

Rotationally equivariant convolutions can be implemented by isotropic filters (a prior on the conv2d weight):
![[Pasted image 20240605142432.png|Pasted image 20240605142432.png]]