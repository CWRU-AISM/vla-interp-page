# Not All Features Are Created Equal

### A Mechanistic Study of Vision-Language-Action Models

[Bryce Grant](https://bryceag11.github.io), [Xijia Zhao](https://xijiazhao.github.io/), [Peng Wang](https://pengwangucla.github.io/)<br>
Case Western Reserve University

ICLR 2026 Multimodal Intelligence Workshop (Oral)

<a href="https://arxiv.org/abs/2603.19233"><img src="https://img.shields.io/badge/arXiv-2603.19233-b31b1b.svg" alt="arXiv"></a>
<a href="https://cwru-aism.github.io/vla-interp-page/"><img src="https://img.shields.io/badge/Project-Page-blue" alt="Project Page"></a>
<a href="https://action-atlas.com"><img src="https://img.shields.io/badge/Action%20Atlas-Live%20Demo-1a1a2e" alt="Action Atlas"></a>
<a href="https://huggingface.co/collections/bag100/action-atlas"><img src="https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Collection-yellow" alt="Hugging Face"></a>

Project page for a mechanistic interpretability study of Vision-Language-Action (VLA) models. We train per-token sparse autoencoders and apply causal interventions (activation injection, ablation, feature steering) across six VLA architectures to show that fine-tuned VLAs execute coordinate-bound motor programs.

## Action Atlas

The interactive feature-exploration platform is live at [action-atlas.com](https://action-atlas.com): UMAP feature explorer, layer circuits, ablation comparisons, and rollout videos across all six models.

## Deploying

This is a static site served over GitHub Pages from the `master` branch.

1. Push to GitHub (`CWRU-AISM/vla-interp-page`).
2. Settings > Pages > Source: Deploy from branch `master` / root.
3. The site goes live at the corresponding GitHub Pages URL.

For local preview, run `python serve.py` and open the printed URL, or open `index.html` directly.

## Structure

```
vla-interp-page/
├── index.html        Main project page
├── tutorial.html     Setup and tutorial page
├── serve.py          Local preview server
├── paper.pdf         Paper
└── static/
    ├── css/          Bulma, FontAwesome, custom styles
    ├── js/           FontAwesome bundle
    ├── images/       Figures
    └── videos/       Hero background
```

## Credits

Website template structure inspired by [Nerfies](https://nerfies.github.io).
