# Not All Features Are Created Equal — Project Page

Project page for "Not All Features Are Created Equal: A Mechanistic Study of Vision-Language-Action Models" (RSS 2026).

## Live Links

- **Project Page:** (this repo, deploy via GitHub Pages)
- **Action Atlas:** [action-atlas.com](https://action-atlas.com)
- **Code:** [github.com/CWRU-AISM/vla_interp](https://github.com/CWRU-AISM/vla_interp) (releasing soon)

## Deploying

This is a static site. To deploy on GitHub Pages:

1. Push this repo to GitHub (e.g., `CWRU-AISM/CWRU-AISM.github.io` or `CWRU-AISM/vla-interp-page`)
2. Go to Settings > Pages > Source: Deploy from branch `main` / `root`
3. The site will be live at the corresponding GitHub Pages URL

For local preview, just open `index.html` in a browser.

## Structure

```
vla-interp-page/
├── index.html              # Main project page (single page, all sections)
├── static/
│   ├── css/
│   │   ├── bulma.min.css   # Bulma CSS framework
│   │   ├── fontawesome.all.min.css
│   │   └── index.css       # Custom styles
│   ├── js/
│   │   └── fontawesome.all.min.js
│   └── images/
│       ├── fig1_core_findings.png
│       ├── fig2_sae_ev.png
│       ├── fig3_temporal.png
│       ├── fig4_goldilocks.png
│       ├── fig5_language.png
│       ├── fig6_probes.png
│       ├── fig7_spider_comparison.png
│       ├── fig8_summary.png
│       ├── qualitative_grid_enhanced.png
│       └── qualitative_multi_concept.png
├── .gitignore
└── README.md
```

## Credits

Website template structure inspired by [Nerfies](https://nerfies.github.io/).
