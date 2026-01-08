# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Jekyll-based personal blog hosted on GitHub Pages. It uses the Minima theme and is called "Junk Drawer" - a personal blog for documenting thoughts and activities.

## Build & Development Commands

```bash
# Local development (requires Jekyll installed)
bundle exec jekyll serve

# Build the site
bundle exec jekyll build

# Install dependencies
bundle install
```

## Architecture

- **Theme**: Minima (Jekyll's default theme)
- **Hosting**: GitHub Pages (auto-builds on push to main)
- **Content**: Markdown files in `_posts/` with YYYY-MM-DD-title.md naming convention

### Key Files

- `_config.yml` - Site configuration (title, description, author, theme)
- `index.md` - Homepage content
- `_layouts/post.html` - Custom post layout that adds published/last_modified dates
- `_posts/` - Blog post content in Markdown

### Post Front Matter

Posts support these front matter fields:
```yaml
layout: post
title: Post Title
date: YYYY-MM-DD
last_modified: YYYY-MM-DD  # Optional - displays "Last updated" if present
```
