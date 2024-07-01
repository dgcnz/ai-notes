---
authors:
  - "[[Timothée Darcet|Timothée Darcet]]"
  - "[[Maxime Oquab|Maxime Oquab]]"
  - "[[Julien Mairal|Julien Mairal]]"
  - "[[Piotr Bojanowski|Piotr Bojanowski]]"
year: 2023
tags:
  - paper
  - vit
  - dl_theory
url: https://arxiv.org/pdf/2309.16588
share: true
---
> [!tldr] Abstract
> Transformers have recently emerged as a powerful tool for learning visual representations. In this paper, we identify and characterize artifacts in feature maps of both supervised and self-supervised ViT networks. The artifacts correspond to high-norm tokens appearing during inference primarily in low-informative background areas of images, that are repurposed for internal computations. We propose a simple yet effective solution based on providing additional tokens to the input sequence of the Vision Transformer to fill that role. We show that this solution fixes that problem entirely for both supervised and self-supervised models, sets a new state of the art for self-supervised visual models on dense visual prediction tasks, enables object discovery methods with larger models, and most importantly leads to smoother feature maps and attention maps for downstream visual processing.


## Note

- note to myself:
	- [ ] Read paper in depth #personal 🔼 