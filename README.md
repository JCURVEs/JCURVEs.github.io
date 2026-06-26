# JCURVEs.github.io

Personal publishing space for technical notes, experiments, and web-based reports.

Live site: [https://jcurves.github.io/](https://jcurves.github.io/)

## What This Site Is For

This site is being refocused from a default Jekyll theme fork into a public index for:

- AI and automation experiments
- Technical reports and research notes
- Smart building, digital twin, and energy infrastructure analysis
- Personal knowledge-base outputs that are useful enough to publish

## Featured Page

- [AI Report 2026](https://jcurves.github.io/ai-report-2026/)  
  A graduate-school technical report on the 2020-2026 AI transition, comparing large general-purpose models with lightweight specialized models and connecting the discussion to data centers, energy efficiency, and industrial execution.

## Repository Structure

```text
.
├── ai-report-2026/          # Static report page served from the root source
├── docs/ai-report-2026/     # Static report page mirrored for docs-source Pages setup
├── _posts/                  # Jekyll posts
├── _pages/                  # Jekyll pages
├── assets/                  # Shared site assets
└── _config.yml              # Jekyll site configuration
```

The report page is mirrored in both `ai-report-2026/` and `docs/ai-report-2026/` because the historical Pages setup may use either root or `docs` as the publishing source.

## Publishing Workflow

1. Add or update a static page under a dedicated folder.
2. Keep page assets local to that folder when possible.
3. Commit to `master`.
4. Push to GitHub.
5. Verify the deployed URL on GitHub Pages.

## Local Notes

This repository still contains the Minimal Mistakes Jekyll theme structure. The next cleanup step is to simplify the site configuration, remove unused demo/theme content, and turn the homepage into a focused index of projects and published notes.

## Credits

The original site structure is based on the [Minimal Mistakes Jekyll theme](https://github.com/mmistakes/minimal-mistakes).
