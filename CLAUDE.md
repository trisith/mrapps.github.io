# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Jekyll-based freelancer portfolio landing page for GitHub Pages (mrapps.github.io).

## Commands

```bash
# Local development (requires Ruby and Jekyll)
bundle install
bundle exec jekyll serve

# Site builds automatically on GitHub Pages when pushed to main branch
```

## Architecture

Static Jekyll site with single-page layout:

- `_config.yml` - Site configuration (title, description, URL)
- `_layouts/default.html` - Base HTML layout template
- `index.html` - Main landing page with all sections (Hero, Services, Portfolio, About, Contact)
- `assets/css/style.css` - All styling

## Deployment

Push to the `main` branch - GitHub Pages builds and deploys automatically. No build step required locally.

## Customization

Edit `index.html` to update:
- Contact email (search for `your-email@example.com`)
- Form endpoint (search for `formspree.io/f/your-form-id`)
- Portfolio projects
- Skills and percentages
- Social links in footer
