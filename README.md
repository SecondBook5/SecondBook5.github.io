# AJ Book — Research Portfolio

This repository contains the source for [secondbook5.github.io](https://secondbook5.github.io/), my research portfolio and academic CV.

The site summarizes my work in spatial regulatory biology, systems immunology, cell-state dynamics, and reproducible computational biology. It includes selected projects, publications, presentations, research experience, education, and technical competencies.

## Repository structure

- `_data/data.yml` — biography, research focus, projects, education, experience, and competencies
- `_data/publications.yml` — publications and preprints
- `_includes/` — reusable Jekyll sections
- `_layouts/` — page layouts
- `assets/` — stylesheets, images, and supporting assets
- `index.html` — homepage section order

## Local development

The site is built with Jekyll. To run it locally:

```bash
git clone https://github.com/SecondBook5/SecondBook5.github.io.git
cd SecondBook5.github.io
bundle install
bundle exec jekyll serve
```

The preview will be available at [http://localhost:4000](http://localhost:4000).

Docker is also supported:

```bash
docker-compose up
```

## Deployment

The site is published through GitHub Pages from the `master` branch. Changes should be previewed locally before they are merged.

## Theme attribution

The site is adapted from the [Orbit](https://themes.3rdwavemedia.com/bootstrap-templates/resume/orbit-free-resume-cv-bootstrap-theme-for-developers/) CV theme by Xiaoying Riley and the [online-cv](https://github.com/sharu725/online-cv) Jekyll implementation.
