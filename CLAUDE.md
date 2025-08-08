# CLAUDE.md
すべて日本語で回答してください。

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is Yuki Takeyama's portfolio website built with Hugo static site generator. The site is bilingual (English/Japanese) and showcases personal information, research, projects, and work experience. It uses the PaperMod theme and is deployed to GitHub Pages.

## Development Commands

### Build the site
```bash
hugo -d docs
```
This builds the static site and outputs to the `docs/` directory, which is used for GitHub Pages deployment.

### Local development server
```bash
hugo server --disableFastRender
```
This starts a local development server with live reload. The `--disableFastRender` flag ensures all changes are properly rebuilt.

### Other useful Hugo commands
```bash
hugo server --buildDrafts     # Include draft content
hugo server --buildFuture     # Include future-dated content
```

## Site Architecture

### Multi-language Configuration
- Default language: English (`en`)
- Secondary language: Japanese (`ja`)
- Content structure:
  - `content/en/` - English content
  - `content/ja/` - Japanese content
- Language-specific menus and permalinks are configured in `config.toml`

### Key Configuration Files
- `config.toml` - Main Hugo configuration with theme settings, languages, and site parameters
- `static/` - Static assets (images, documents)
- `layouts/shortcodes/image.html` - Custom shortcode for responsive images

### Content Structure
Main content sections:
- `about.md` - Personal information and biography
- `research.md` - Academic research and publications  
- `project.md` - Personal projects and developments
- `workexp.md` - Professional work experience

### Theme and Styling
- Uses PaperMod theme
- Profile mode enabled on homepage
- Custom favicon and social icons configured
- Responsive image handling via custom shortcode

### Deployment
- Builds to `docs/` directory for GitHub Pages
- Base URL: https://takeyamayuki.github.io
- Static files served from `static/img/` directory

## Content Editing Guidelines

When editing content:
- Maintain consistent frontmatter structure across both languages
- Use proper Hugo markdown syntax
- Images should be placed in `static/img/` and referenced as `/img/filename`
- Use the custom `{{< image >}}` shortcode for responsive images
- Keep bilingual content synchronized between `en/` and `ja/` directories

## Theme Customization

The site uses minimal customizations:
- Custom image shortcode in `layouts/shortcodes/image.html`
- PaperMod theme configured in profile mode
- Social icons and contact information in site params