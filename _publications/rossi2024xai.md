---
layout: publication
title: "Towards Grounded Explanations for Vision Transformers"
authors:
  - Anna Rossi
  - Jane Doe
venue: CVPR 2024
year: 2024
type: conference
abstract: >
  We introduce a post-hoc explanation method for Vision Transformers that
  generates both visual saliency maps and natural language justifications
  aligned with human annotator judgements.
pdf: https://arxiv.org/abs/2402.00000
code:
arxiv: "2402.00000"
doi:
tags:
  - Explainable AI
  - Computer Vision
plotly: false
---

## Key Contributions

- A gradient-routing mechanism that produces faithful saliency maps for ViT patch tokens
- A lightweight language decoder jointly trained with contrastive supervision
- A user study (n=120) showing a 37% improvement in user trust over GradCAM baselines

## BibTeX

```bibtex
@inproceedings{rossi2024xai,
  title     = {Towards Grounded Explanations for Vision Transformers},
  author    = {Rossi, Anna and Doe, Jane},
  booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  year      = {2024}
}
```
